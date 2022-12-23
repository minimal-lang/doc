<div align='center'>

### Default ones
• `+` Addition;  
• `-` Subtraction;  
• `.` Multiplication;  
• `^` Elevation;  
• `/` Division;  
• `v` Square root.

### Setting
It’s a normal function with the `op` modifier that returns one.

• If it expects two values they are the left and the right values;  
• If it expected just one value this will be the right value.

### Example
<div align='left'>

  ```
    import 'std.mnl'

    ; factorial
    op int ! (int right)
      res = 1

      loop i from 2 by 1 till left
        res *= i

      return res

    print(!4 + 2) ; 26
  ```
</div>

