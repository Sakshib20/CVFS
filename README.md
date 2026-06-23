# Customised Virtual File System (CVFS)

## Overview
This project is a custom implementation of a Virtual File System (VFS) that simulates the core functionality of the Linux file system[cite: 1]. It is built entirely in C, with its own custom shell to interact with the virtual environment[cite: 1]. The project provides a practical understanding of system calls, file handling, memory management, and OS internals[cite: 1].

## Key Features
* **Custom Shell Interface:** Provides Linux-like commands for file operations (create, open, read, write, delete, ls, etc.)[cite: 1].
* **System Call Simulation:** Implements core Linux file system system calls (open, read, write, lseek, close, rm, etc.) using C[cite: 1].
* **File System Data Structures:** Manages self-defined memory structures including the Incore Inode Table, File Table, UAREA (User Area), and User File Descriptor Table[cite: 1].
* **Platform Independent:** Allows system-level file handling functionalities of Linux to be used on any operating system platform[cite: 1].
* **Database-like Functionality:** Provides a customised database management layer with structured file handling[cite: 1].

## Repository Structure
This repository utilizes a simplified structure containing only the source code and documentation:

```text
/cvfs-project
├── /src          # Contains all C source files and header definitions
└── README.md     # Project documentation


## Getting Started

### Prerequisites
* A C compiler (e.g., GCC or Clang)

### Build and Run
Because this project does not utilize a Makefile, you must manually compile all source files located in the `/src` directory.

1. Clone the repository and navigate to the root directory.
2. Compile the core logic and shell interface manually:
   \`\`\`bash
   gcc src/*.c -o Myexe
   \`\`\`
3. Execute the custom virtual file system[cite: 1]:
   \`\`\`bash
   ./Myexe
   \`\`\`

### Example Usage
Once the custom shell is running, you can interact with the virtual environment[cite: 1]:

\`\`\`bash
Marvellous CVFS> create Demo.txt
Marvellous CVFS> write Demo.txt "Jay Ganesh"
Marvellous CVFS> read Demo.txt
Jay Ganesh
Marvellous CVFS> ls
Demo.txt
Marvellous CVFS> rm Demo.txt
Marvellous CVFS> exit
\`\`\`

## Author
**Sakshi Pradeep Bhapkar**  
Email: sakshi.p.bhapkar@gmail.com
