Brand new pintos for Operating Systems and Lab (CS330), KAIST, by Youngjin Kwon.

The manual is available at https://casys-kaist.github.io/pintos-kaist/.


pintos -T 10 -- -q run alarm-single

```
pass tests/threads/alarm-single
pass tests/threads/alarm-multiple
pass tests/threads/alarm-simultaneous
FAIL tests/threads/alarm-priority
pass tests/threads/alarm-zero
pass tests/threads/alarm-negative
FAIL tests/threads/priority-change
FAIL tests/threads/priority-donate-one
FAIL tests/threads/priority-donate-multiple
FAIL tests/threads/priority-donate-multiple2
FAIL tests/threads/priority-donate-nest
FAIL tests/threads/priority-donate-sema
FAIL tests/threads/priority-donate-lower
FAIL tests/threads/priority-fifo
FAIL tests/threads/priority-preempt
FAIL tests/threads/priority-sema
FAIL tests/threads/priority-condvar
FAIL tests/threads/priority-donate-chain
FAIL tests/threads/mlfqs/mlfqs-load-1
FAIL tests/threads/mlfqs/mlfqs-load-60
FAIL tests/threads/mlfqs/mlfqs-load-avg
FAIL tests/threads/mlfqs/mlfqs-recent-1
pass tests/threads/mlfqs/mlfqs-fair-2
pass tests/threads/mlfqs/mlfqs-fair-20
FAIL tests/threads/mlfqs/mlfqs-nice-2
FAIL tests/threads/mlfqs/mlfqs-nice-10
FAIL tests/threads/mlfqs/mlfqs-block
```
```
pass tests/threads/alarm-single
pass tests/threads/alarm-multiple
pass tests/threads/alarm-simultaneous
pass tests/threads/alarm-priority
pass tests/threads/alarm-zero
pass tests/threads/alarm-negative
pass tests/threads/priority-change
FAIL tests/threads/priority-donate-one
FAIL tests/threads/priority-donate-multiple
FAIL tests/threads/priority-donate-multiple2
FAIL tests/threads/priority-donate-nest
FAIL tests/threads/priority-donate-sema
FAIL tests/threads/priority-donate-lower
pass tests/threads/priority-fifo
pass tests/threads/priority-preempt
FAIL tests/threads/priority-sema
FAIL tests/threads/priority-condvar
FAIL tests/threads/priority-donate-chain
FAIL tests/threads/mlfqs/mlfqs-load-1
FAIL tests/threads/mlfqs/mlfqs-load-60
FAIL tests/threads/mlfqs/mlfqs-load-avg
FAIL tests/threads/mlfqs/mlfqs-recent-1
FAIL tests/threads/mlfqs/mlfqs-fair-2
FAIL tests/threads/mlfqs/mlfqs-fair-20
FAIL tests/threads/mlfqs/mlfqs-nice-2
FAIL tests/threads/mlfqs/mlfqs-nice-10
FAIL tests/threads/mlfqs/mlfqs-block
```