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
Here’s a more natural-sounding introduction for the **get_next_line** project in English, French, and Korean:

**get_next_line** is a C project that aims to provide a function for reading a line from a file descriptor, including standard input. This implementation allows for efficient line-by-line reading from files, handling multiple file descriptors simultaneously. The project focuses on memory management and dynamic allocation, ensuring that resources are properly managed while reading input. By working on **get_next_line**, you'll gain a deeper understanding of file handling in C and improve your skills in working with buffers and strings.

**get_next_line** est un projet en C qui vise à fournir une fonction permettant de lire une ligne à partir d'un descripteur de fichier, y compris l'entrée standard. Cette implémentation permet de lire efficacement ligne par ligne à partir de fichiers, tout en gérant simultanément plusieurs descripteurs de fichier. Le projet met l'accent sur la gestion de la mémoire et l'allocation dynamique, garantissant que les ressources sont correctement gérées lors de la lecture de l'entrée. En travaillant sur **get_next_line**, vous approfondirez votre compréhension de la gestion des fichiers en C et améliorerez vos compétences dans la manipulation des tampons et des chaînes.

**get_next_line**는 C 프로젝트로, 파일 디스크립터(표준 입력 포함)에서 한 줄을 읽기 위한 함수를 제공하는 것을 목표로 합니다. 이 구현은 파일에서 효율적으로 한 줄씩 읽을 수 있으며, 여러 파일 디스크립터를 동시에 처리할 수 있습니다. 이 프로젝트는 메모리 관리와 동적 할당에 중점을 두어 입력을 읽는 동안 자원이 적절하게 관리되도록 합니다. **get_next_line** 작업을 통해 C에서 파일 처리에 대한 깊은 이해를 얻고 버퍼와 문자열을 다루는 기술을 향상시킬 수 있습니다.

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
- 파일 디스크립터에서 줄 바꿈 문자('\n')를 포함한 줄을 읽음.
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
