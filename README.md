# csapp

## code
The code in `code` is my learning record of video course of [yaaangmin](https://space.bilibili.com/4564101). His public repo [bcst_csapp](https://github.com/yangminz/bcst_csapp) is also available.

### branch: simple-asm-simulator
The `simple-asm-simulator` project is the bcst_csapp code before [video 0x08](https://www.bilibili.com/video/BV1WK41137JT) (the first code rebuilding).

This project simulates 15 assembly instructions of `add.c`. The 15 instructions is shown in `add.txt`, and is simply placed in `code.c`.

The check information of registers and memory in `main.c` is obtained through gdb.

To test this branch, you can run `make csapp` in `simple-asm-simulator` to compile the source code, and run `make run` to check the output. The last 2 lines will show the match results.

### branch: part1_finish
The part 1 code is finished according to the video 0x0C of bcst_csapp. The tests of add function and recursive sum function are passed by running `make hardware_csapp`.

In this project, the assembly instructions are decoded by strings.

### branch: main
The branch main is still under construction.

## ~~lab~~
~~The labs of the CSAPP book.~~