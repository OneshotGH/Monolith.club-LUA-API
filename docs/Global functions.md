---
### formatInt
```cpp
string formatInt(int64 val, const string&in options = "", uint width = 0)
```
int64 val;

string options = "";

uint width = 0;


---
### formatUInt
```cpp
string formatUInt(uint64 val, const string&in options = "", uint width = 0)
```
uint64 val;

string options = "";

uint width = 0;


---
### formatFloat
```cpp
string formatFloat(double val, const string&in options = "", uint width = 0, uint precision = 0)
```
double val;

string options = "";

uint width = 0;

uint precision = 0;


---
### parseInt
```cpp
int64 parseInt(const string&in, uint base = 10, uint&out byteCount = 0)
```
string ;

uint base = 10;

uint byteCount = 0;


---
### parseUInt
```cpp
uint64 parseUInt(const string&in, uint base = 10, uint&out byteCount = 0)
```
string ;

uint base = 10;

uint byteCount = 0;


---
### parseFloat
```cpp
double parseFloat(const string&in, uint&out byteCount = 0)
```
string ;

uint byteCount = 0;


---
### RegisterCallback
```cpp
void RegisterCallback(const string callbackName, CreateMoveDef@ cb)
```
string callbackName;

CreateMoveDef cb;


---
### PrintStr
```cpp
void PrintStr(const string&in str)
```
string str;
