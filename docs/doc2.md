#Global Functions

---
# formatInt
```as
string formatInt(int64 val, const string&in options = "", uint width = 0)
```
### arguments
int64 val;

string options = "";

uint width = 0;


---
# formatUInt
```as
string formatUInt(uint64 val, const string&in options = "", uint width = 0)
```
### arguments
uint64 val;

string options = "";

uint width = 0;


---
# formatFloat
```as
string formatFloat(double val, const string&in options = "", uint width = 0, uint precision = 0)
```
### arguments
double val;

string options = "";

uint width = 0;

uint precision = 0;


---
# parseInt
```as
int64 parseInt(const string&in, uint base = 10, uint&out byteCount = 0)
```
### arguments
string ;

uint base = 10;

uint byteCount = 0;


---
# parseUInt
```as
uint64 parseUInt(const string&in, uint base = 10, uint&out byteCount = 0)
```
### arguments
string ;

uint base = 10;

uint byteCount = 0;


---
# parseFloat
```as
double parseFloat(const string&in, uint&out byteCount = 0)
```
### arguments
string ;

uint byteCount = 0;


---
# RegisterCallback
```as
void RegisterCallback(const string callbackName, CreateMoveDef@ cb)
```
### arguments
string callbackName;

CreateMoveDef cb;


---
# PrintStr
```as
void PrintStr(const string&in str)
```
### arguments
string str;

