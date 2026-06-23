# Customised Virtual File System (CVFS)

## Repository Structure
This repository utilizes a simplified structure containing only the source code and documentation:

```text
/cvfs-project
├── /src          # Contains all C source files and header definitions
└── README.md     # Project documentation
```

## Getting Started

### Prerequisites
* A C compiler (e.g., GCC or Clang)

### Build and Run
Because this project does not utilize a Makefile, you must manually compile all source files located in the `/src` directory.

1. Clone the repository and navigate to the root directory.
2. Compile the core logic and shell interface manually:
   ```bash
   gcc src/*.c -o Myexe
   ```
3. Execute the custom virtual file system:
   ```bash
   ./Myexe
   ```

### Example Usage
Once the custom shell is running, you can interact with the virtual environment:

```bash
Marvellous CVFS> create Demo.txt 
Marvellous CVFS> write Demo.txt "Jay Ganesh" 
Marvellous CVFS> read Demo.txt 
Jay Ganesh 
Marvellous CVFS> ls 
Demo.txt 
Marvellous CVFS> rm Demo.txt 
Marvellous CVFS> exit 
```

## Author
**Sakshi Pradeep Bhapkar**
* **Email:** sakshi.p.bhapkar@gmail.com
* **Phone:** 9284292095
