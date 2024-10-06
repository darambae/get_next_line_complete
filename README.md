# get_next_line

## Table of Contents

- [get\_next\_line](#get_next_line)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [Feature](#feature)
  - [Installation](#installation)
  - [Functions List](#functions-list)
  - [Project Structure](#project-structure)
  - [Bonus](#bonus)
    
## Introduction

get_next_line is a project that aims to create a function capable of reading a line ending with a newline character ('\n') from a file descriptor. This function is essential for handling input in a controlled and efficient manner, and is a common requirement in many real-world applications. This project is part of the 42 school curriculum, designed to enhance understanding of file I/O operations and dynamic memory management in C.

get_next_line est un projet visant à créer une fonction capable de lire une ligne se terminant par un caractère de nouvelle ligne ('\n') à partir d'un descripteur de fichier. Cette fonction est essentielle pour gérer les entrées de manière contrôlée et efficace, et est une exigence courante dans de nombreuses applications réelles. Ce projet fait partie du programme de l'école 42, conçu pour améliorer la compréhension des opérations d'E/S de fichiers et de la gestion dynamique de la mémoire en C.

get_next_line는 파일 디스크립터에서 줄 바꿈 문자 ('\n')로 끝나는 줄을 읽을 수 있는 함수를 만드는 것을 목표로 하는 프로젝트입니다. 이 함수는 입력을 제어되고 효율적으로 처리하는 데 필수적이며, 많은 실제 응용 프로그램에서 일반적으로 요구됩니다. 이 프로젝트는 파일 I/O 작업 및 C에서의 동적 메모리 관리에 대한 이해를 높이기 위해 설계된 42 학교 커리큘럼의 일부입니다.

---

## Feature

- Reads a line from a file descriptor, including the newline character.
- Handles multiple file descriptors simultaneously.
- Efficient memory usage with dynamic buffer allocation.
<br><br>
- Lit une ligne à partir d'un descripteur de fichier, y compris le caractère de nouvelle ligne.
- Gère plusieurs descripteurs de fichiers simultanément.
- Utilisation efficace de la mémoire avec allocation dynamique de tampon.
<br><br>
- 파일 디스크립터에서 줄 바꿈 문자를 포함한 줄을 읽음.
- 여러 파일 디스크립터를 동시에 처리.
- 동적 버퍼 할당을 통한 효율적인 메모리 사용.

---

## Installation

```sh
git clone https://github.com/darambae/get_next_line.git
cd get_next_line
gcc -Wall -Wextra -Werror get_next_line.c get_next_line_utils.c -o get_next_line
```

---

## Functions List

- `get_next_line` - Reads a line from a file descriptor.
<br><br>
- `get_next_line` - Lit une ligne à partir d'un descripteur de fichier.
<br><br>
- `get_next_line` - 파일 디스크립터에서 줄을 읽음.

---

## Project Structure
```
get_next_line/
│
├──get_next_line.c
├── get_next_line.h
├── get_next_line_bonus.c
├── get_next_line_bonus.h
├── get_next_line_utils.c
├── get_next_line_utils_bonus.c
└── README.md
```
---

## Bonus

- Handles multiple file descriptors at the same time.
- Returns the line read, or NULL if there is nothing more to read or an error occurred.
<br><br>
- Gère plusieurs descripteurs de fichiers en même temps.
- Renvoie la ligne lue, ou NULL s'il n'y a plus rien à lire ou si une erreur s'est produite.
<br><br>
- 여러 파일 디스크립터를 동시에 처리.
- 읽은 줄을 반환하거나 더 이상 읽을 것이 없거나 오류가 발생하면 NULL을 반환.
