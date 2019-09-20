---
layout: post
title: Porting of RCBeam to Python
date: 2019-09-20

---

Last year, I created a library in java called **RCBeam**. I used this in my masters class for
checking and automating calculation for our subject Design of Concrete Structures.

The library is already working for me but not to many people in my class as you have to know some knowledge in
java to run the program. I wanted to share it. For learning purposes to some people that it may be useful and to me
by gathering user's comments.

Because of this, I decided to create a small web application for it. And since I don't have much experience in Java
web development as backend and I think it may be an overkill on my side, I decided to port the code in python and
code it in flask framework instead as a backend. Maybe provide some API if given enough time and help.

Tonight, I started breaking the classes from the java code and transferring those to python.

For reference, the python code can be access through github [(https://github.com/syncsoft-solutions/pyrca)](https://github.com/syncsoft-solutions/pyrca)
