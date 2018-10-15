## what i learned

- 真正意义上理解了处于`BLOCKED`状态的进程是不占用CPU的意思。之前的理解一直有偏差，实际上，被BLOCK的进程，可以理解成被操作系统从schedule list中暂时remove掉了，必然不会占用CPU，相当于被暂时freeze了，这个process的执行状态被操作系统保存，等待下次被唤醒。

- 进程这个概念，需要的硬件和软件的完美配合，即CPU和操作系统的合作，才呈现在了普通用户面前。
