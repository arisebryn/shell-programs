# mulithreaded-shell
mulitthreaded-shell is a program of a client and server files built in the C programming language.

## Installation

Needed dependencies for running the program successfully. This step assumes that you know how to access and use a host VPN.

```
Putty Winscp FortiClient
```

Download and save the following file to a folder on your local disk.

```
miniThread.c
```

Upload this file from local disk to your remote network host using Winscp and FortiClient.

## Usage
Open a terminal in putty and navigate to the directory containing your file using:

```
cd <directory name>
```

Run the following commands to compile and run your program.

```c
gcc -pthread miniThread.c -o miniThread
```

```
./miniThread
```

Follow the prompt output by the program in the terminal. Run commands using the multithreaded shell.