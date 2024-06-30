# APC Queue Injection Rust

This project performs APC Queue Injection in Rust, an EDR Evasion and EDR Bypass technique! 

We enumerate through all of the threads active in the target remote process, then queue an APC
callback routine which is a pointer to the shellcode (remote virtual address).

POC video coming soon!