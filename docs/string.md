
## Behaviors
```cpp
~string()
string()
string(const string&in)
```
---
## Methods
### opAssign
```cpp
string& opAssign(const string&in)
```

### opAddAssign
```cpp
string& opAddAssign(const string&in)
```

### opEquals
```cpp
bool opEquals(const string&in) const
```

### opCmp
```cpp
int opCmp(const string&in) const
```

### opAdd
```cpp
string opAdd(const string&in) const
```

### length
```cpp
uint length() const
```

### resize
```cpp
void resize(uint)
```

### isEmpty
```cpp
bool isEmpty() const
```

### opIndex
```cpp
uint8& opIndex(uint)
```

### opIndex
```cpp
const uint8& opIndex(uint) const
```

### opAssign
```cpp
string& opAssign(double)
```

### opAddAssign
```cpp
string& opAddAssign(double)
```

### opAdd
```cpp
string opAdd(double) const
```

### opAdd_r
```cpp
string opAdd_r(double) const
```

### opAssign
```cpp
string& opAssign(float)
```

### opAddAssign
```cpp
string& opAddAssign(float)
```

### opAdd
```cpp
string opAdd(float) const
```

### opAdd_r
```cpp
string opAdd_r(float) const
```

### opAssign
```cpp
string& opAssign(int64)
```

### opAddAssign
```cpp
string& opAddAssign(int64)
```

### opAdd
```cpp
string opAdd(int64) const
```

### opAdd_r
```cpp
string opAdd_r(int64) const
```

### opAssign
```cpp
string& opAssign(uint64)
```

### opAddAssign
```cpp
string& opAddAssign(uint64)
```

### opAdd
```cpp
string opAdd(uint64) const
```

### opAdd_r
```cpp
string opAdd_r(uint64) const
```

### opAssign
```cpp
string& opAssign(bool)
```

### opAddAssign
```cpp
string& opAddAssign(bool)
```

### opAdd
```cpp
string opAdd(bool) const
```

### opAdd_r
```cpp
string opAdd_r(bool) const
```

### substr
```cpp
string substr(uint start = 0, int count = - 1) const
```

### findFirst
```cpp
int findFirst(const string&in, uint start = 0) const
```

### findFirstOf
```cpp
int findFirstOf(const string&in, uint start = 0) const
```

### findFirstNotOf
```cpp
int findFirstNotOf(const string&in, uint start = 0) const
```

### findLast
```cpp
int findLast(const string&in, int start = - 1) const
```

### findLastOf
```cpp
int findLastOf(const string&in, int start = - 1) const
```

### findLastNotOf
```cpp
int findLastNotOf(const string&in, int start = - 1) const
```

### insert
```cpp
void insert(uint pos, const string&in other)
```

### erase
```cpp
void erase(uint pos, int count = - 1)
```

### split
```cpp
string[]@ split(const string&in) const
```

