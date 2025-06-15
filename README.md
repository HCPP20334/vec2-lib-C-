# vec2.h - Lightweight 2D Vector Library for C++

![C++11](https://img.shields.io/badge/C++-11-blue.svg)
![License](https://img.shields.io/badge/License-MIT-green.svg)

A header-only library providing 2D vector structures with various numeric types.

## Features

- 🚀 **6 vector types** (int8/16/32/64, float64, double64)
- 🔒 **Bounds-checked access** via `operator[]`
- 📏 **Size utilities** for each vector type
- 🏗 **constexpr constructors** for compile-time use
- 💻 **Single-header** design (just include `vec2.h`)

## Installation

Simply copy `vec2.h` to your project's include directory:

```bash
wget https://raw.githubusercontent.com/hcpp20334/your-repo/main/vec2.h
```
```C++
Usage
cpp
#include "vec2.h"

int main() {
    // Create vectors
    i32Vec2 pixel(1280, 720);
    d64Vec2 position(3.14159, 2.71828);

    // Access elements
    std::cout << "Screen: " << pixel.x << "x" << pixel.y << std::endl;

    // Check sizes
    GetAllVec2Size();
    
    return 0;
}
```
## API Reference
Vector Types
-
Type	Description	Components
- i8Vec2	8-bit integer vector	x, y (int8_t)
- i16Vec2	16-bit integer vector	x, y (int16_t)
- i32Vec2	32-bit integer vector	x, y (int32_t)
- i64Vec2	64-bit integer vector	x, y (int64_t)
- f64Vec2	64-bit float vector	x, y (float64_t)
- d64Vec2	64-bit double vector	x, y (double64_t
