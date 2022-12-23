<div align='center'>

### Attributes

• The privacy levels are `private`, `protected` or `public`;  
• If you omit the privacy level, it will be `public`;  
• You can assign a default value (If you do it you don’t need to say its type).

<div align='left'>

  ```
    <?privacy level> <?type> <name> = <expr>
    <?privacy level> <?type> <name>
  ```
</div>

### Methods

Normal functions with privacy level.

• Modifiers:
    • `static` Makes you be able to call this method without instance the class.  
• Use the keyword `ctx` to access the class reference (pointer / context).

<div align='left'>

  ```
    <?privacy level> <...?modifiers> <return type> <name>(<...arguments>)
      <...statements>
  ```
</div>

### Interfaces

<div align='left'>

  ```
    intr <name>
      <...?attributes>
      <...?methods without statements>

    intr <name> extends <another interface's name>
      <...?attributes>
      <...?methods without statements>
  ```
</div>

### Classes

• You don’t need to pass the name if you’re instancing it or creating a ref;

• Modifiers:  
    • `sealed` Don’t let the class be extended.

<div align='left'>

  ```
    <...?modifiers> class <?name>
      <...?attributes>
      <...?methods>

    class <?name> extends <another class' name>
      <...?attributes>
      <...?methods>

    class <?name> implements <interface's name>
      <...?attributes>
      <...?methods>
  ```
</div>

### Using

<div align='left'>

  ```
    ; normal instance
    Person per1 = new Person

    ; real time instance
    per2 = new class
      public name = 'Panda'

    ; saving in a variable
    per3 = class
      public name = 'Panda'
  ```
</div>

