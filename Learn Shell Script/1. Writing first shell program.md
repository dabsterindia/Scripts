# Writing "Hello World" program in Shell

## 1. Create a file hello.sh anf print hello world using below steps
`vi hello.sh`


```
#!/usr/bin/env bash
echo 'Hello World'
```

## 2. Execute the program
```
# chmod +x hello.sh
# ./hello.sh
```

OR

`# sh hello.sh`


### Here:
`#!/usr/bin/env bash` - This is known as shebang (It tells Unix which interpreter to use for execution)

Some other shebangs
```
#!/usr/bin/env bash
#!/bin/bash
#!/bin/sh
#!/bin/sh ```


