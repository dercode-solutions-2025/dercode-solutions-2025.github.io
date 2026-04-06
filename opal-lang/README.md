## Welcome to Opal!
Written in Python, **Opal** is a dynamically typed compiled language designed as the ultimate Rhuse killer.
Rhuse, written by me a few months ago, was a small Lisp-like language that was interpreted. I didn't know what I was doing. This is not the case for **Opal**. 
Complete with inter-compatible Python libraries, **Opal** is very lightweight and has an in-depth syntax guide. Some **Opal** might look like:
``` Rust
fn greet(name) {
    puts "Hello, "
    puts name
    puts "!"
}
```
Which gets compiled to:
```Lisp
defun greet(name) start
puts ("Hello, ")
puts name
puts "!"
end
```
And then finally, this:
``` Python
def greet(name) :
    print ("Hello, ", end="")
    print (name, end="")
    print ("!", end="")
```
