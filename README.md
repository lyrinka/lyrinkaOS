# lyrinkaOS
 A lightweight operating system for Cortex - M processors. 
 This OS is different from the previous lyrinkaOS.old, which is based on coroutines. 
 
 The operating system is designed for and tested on STM32 MCUs. Software simulation and STM32F103C8T6(72MHz) would be used for development and debugging and further plans include migrating to STM32F030C8T6(48MHz) and STM32F411CEU6(100MHz), covering mainstream Cortex - M0/3/4 core processors. 

 This OS offers fast context switching (<100 cycles) with value passing and other useful miscellaneous features supported. The basic context switching framework, named Emily, provides full extended Rin architecture functionality, while one of the previous OS uses extended Lin architecture. For scheduling, the concept and part of the code of the previous OS would be used. The same priority-based scheduler, Lint, is implemented with no excessive special features. The inter-process communications are supported by native semaphores, which accelerates the development of applications using queued message handler or actor framework. 

 The OS is intended to provide more functionality with the approximately same amount of overhead compared with other major RTOS. The basic idea is to unify more cases. But somehow my abilities are limited, and my OS isn't designed to be compared with others through mere benchmarks, but to connect with educational values and provide a better clarity when explaining and exploring the principals of an operating system. 

 After all, it's just something written during pure entertaining rather than written to be competitive. Thank you for your unrelenting criticism >_< 
