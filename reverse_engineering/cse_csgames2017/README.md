## Description
Voir le pdf en français ou en anglais pour une description détaillé du challenge.

## Informations
À rouler sur votre machine locale.

Les challenges des CS Games 2017 sont disponibles sur github: [https://github.com/csgames/compe2017](https://github.com/csgames/compe2017)

Si les fichiers binaires ne fonctionnent pas sur votre ordinateur, la solution est de compiler manuellement les fichiers que vous retrouverez sur le github officiel de la compétition.

## Opcodes

### InsWidthImmReg
MEMW  0000 0000
MEMR  0000 0001

### InsWidthRegReg
MEMR  0001 0000
MEMW  0001 0001

### InsWidthRegImm
MEMW  0010 0000

### InsWidthImmImm
MEMW  0011 0000

### InsFlagImm
JMPR  0100 0000
JMP   0100 0001

### InsFlagReg
JMPR  0101 0000
JMP   0101 0001

### InsImmReg
MOV   0110 0000
AND   0110 0001
OR    0110 0010
XOR   0110 0011
SHR   0110 0100
SHL   0110 0101
ADD   0110 0110
SUB   0110 0111
CMP   0110 1000

### InsReg
NOT   0111 0000
SNT   0111 0001
CALL  0111 0010
PUSH  0111 0011
POP   0111 0100

### InsImm
SNT   1000 0000
PUSH  1000 0001
CALL  1000 0010

### InsRegReg
XOR   1001 0000
ADD   1001 0010
SUB   1001 0011
MUL   1001 0100
DIV   1001 0101
SHL   1001 0110
AND   1001 0111
OR    1001 1000
SHR   1001 1001
CMP   1001 1010
MOV   1001 1011
WTHM  1001 1100

### INS
RET   1111 0000
NOP   1111 1111

1111


## Bon hacking!

