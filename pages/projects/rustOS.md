---
layout: default
title: Projects
permalink: /projects/RustOS
---

# **Writing an Operating System in Rust**
I've always wanted to play around with writing an operating system but, I never knew where to start. A few months ago I discovered Philipp Oppermann's [blog](https://os.phil-opp.com/) and on there he has a tutorial for writing a very minimalistic operating system in Rust. Since then, I've been following the tutorials as well as making changes where I see fit. Below I've documented the steps I've already completed.


### **Standalone Rust Binary**
Created a Rust executable that does not link to the standard library making it able to run Rust code on a bare metal system without an OS. In this part we wrote a panic handler, overwrote the entry point for the Rust compiler

### **GitHub Repo**
* [RustOS](https://github.com/amalik18/RustOS)
