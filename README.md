# dr-quine

**Time:**: ~10h ( Without any asm practice )

**Final mark**: .../125

|Language|State|
|:---:|:---:|
|**Colleen**|
|**C**|✅|
|**Go**|✅|
|**ASM**|✅|
|**Grace**|
|**C**|✅|
|**Go**|✅|
|**ASM**|✅|
|**Sully**|
|**C**|✅|
|**Go**|✅|
|**ASM**|✅|


## Colleen

### C
```
	printf specifications:

	%2$c -> print second argument as a character
	%position$type

	why:
		%s does not escape \t / \n which indents
				const char *source_code
		twice.
```

### Go
```
	(fmt.)Printf is a bit different from C

	%[2]c
	%[argument_index]format
```

### ASM

![Arguments](https://raw.githubusercontent.com/c3b5aw/dr-quine/main/docs/images/j8hpC.png)
```
	Arguments like in C.
```

## Grace

###
![std flib](https://www.plantation-productions.com/Webster/www.artofasm.com/DOS/ch13/CH13-10.html)

## Sully

Trick is to check if sully_5 has been generated in order to decrease integer.

However, we could have checked if the program name was equal to the Parent ("Sully")