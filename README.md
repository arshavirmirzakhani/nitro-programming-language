![image](https://user-images.githubusercontent.com/76659587/206839876-629bd1b7-4214-4176-b0e6-21294bca6761.png)
# nitro-programming-language

nitro is a programming language that programmed with c++ , Flex , Bison and uses LLVM compile system.
and uses optimization for fast compile.

### syntax 

nitro syntax is familiar to python syntax
, heres an example of a simple program in nitro :

```
word = "nitro"

for i in range(len(word)):
  print(i)
```

### how it works?

nitro uses Flex/Bison for tokenising and parsing and uses LLVM for compiling

```mermaid
graph TD;
  lexer(Flex Lexer.l)-- generator --> main(nitro.cpp);
  parser(Bison Parser.y)-- generator --> main(nitro.cpp);
  LLVM(LLVM) --> main(nitro.cpp)
  main(nitro.cpp) --> compiler(nitro compiler)
```



### features

- fast compile
- better data management (variables , classes , objects)
- easy and fun to learn

### development 

remember that **this programming is in development and its not ready yet!** 
