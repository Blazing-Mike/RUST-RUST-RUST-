   
#### ANATOMY OF A RUST PROGRAM

``
fn main() {
}
``
The *main*b function is special, it is the first code that runs in every Rust executable program.

It declares a function main ( no parameters and doesnt return anything).

After writing your code, you need to compile it first before running it. to compile rust.

Run "cargo build" in your command line editor ( i am using CMD on windows), after building it you can then run it with

".\target\debug\hello-rust.exe " then you have your output in your editor. OR you can run and build it just one command which is " cargo  run ".

###   BASIC TYPES

   -booleans - bool for representing true/false
   
   -unsigned integers - u8 u16 u32 u64 u128 for representing nonnegative whole numbers
   
   -signed integers - i8 i16 i32 i64 i128 for representing whole numbers
   
   -pointer sized integers - usize isize for representing indexes and sizes of things in memory
   
   -floating point - f32 f64
   
   -tuple - (value, value, ...) for passing fixed sequences of values on the stack
   
   -arrays - [value, value, ...] a collection of similar elements with fixed length known at compile time
   
   -slices - a collection of similar elements with length known at runtime
   
   -str (string slice) - text with a length known at runtime
