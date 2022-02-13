# MiniLibx
GETTING STARTED WITH THE MINILIBX
### **Description**

The **minilibx** is a small **C** library used for rendering graphics, primarily used by **42 students**. As the name implies, this library is built on top of the X Window System API, to provide a much simpler programming interface suited for beginners. Indeed, no X knowledge is needed at all to render graphics properly using this kind of library.

However, I found that this library is lacking any serious documentation about how to get started with it. That's why I wanted to make posts about this. In this post as well as the upcoming ones, I'll try to demonstrate how we can use the minilibx in an efficient and comprehensive way.

This first post will have a small theoric part, to make sure that we understand what is going on under the hood when using this kind of library. The remaining will all be about building things using code directly (that's what you're expecting, right ?).

**I will focus on the GNU/Linux version of the minilibx here. I will not cover the differences between it and the MacOS version.**