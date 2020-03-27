# RustHowTo
How to do something during rust developing.

---

# 基础

这里罗列了Rust最基本的东西

## 基础类型

| 符号   | 长度      | 值范围 |
| ----- | --------- | ------ |
| u8    | 8-bit     | 0~255 |
| u16   | 16-bit    | 0~65535 |
| u32   | 32-bit    | 0~4294967295 |
| u64   | 64-bit    | 0~18446744073709551615 |
| u128  | 128-bit   |        |
| usize | arch      | - |
| i8    | 8-bit     | -128~127 |
| i16   | 16-bit    | -32768~32767 |
| i32   | 32-bit    | -2147483648~2147483647 |
| i64   | 64-bit    | -9223372036854775808~9223372036854775807 |
| i128  | arch      | - |
| isize | isize-bit |        |
| f32   | 32-bit    |        |
| f64   | 64-bit    |        |
| bool  | 64-bit    | true~false |
| char  | 32-bit    |        |


## 如何定义变量

```rust
// 基本定义
let num1: u32 = 1;
let num2 = 2;    // i32
let float = 1.1; // f64
let done = true;
let char = 'z';

// 数值运算
let sum = 5 + 10;
let difference = 95.5 - 4.3;
let product = 4 * 30;
let quotient = 56.7 / 32.2;
let remainder = 43 % 5;

// 元组
let tup: (i32, f64, u8) = (500, 6.4, 1);
let (x, y, z) = tup;
let x1 = tup.0;
let y1 = tup.1;
let z1 = tup.2;

// int数组
let arr0: [i32; 5] = [0; 10];  // init a empty int array
let arr2: [i32; 5] = [1, 2, 3, 4, 5]; // init a known int array
let arr1 = [1, 2, 3, 4, 5];  // type automatic derivation, can omit writing
let first = arr1[0];
let second = arr1[1];

// bytes = u8 array
let bytes1: [u8; 5] = [0; 5];
let bytes2 = [0u8; 5];

// 切片 = 数组的一部分
let int_slice = &arr1[1..3];
let bytes_slice = &bytes1[1..3];

```

## 如何定义常量


## 如何输出打印

```rust
println!(123);
println!("{:?}", abc)
```

## 如何进行流程控制

```rust

```

## 如何定义函数

```rust

```

## 如何定义类

```rust

```

## 如何定义方法

```rust

```

## 如何定义宏

```rust

```

## 如何定义自定义类型

```rust

```

## 如何控制可见性

## 如何组织代码结构



# 类型转换

## 如何将int转成bytes

```rust
u32::to_be_bytes();
```

## 如何将bytes转成int

```rust

```

# 加解密



# 编码解码



# 实际应用



# 参考文献

# 贡献者





