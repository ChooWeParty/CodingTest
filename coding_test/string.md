## 문자열 입력

- **한줄 입력 받기**: `getline(cin, s); // s에 저장된 마지막 문자는 '\n'`
- **공백문자 기준 저장**: `scanf("%d", i);`
- **개행문자 무시**: `cin.ignore();`
- **입력 버퍼 초기화**: `cin.clear()`

## string 함수
- **assign(), 문자열을 할당**
```
s = "ABCDEF"
string s1, s2, s3;
s1.assign("ABCDEFG"); // s1 = "ABCDEFG"
s2.assign(3, 'a'); // s2 = "aaa"
s3.assign(s, 2, 4): //s3 = "CDEF" 2번째부터 4개  
```
- **append(), 문자열 붙이기**
```
s.append("ABCDEF"); // s = "ABCDEF"
s.append(3, 'x'); // s = "ABCDEFxxx"
s2.append(s, 2, 4); // s2 = "CDEF"
```
- **erase(), 문자열 삭제**
```
s.erase(0, 3); // 인덱스 0부터 3개 삭제
```
- **find(), 문자열 찾기, 시작 위치 반환**
```
string s1 = "abcd";
string s2 = "b";
int location = s1.find(s2);
int location = s1.find(s2, x);
```
- **replace(), 문자열 대체**
```
string s = "abc_def";
s.replace(4, 3, "zzz"); // s= "abc_zzz"
```
- **insert(), 문자열 삽입**
```
string s = "ABCDEF"
s.insert(2, "xx"); // s = "ABxxCDEF"
```
- **at(), 특정위치 문자를 엑세스**
```
string s = "ABCDEF"
char c = s.at(3); // c = 'D'
```
- **strlen(), string -> char\***
```
string s = "ABCDEF"
int length = (strlen(s.c_str());
```