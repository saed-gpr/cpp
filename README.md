# CPP
# جلسه اول
### اسکلت تمامی برنامه هایی که با cpp نوشته میشن

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

# معرفی دستور `cin`

این دستور میتواند از کاربر ورودی ای را بگیرد. همچنین این دستور مخفف character input هست

```cpp
#include <iostream>
using namespace std;

int main (){

  cout << "enter your age:" << endl;
  int age;
  cin >> age;
  return 0;
}
```


# تمرین جلسه اول:

برنامه ای بنویسید که جمله enter your age را به کاربر نشان دهد و منتظر باشد که کاربر سن خود را وارد کند و سپس سن او را در خروجی چاپ کند.

# جلسه دوم

#### انواع عملگر ها:

- عملگرهای محاسباتی (+, -, *, /, %)
- عملگرهای مقایسه‌ای (==, !=, <, >, <=, >=)
- عملگرهای منطقی (&&, ||, !)
- عملگرهای ترکیبی (+=, -=, *=, ...)


### مثال

```cpp
#include <iostream>
using namespace std;

int main (){

	int a = 10, b = 3;
	cout << "Sum: " << a + b << endl;
	cout << "Remainder: " << a % b << endl;
	cout << "tafrigh: " << a - b << endl;
  
  return 0;
}
```


عملیات مقایسه‌ای
```cpp

a == b; // برابر است؟
a != b; // نابرابر است؟
a > b;  // بزرگ‌تر است؟
```
عملیات منطقی
```cpp
a > 5 && b < 10; // و
a > 5 || b < 10; // یا
!a;              // نقیض
```

# ساختار های شرطی

دستور if


```cpp
int age = 20;
if (age >= 18) {
    cout << "You are an adult." << endl;
}
```

دستور if-else

```cpp
if (age >= 18) {
    cout << "You can vote." << endl;
} else {
    cout << "You are too young to vote." << endl;
}
```

### تمرین جلسه دوم

فرض کنید قرار است که برنامه یک سیستمی را مینویسید که فقط باید افراد 20 سال به بالا به ان دسترسی یابد. در مرحله اول این برنامه باید سن کاربر را بپرسد و اگر سن کاربر 20 یا بالاتر بود عبارت done رو به عنوان خروجی نمایش دهد و اگر سن کاربر کمتر از 20 بود عبارت exit رو به عنوان مثال نمایش دهد
Author : [Saed Gholipour](https://github.com/saed-gpr)
