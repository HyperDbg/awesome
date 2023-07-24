# Awesome HyperDbg ![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)

A list of awesome resources about HyperDbg.

## Articles

### Papers
- [HyperDbg: Reinventing Hardware-Assisted Debugging (CCS'22)](https://dl.acm.org/doi/abs/10.1145/3548606.3560649) [[arXiv](https://arxiv.org/abs/2207.05676)]
- [Kernel Debugger Design In HyperDbg](https://research.hyperdbg.org/debugger/kernel-debugger-design.html)
- [VM-exit Transparency In HyperDbg](https://research.hyperdbg.org/debugger/transparency.html)
- [Chasing Bugs with/in Hypervisors](https://research.hyperdbg.org/debugger/chasing-bugs.html)

### Blog Posts
- [HyperDbg’s One Thousand and One Nights](https://rayanfam.com/topics/hyperdbg-one-thousand-and-one-nights)

### Miscellaneous
- [GDB to LLDB to Windbg to HyperDbg Command Map](https://hyperdbg.github.io/commands-map)

## Documentation

### Attaching/Building HyperDbg 
- [Build & Install](https://docs.hyperdbg.org/getting-started/build-and-install)
- [Attach to a remote machine](https://docs.hyperdbg.org/getting-started/attach-to-hyperdbg/debug)
- [Attach to local machine](https://docs.hyperdbg.org/getting-started/attach-to-hyperdbg/local-debugging)
- [Start a new process](https://docs.hyperdbg.org/getting-started/attach-to-hyperdbg/start-process)
- [Attach to a running process](https://docs.hyperdbg.org/getting-started/attach-to-hyperdbg/attach-process)
- [Guide for using the Software Development Kit (SDK)](https://docs.hyperdbg.org/using-hyperdbg/sdk)

### User-mode Debugging
- [Getting Results of a System-call](https://docs.hyperdbg.org/using-hyperdbg/user-mode-debugging/examples/events/getting-results-of-a-system-call)

### Kernel-mode Debugging
- [Connecting To HyperDbg](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/beginning/connecting-to-hyperdbg)
- [Configuring Symbol Server/Path](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/beginning/configuring-symbol-server-path)
- [Setting Breakpoints & Stepping Instructions](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/basics/setting-breakpoints-and-stepping-instructions)
- [Displaying & Editing & Searching Memory](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/basics/displaying-and-editing-and-searching-memory)
- [Showing & Modifying Registers and Flags](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/basics/showing-and-modifying-registers-and-flags)
- [Mapping Data & Create Structures, and Enums From Symbols](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/basics/mapping-data-and-create-structures-and-enums-from-symbols)
- [Switching to a Specific Process or Thread](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/basics/switching-to-a-specific-process-or-thread)
- [Managing Events](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/managing-events)
- [Hooking Any Function](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/hooking-any-function)
- [Intercepting All SYSCALLs](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/intercepting-all-syscalls)
- [Monitoring Accesses To Structures](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/monitoring-accesses-to-structures)
- [Triggering Special Instructions](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/triggering-special-instructions)
- [Identifying System Behavior](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/events/identifying-system-behavior)
- [Defeating Anti-Debug & Anti-Hypervisor Methods](https://docs.hyperdbg.org/using-hyperdbg/kernel-mode-debugging/examples/misc/defeating-anti-debug-and-anti-hypervisor-methods)

### Script-engine
- [view system state (registers, memory, variables)](https://docs.hyperdbg.org/commands/scripting-language/examples/view-system-state)
- [change system state (registers, memory, variables)](https://docs.hyperdbg.org/commands/scripting-language/examples/change-system-state-registers-memory-variables)
- [trace function calls](https://docs.hyperdbg.org/commands/scripting-language/examples/trace-function-calls)
- [conditional breakpoints and events](https://docs.hyperdbg.org/commands/scripting-language/examples/conditional-breakpoints-and-events)
- [patch the normal sequence of execution](https://docs.hyperdbg.org/commands/scripting-language/examples/patch-the-normal-sequence-of-execution)
- [access to a shared variable from different cores](https://docs.hyperdbg.org/commands/scripting-language/examples/access-to-a-shared-variable-from-different-cores)
- [count occurrences of events](https://docs.hyperdbg.org/commands/scripting-language/examples/count-occurrences-of-events)
- [A collection of useful HyperDbg scripts](https://github.com/HyperDbg/scripts)

### Components
- [Event forwarding](https://docs.hyperdbg.org/tips-and-tricks/misc/event-forwarding)
- [Event short-circuiting](https://docs.hyperdbg.org/tips-and-tricks/misc/event-short-circuiting)

## Videos
- [CPS4150 Computer Architecture Final Seminar Presentation HyperDbg](https://www.youtube.com/watch?v=WHkXdv3tQvA)


## Presentations
- [Slides for IPM Presentation (2022) - HyperDbg Debugger](https://github.com/HyperDbg/slides/tree/main/2022/IPM)
- [Slides for 29th ACM Conference on Computer and Communications Security (CCS'22) - HyperDbg](https://github.com/HyperDbg/slides/tree/main/2022/CCS2022)
- [Slides for Zer0Con 2023 - Chasing Bugs with/in Hypervisors](https://github.com/HyperDbg/slides/tree/main/2023/Zer0Con2023)

# Non-English resources

A list of awesome resources about HyperDbg (non-English languages).

## Persian
- [A Practical Introduction to HyperDbg Debugger (وبینار مقدمه ای بر دیباگر هایپردیباگ)](https://www.youtube.com/watch?v=EK5WwWb5WNA)

## Spanish
- [Hyperdbg instalacion y primeros pasos](https://www.youtube.com/watch?v=BBp5kGL1qoI)
- [HYPERDBG PRIMEROS PASOS Y NUEVOS FEATURES](https://www.youtube.com/watch?v=rmkEW5IVDyg)
