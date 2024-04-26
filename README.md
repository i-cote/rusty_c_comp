# C compiler written in Rust

This repository contains the code for a C compiler  
written in Rust.   
It uses the antlr suite to generate code to visit the AST.  
We use this visitor structure to generate an IR from  
the AST and then convert the IR into x86 which is currently  
the only supported target.  
