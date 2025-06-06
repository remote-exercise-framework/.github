## Remote Exercise Framework

The Remote Exercise Framework (or REF for short) provides a learning platform for university courses in the domain of computer security. Instructors write challenges that students then can solve in a controlled, dedicated environment (each student receives their own Docker container, which they connect to via SSH - enabling students to learn materials regardless of their choice of hardware or OS). REF provides various convenience features, including automated solution checking, partial hints supporting students on their way towards solving challenges, introspection capabilities enabling instructors to provide tailored guidance, an online overview for instructors on how many students have solved a particular challenge, simple deadline management, and an online grading interface for instructors. 

### Quick Overview

- [ref](https://github.com/remote-exercise-framework/ref): contains the framework itself
- [ref-utils](https://github.com/remote-exercise-framework/ref-utils): a set of utility libraries, primarily enabling automated tests and partial hints that support students
- [ref-linux](https://github.com/remote-exercise-framework/ref-linux): a patched Linux kernel that allows to disable ASLR even on setuid binaries
- [ref-openssh-portable](https://github.com/remote-exercise-framework/ref-openssh-portable): a patched OpenSSH server that serves as a reverse proxy for SSH connections to forward students to their respective container
