# Programming
The project is created to learning *Javascript* and *Python3*, but beginning with C++ on [Tsinghua X_2015_T2](http://www.xuetangx.com/courses/course-v1:TsinghuaX+30240233X_2015_T2+sp/info), I wrote down the notes reference from [MichaelLiao](https://www.liaoxuefeng.com/) and some demos during learning to review later!      

*Text editor*：1. [Dev-C++](https://sourceforge.net/projects/orwelldevcpp/) 2. [Visual Studio Code](https://code.visualstudio.com/) 3. [Notepad ++](https://notepad-plus-plus.org/download/v7.5.3.html)   

Also welcome to visit the [Programming_CN](https://github.com/007tom/Programming_CN)!
## Ⅰ. Knowledge Point     

	Attention: 
		
		1. All of the languages below is sensitive to case;
		
		2. ';' indicates that the end of a sentence;
		
		3. Please indent with "Tab" key or 4 keyboard instead;
	
### 1. *C++*

	Tip:

		Attention to priority of opertators.
		
#### 1.1 The meaning of program design:

```
	#include <iostream>  // include library functions
	using namespace std; // namespace 
	/* the main function */
	int main() {
	
		return 0;
	}
```

### 2. *Javascript*

#### 2.1 Data Type:
(1) Number:

+ no distinction between int and float;
+ *NaN*, standing for '*Not a Number*', is used when sentences can not be computed! 
+ *Infinity* represents much great number, when used in case that the number exceed maximum!
```
	0 / 0; // NaN
	2 / 0; // Infinity
```

(2) String:

(3) Boolean: true false

### 3. *Python3*   

## Ⅱ. Demos
### 1/33. Shopping
  Description:       
  
                           |    *price*    >>> *amount*
               *Tomatos*   | ￥7.9 yuan/kg >>>  0.8kg
               *Eggs*      | ￥9.5 yuan/kg >>>  1.5kg
               *Cucumbers* | ￥8.7 yuan/kg >>>  0.6kg
               
   Question: How much the total vegetables?
   
#### *C++* edition

 ```
#include <iostream>
using namespace std;

int main()
{
	cout << 7.9 * 0.8 + 9.5 * 1.5 + 8.7 * 0.6 << endl;
	return 0;
}
  ```
     
#### *Python3* edition   

  ```
print(7.9 * 0.8 + 9.5 * 1.5 + 8.7 * 0.6)
  ```   
     
#### *Javascript* edition   
 
  ```
  console.log(7.9 * 0.8 + 9.5 * 1.5 + 8.7 * 0.6)
  ```   
     
### 2/33. 
