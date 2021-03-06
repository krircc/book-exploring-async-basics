# Summary

[Introduction](./introduction.md)
- [Concurrent vs Parallel](./1_concurrent_vs_parallel.md)
- [Async history](./2_async_history.md)
- [The Operating System and CPU](./3_0_the_operating_system.md)
  - [Communicating with the OS](./3_1_communicating_with_the_os.md)
  - [Writing Cross Platform Abstractions](./3_2_cross_platform_abstractions.md)
  - [The CPU and the OS](./3_3_the_cpu_and_the_os.md)
- [Interrupts, Firmware and I/O](./4_interrupts_firmware_io.md)
- [Strategies for handling I/O](./5_strategies_for_handling_io.md)
- [Epoll, Kqueue and IOCP](./6_epoll_kqueue_iocp.md)
- [Introducing our main example](./7_0_introducing_our_main_example.md)
  - [What is Node?](./7_1_what_is_node.md)
  - [What's our plan](./7_2_whats_our_plan.md)
- [Implementing our own Runtime](8_0_implementing_our_own_runtime.md)
    - [Running our runtime - the main loop](./8_1_the_main_loop.md)
    - [Setting up our runtime](./8_2_setting_up_runtime.md)
    - [Timers](./8_3_timers.md)
    - [Callbacks](./8_4_callbacks.md)
    - [Threadpool](./8_5_threadpool.md)
    - [I/O eventqueue](./8_6_io_eventqueue.md)
    - [Cleaning up](./8_8_cleaning_up.md)
    - [Infrastructure](./8_9_infrastructure.md)
- [Modules](./9_0_modules.md)
  - [File module](./9_1_file_module.md)
  - [Crypto module](./9_2_crypto_module.md)
  - [Http module](./9_3_http_module.md)
- [Putting the pieces together](./10_putting_pieces_together.md)
- [Final code](./11_final_code.md)
- [Shortcuts and improvements](./12_shortcuts_and_improvements.md)

[Conclusion](./conclusion.md)