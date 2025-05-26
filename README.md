# CPP

# اسکلت تمامی برنامه هایی که با cpp نوشته میشن

<p>
  
```cpp
#include <iostream> //فرا خوانی کنابخانه ای به اسم iostream

using namespace std; // در همه ی برنامه ها ثابت هست

// برنامه ای که میخواهیم بنویسیم را در این بخش مینویسیم
int main(){
  return 0;
}
```
</p>

<p aling = 'center'>
  تمامی این خط های کد ثابت هستن و در هر برنامه ای باید نوشته بشن
</p>

# معرفی دستور `cout`

این دستور مخفف character output هست که هر چیزی که بنویسیم را در خروجی به ما میدهد. فرم کلی ان به صورت زیر است.

```cpp
cout << "" << endl;
```

### مثال :


```cpp
#include <iostream>
using namespace std;

int main (){

  // استفاده از دستور cout برای نشان دادن خروجی تحت عنوان Hello world :)
  cout << "Hello world :)" << endl;
  return 0;
}

```

# معرفی کامت ها در cpp

کامنت ها در cpp با علامت // نشان داده میشوند که این بخش از کد در روند برنامه هیچ تاثیری ندارند

### مثال :

```cpp
#include <iostream>
using namespace std;

int main (){

// این متن نوشته شده توسط کامپایلر نادیده گرفته میشود و هیج تاثیری در برنامه ندارد
// کامنت دوم
// 3rd comment
  return 0;
}
```


# انواع داده ها و متغیر ها

پرکاربرد ترین نوع داده ها در cpp

- `int` : اعداد صحیح.
- `float` : اعداد اعشاری 
- `string` : جمله یا رشته
- `char` : کاراکترها (مانند 'A').
- `bool` : مقادیر درست (true) و غلط (false).ا

### مثال: 

```cpp
int age = 25;
float height = 1.75;
char grade = 'A';
bool isStudent = true;
```

### به مثال زیر توجه کنید


```cpp
#include <iostream>
using namesapace std;

int main(){

  char name = 'H';
  int age = 23 ;

cout << age << " " << name << endl;
return 0;
}
```

Autor : [Saed Gholipour](https://github.com/saed-gpr)
