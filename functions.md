<div align='center'>

### Arguments
• Arguments are normal variables/constants with or without assignment;  
• Arguments are passed inside parenthesis;  
• If you want to make it has a default value, you can assign it;  
• If you don’t pass a argument’s type it will be considered `any`.

### Syntax
• You can pass types _(`<T, Wind>`)_;  
• If you don’t pass the statements you’re only setting the function type _(most used for standard language’s functions)_, it doesn’t overwrite the original function.

<div align='left'>

  ```
    <return type> <name> (<...?arguments>)
      <...?statements>

    <return type> <name> <<...?types>> (<...?arguments>)
      <...?statements>
  ```
</div>

### Using
• If you don’t pass an argument _(only put a comma)_ the value passed will be its type empty.

<div align='left'>

  ```
    <name> (<...?arguments>)
    <name> (,,<...res of the arguments>)
  ```
</div>

### Return
<div align='left'>

  ```
    return <expr>
  ```
</div>

