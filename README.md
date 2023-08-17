# CPU-PY
a simplest implementation of isa/assembler/emulator in python

## This project is arranged from research use
source:
https://github.com/garyexplains/examples

## Detail
- ISA: 16bit_cpu.png
- vASM.py: assembler to create rom.bin
- emulator: cpu emulator of own ISA, read rom.bin staticly written in code

## Getting Started
- vASM: create program file for emulator
```
python3 vASM.py a2z.asm
```
- EMULATOR: run a2z program
```
python3 emulator.py
```
壓住enter他會自己跑