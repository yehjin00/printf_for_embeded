# printf-for-embeded

Input only numeric because of using it for embedded.<br/>
When you input numeric in a range of unsigned char or int or long, fun function returns it to character.

[Condition]
1. Form of function : fun(”Hello %d”, &a),  print like Hello 123
2. Using %1, %2, %4
   %1 : tU08 to char
   %2 : tU16 to char
   %4 : tU32 to char

Type definition<br/>
unsigned char = tU08<br/>
unsigned int = tU16<br/>
unsigned long = tU32
