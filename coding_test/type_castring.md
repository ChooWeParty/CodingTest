## char -> integer
 - ### 함수 이용 x
```
char a = '1';
int i = a - '0';
```
 - ### 함수 이용
```
char str[] = "123";
int i = 10;
int i_ch;
i_ch = atoi(str); 
// "2005년도 10월" -> 2005
```
## char -> float
```
float f;
d = atof(str);
```
## integer -> char
```
int i = 10;
char c_int[10];
itoa(i, c_int, 10); // int 변수, 저장할 char 변수, 진수
```
## string - >int
```
string str = "34";
int i = atoi(str.c_str());
// atoi(char*)
```
## int -> string
```
int i = 5;
string str = to_string(i);
```
## StringBuffer, StringBuilder  (*in java*)
 - StringBuffer : Multi-Thread
 - StringBuilder : Single-Thread

## 헤더파일
`<cstdlib>`, `<string>`, `<iostream>`

## char* -> string
```
char* cStr = "Cstring";
string cppStr = cStr;
```
## string -> char*
```
string s = "cPstring";
const char* c = s.c_str();
```
## char* -> int
```
char* c = "201";
int num = atoi(cstr);
```
## string -> char* -> int
```
string s = "2017";
int i = atoi(s.c_str());
```