
# array
## Behaviors
```cpp
void $beh5()
void $beh6()
int $beh9()
void $beh10()
bool $beh11()
void $beh12(int&in)
void $beh13(int&in)
bool $beh8(int&in, bool&out)
T[]@ $list(int&in type, int&in list) { repeat T }
```
---
## Methods
### opIndex
```cpp
T& opIndex(uint index)
```

### opIndex
```cpp
const T& opIndex(uint index) const
```

### opAssign
```cpp
T[]& opAssign(const T[]&in)
```

### insertAt
```cpp
void insertAt(uint index, const T&in value)
```

### insertAt
```cpp
void insertAt(uint index, const T[]&inout arr)
```

### insertLast
```cpp
void insertLast(const T&in value)
```

### removeAt
```cpp
void removeAt(uint index)
```

### removeLast
```cpp
void removeLast()
```

### removeRange
```cpp
void removeRange(uint start, uint count)
```

### length
```cpp
uint length() const
```

### reserve
```cpp
void reserve(uint length)
```

### resize
```cpp
void resize(uint length)
```

### sortAsc
```cpp
void sortAsc()
```

### sortAsc
```cpp
void sortAsc(uint startAt, uint count)
```

### sortDesc
```cpp
void sortDesc()
```

### sortDesc
```cpp
void sortDesc(uint startAt, uint count)
```

### reverse
```cpp
void reverse()
```

### find
```cpp
int find(const T&in value) const
```

### find
```cpp
int find(uint startAt, const T&in value) const
```

### findByRef
```cpp
int findByRef(const T&in value) const
```

### findByRef
```cpp
int findByRef(uint startAt, const T&in value) const
```

### opEquals
```cpp
bool opEquals(const T[]&in) const
```

### isEmpty
```cpp
bool isEmpty() const
```

### sort
```cpp
void sort(array::less&in, uint startAt = 0, uint count = uint ( - 1 ))
```

