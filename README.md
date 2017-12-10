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

	* Operators:
	
	1. && 'and', || 'or', ! 'not';
	
	2. Comprision operators:　> >= < <= == ===
	
		* == could transfer the data type automatically and then compare them, so we have better using === to do comparision.
		
		* NaN is equal to nothing included itself:
		
			NaN === NaN; // false
			
		the only way to judge it is to use the function named isNaN():
		
			isNaN(NaN); // true
			
		* float comparision:
		
			1/3 === (1 - 2/3); // false
			
		Opps! the right way is to compute ABS of their difference and then to compare with a threshold:
		
			Math.abs(1/3 - (1 - 2/3)) < 0.0000001; // true
			
(4) null, undefined

	* null, 0, ''
	
	1. null is represented data which value is nothing, and it is associated with None in Python;
	
	2. 0 is a number;
	
	3. '' is a string which length is 0.
	
	* undefined means that data has not defined;
	
	* Usually, we prefer to use null unless we have to judge whether premeters of function have delivered.
	
(5) Array:

	* Odered sets, could contains all type of data.
	
	* Ways to make a array:
	
		1. [a, b];
		2. new.Array(a, b);
		
	for better readability code, we highly recommended to use the formmer to create a array.
	
	* Access: using index
	
			arr[0]; // visit the 1st element. output: a
			arr[2]; // undefined
			

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
