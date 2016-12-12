# RISC-V Debug task group
The RISC-V Debug Task Group was established to propose specifications for debug on RISC-V implementations. The scope of the group includes run-control and trace debug, but the current focus is to agree upon a standard for run-control debug.

The group is chaired by Tim Newsome (SiFive Inc).

The best way to get involved in this effort is to join and participate in the [RISC-V debug mailing list](https://groups.google.com/a/groups.riscv.org/forum/#!forum/debug).

## Run-control debug
Run-control debug allows you to halt, step, resume, to set breakpoints, and to access GPRs+CSRs+memory. There have been two main proposals for run-control, and much of the group's time has been spent understanding the differences and trade-offs between these two approaches, with the goal of producing a single unified specification.

### Proposed specifications
* The ['Instruction' design](https://dev.sifive.com/documentation/risc-v-external-debug-support/) (see also a [work-in-progress version aiming for reduced implementation size](https://groups.google.com/a/groups.riscv.org/d/msg/debug/7u2qvqJsac4/7j_zyhfLAwAJ)).
* The ['Direct' design](https://groups.google.com/a/groups.riscv.org/d/msg/debug/N2Qu17lALe4/4lzibYmvCQAJ). The primary author of this proposal has also started work on [a version that hopes to combine the best of both proposals](https://groups.google.com/a/groups.riscv.org/d/msg/debug/HYCuX8oP6Ew/NLTr1IWNBAAJ).

The best starting point is to read this [comparison between the two approaches](https://sifive.github.io/debug-mechanism-comparison/).

## Meetings
In addition to discussions on the mailing list, the group has recently started a series of meetings.

### Upcoming

  * Thursday 15th December, 2016. 8am PST. [Details](https://groups.google.com/a/groups.riscv.org/d/msg/debug/CE7UYAC4ytc/V0a0uNjiBAAJ).

### Previous

  * 7th December, 2016. [Slides](https://docs.google.com/presentation/d/1zMAUUgEf1nydUpKVB5Tg9cdOJrl4M0pWdTgHoMEVD4Q/edit?usp=sharing). [Notes](https://groups.google.com/a/groups.riscv.org/d/msg/debug/qoYAY36-5HQ/o6DSzDXlBAAJ).
  * 30th November, 2016. [Slides](https://docs.google.com/presentation/d/1jOjG20-gwtcGybZg2Bu3StV6ljZZV9n2SQAEjKWQwDE/edit?usp=sharing). [Notes](https://groups.google.com/a/groups.riscv.org/d/msg/debug/ucaYL8pNfxo/Rv81fi6nCwAJ).
