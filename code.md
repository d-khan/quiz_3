```
section .text
        global _start

_start:
        mov eax,[var1]
        mov ebx,10
        mul ebx

        mov eax,1
        int 0x80

section .data
        var1 DD -10

segment .bss
        result resb 1
```

![stupid image](https://github.com/d-khan/quiz_3/assets/11669149/e7abd354-9bff-4763-bece-3cc86e2a45b5)
