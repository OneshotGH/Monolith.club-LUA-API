
## Behaviors
```cpp
Vector()
Vector(float x, float y, float z)
```
---
## Fields
```cpp
float x;
float y;
float z;
```
---
## Methods
### opAssign
```cpp
Vector& opAssign(Vector&in other)
```

### opIndex
```cpp
bool opIndex(Vector&in other)
```

### opEquals
```cpp
Vector& opEquals(Vector&in other)
```

### opEquals
```cpp
Vector& opEquals(float other)
```

### opSubAssign
```cpp
Vector& opSubAssign(Vector&in other)
```

### opSubAssign
```cpp
Vector& opSubAssign(float other)
```

### opMulAssign
```cpp
Vector& opMulAssign(Vector&in other)
```

### opMulAssign
```cpp
Vector& opMulAssign(float other)
```

### opDivAssign
```cpp
Vector& opDivAssign(Vector&in other)
```

### opDivAssign
```cpp
Vector& opDivAssign(float other)
```

### opAdd
```cpp
Vector opAdd(Vector&in other)
```

### opSub
```cpp
Vector opSub(Vector&in other)
```

### opMul
```cpp
Vector opMul(Vector&in other)
```

### opMul
```cpp
Vector opMul(float other)
```

### opDiv
```cpp
Vector opDiv(Vector&in other)
```

### opDiv
```cpp
Vector opDiv(float other)
```

### LengthSqr
```cpp
float LengthSqr()
```

### Length2DSqr
```cpp
float Length2DSqr()
```

### Length
```cpp
float Length()
```

### Length2D
```cpp
float Length2D()
```

### Normalize
```cpp
void Normalize()
```

### Normalized
```cpp
Vector Normalized()
```

### Cross
```cpp
Vector Cross(Vector&in other)
```

### DistTo
```cpp
float DistTo(Vector&in other)
```

### DistToSqr
```cpp
float DistToSqr(Vector&in other)
```

### Extrapolate
```cpp
Vector Extrapolate(Vector&in pos, float t)
```

### Interpolate
```cpp
Vector Interpolate(Vector&in pos, float t)
```

### Dot
```cpp
float Dot(Vector&in other)
```

### Dot
```cpp
float Dot(float&in other)
```

