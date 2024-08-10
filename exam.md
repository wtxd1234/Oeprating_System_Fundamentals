### Operating System Fundamentals

#### **1. Introduction to Operating Systems**
- **Definition**: Software that manages computer hardware and software resources, providing common services for computer programs.
- **Functions**: Process management, memory management, file system management, device management, and security.

#### **2. Operating System Structure**
- **Monolithic Systems**: Single large kernel containing numerous services.
- **Layered Systems**: Divided into layers, each built on top of lower layers.
- **Microkernels**: Minimal kernel running basic services, with additional services in user space.
- **Modules**: Kernel with modular components that can be loaded and unloaded dynamically.

#### **3. Process Management**
- **Process**: A program in execution; includes program counter, registers, and variables.
- **Process States**: New, Ready, Running, Waiting, Terminated.
- **Process Control Block (PCB)**: Contains process state, program counter, CPU registers, memory limits, etc.
- **Context Switching**: Saving the state of a process and loading the state of another.

#### **4. Threads and Concurrency**
- **Thread**: Smallest sequence of programmed instructions that can be managed independently.
- **Multithreading**: Multiple threads within a single process, sharing resources.
- **Concurrency Issues**: Race conditions, deadlocks, and starvation.
- **Synchronization**: Mechanisms like mutexes, semaphores, and monitors to handle concurrency.

#### **5. CPU Scheduling**
- **Goals**: Efficient use of CPU, fast response time, and fair allocation of resources.
- **Scheduling Algorithms**:
  - **FCFS (First-Come, First-Served)**: Simple, non-preemptive.
  - **SJF (Shortest Job First)**: Optimal for short processes, non-preemptive or preemptive (SRTF).
  - **Round Robin**: Time-sharing, each process gets a small time slice.
  - **Priority Scheduling**: Processes are assigned priorities, higher priority executed first.
  - **Multilevel Queue**: Multiple queues for different types of processes, each with its own scheduling.

#### **6. Memory Management**
- **Responsibilities**: Tracking memory usage, managing allocation/deallocation, and ensuring effective memory utilization.
- **Memory Allocation**:
  - **Contiguous Allocation**: Processes are given continuous memory blocks.
  - **Non-Contiguous Allocation**: Memory divided into fixed-size or variable-size blocks (paging, segmentation).
- **Virtual Memory**: Allows execution of processes not completely in memory, using paging and swapping.

#### **7. File Systems**
- **File**: Collection of related data; basic storage unit.
- **File Attributes**: Name, type, size, location, permissions, etc.
- **File Operations**: Creation, deletion, reading, writing, and repositioning.
- **Directory Structure**: Single-level, two-level, tree-structured, acyclic-graph, and general graph.
- **File System Implementation**:
  - **Allocation Methods**: Contiguous, linked, indexed.
  - **Free Space Management**: Bitmaps, linked lists, grouping.

#### **8. Input/Output Systems**
- **I/O Hardware**: Devices such as disks, tapes, and network cards.
- **I/O Software**: Device drivers, interrupt handlers, and system calls.
- **Buffering**: Temporary storage for data in transit.
- **Spooling**: Overlapping of I/O operations for efficiency.

#### **9. Security and Protection**
- **Goals**: Protect information from unauthorized access and ensure system reliability.
- **Threats**: Malware, phishing, denial of service (DoS), etc.
- **Security Measures**: Authentication, encryption, access control mechanisms.
- **Protection Mechanisms**: User roles, access control lists (ACLs), and security policies.

#### **10. Advanced Topics**
- **Distributed Systems**: Multiple independent computers working together.
- **Cloud Computing**: Delivery of computing services over the internet.
- **Virtualization**: Creation of virtual versions of physical resources.
