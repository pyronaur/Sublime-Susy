# Sublime Susy 0.1
## Susy Snippets for Sublime Text 2

Currently contains all the basic Susy snippets for Functions and Mixins, and hopefully we can fill in more (like auto-completions) later.

## Usage
Mostly works with favorite Susy Function/Mixin as is, and the snippets are going to prepend the `@include` on their own (except for functions of course).
You should be able to tab over everything, just as you'd expect from ST2 Snippets, right ?

* `span-columns()` has a bit more snippets:  

  * `scol` translates to a simple:  
  ```@include span-columns($columns, $total_columns);```  
  
  * `scolo` adds omega to the mix:
  ```@include span-columns($columns omega, $total_columns);```   
  
  * `scolumn` expands to a full span-columns mixin:
   ```@include span-columns($total_columns omega, $context, $padding, $from);```


