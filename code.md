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
