# Abrar Yasser

Software developer working in C, C++, Java and Python, with an interest in systems programming, concurrency and distributed systems. Currently learning Go by rewriting my blockchain node in it.

## Projects

### Systems and concurrency

| Project | What it is | Built with |
|---|---|---|
| **[audioBox](https://gitlab.com/galdotric/audioBox)** | A library for editing 16-bit audio without copying samples: inserted clips share memory with their source, so an edit to one is heard in both. Includes WAV I/O, ad detection by cross-correlation, and a demo that cuts ads out of a recording. 75 tests, run under AddressSanitizer | C, Make |
| **[mlqdispatcher](https://gitlab.com/galdotric/mlqdispatcher)** | A three-level multi-level queue process dispatcher. Runs each job as a real child process and controls it with signals; FCFS and Round Robin levels, pre-emption and starvation prevention | C++, POSIX signals |
| **[multithreaded-lab-scheduling-simulator](https://gitlab.com/galdotric/multithreaded-lab-scheduling-simulator)** | A simulation of students, tutors and a teacher sharing a limited number of lab rooms, coordinated with threads, mutexes and condition variables | C++, `std::thread` |
| **[docEditor](https://gitlab.com/galdotric/docEditor)** | A collaborative Markdown editor: a server and its clients talk over named pipes, with a thread per client, read/write roles and versioned edits | C, pthreads, FIFOs |

### Distributed systems and networking

| Project | What it is | Built with |
|---|---|---|
| **[bitcoin](https://gitlab.com/galdotric/bitcoin)** | A peer-to-peer blockchain node: Ed25519-signed transactions over TCP, a mempool, transaction forwarding and lowest-hash consensus between peers | Python, PyNaCl |
| **[SOFT3888_TU08_02](https://gitlab.com/galdotric/SOFT3888_TU08_02)** | Team project: a deterministic network-failure dataset and benchmark pipeline that generates, validates and runs failure scenarios on emulated networks | Python, NIKA, Kathara, Docker, uv |

### Games and web

| Project | What it is | Built with |
|---|---|---|
| **[inkballGame](https://gitlab.com/galdotric/inkballGame)** | A ball-and-hole puzzle game: draw ink lines to steer coloured balls into matching holes. Three levels, and a 29-test suite that plays the real game without a window | Java, Processing, Gradle |
| **[birthdayCat](https://gitlab.com/galdotric/birthdayCat)** | A birthday page where an SVG cat sings a tune generated from a name, with confetti, petting and a cake to blow out. A companion tool saves any name's tune as a WAV file | JavaScript, Web Audio, C |

## Tools

C, C++, Java, Python, JavaScript · Git, Make, Gradle, Docker, Kathara, uv · GCC sanitizers, JUnit

## Contact

- GitLab: [@galdotric](https://gitlab.com/galdotric)
- Email: yasserabrar485@gmail.com
