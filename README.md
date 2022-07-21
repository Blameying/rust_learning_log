### Rust learning dashboard

- *7月1日*  使用rustlings进行练习
  - 进行到了结构体部分，涉及到结构体对str类型引用涉及到了生命周期的知识
  - ![screenshot](./images/ScreenShot_2022-07-01_at_16.11.02.jpg)
- *7月2日* rustlings 进行到了错误处理部分，对?运算符印象深刻
  - ![screenshot](./images/ScreenShot_2022-07-02_at_17.44.42.jpg)
- *7月3日* rustlings 错误处理的错误类型转换部分遇到了点问题，就是map_err函数，看着满屏的错误可太恶心了，所以刚进行到了generics部分。Happy Sunday。
  - 完成了rcore-os的lab1， 使用github的codespace，部分手册说的不太完整，但群友的反馈已经得到了修改。
- *7月4日* 今天有些忙，skip
- *7月5日* rustlings 完成quiz3, 包含traits, test 相关内容
- *7月6日* rustlings 完成iterator
- *7月9日* rustlings 完成, 代码地址为: [https://github.com/Blameying/rustlings](https://github.com/Blameying/rustlings)
  下午上传到夏令营给出的codespace中进行评分
- *7月11日* 阅读rust权威指南的trait章节
- *7月12日* rust-quiz完成 16/33
- *7月14日* 阅读lab1指南，学习批处理系统
- *7月21日* 这几天花了挺长时间来完成os3的实验
  - 建立了自己的task_manager，并预留几个可用的状态，按照原有的代码其实它是一个进程对应一个内核栈和一个用户栈，感觉后面可以只维护一个内核栈，当然这种方式确实简化了开发流程。
  - 目前对UPSafeCell的作用机理略有疑惑，感觉后面应该会改成加锁的形式
  - 上下文恢复这部分虽然早有了解，实际写起来加深了对寄存器的功能了解
  - 调试起来确实不太友好，目前gdb调试只能看汇编，但好在可以直接对符号加断点
