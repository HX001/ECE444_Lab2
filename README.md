# ECE444_Lab2
This is Hong Xu
This repo is a clone of https://github.com/miguelgrinberg/flasky

## Activity 1: Installation
![Activity 1 ScreenShot](https://github.com/HX001/ECE444_Lab2/blob/master/Activity1%20Screen%20Shot.png)

## Activity 2: Create hello.py
![Activity 2](https://github.com/HX001/ECE444_Lab2/blob/master/Example%202-2.png)

## Activity 3: Briefly summarize what are the Flask context globals
Ans: There are two contexts in Flask, the application context and the request context. The Flask context globals are variables that can be accessed from all threads. Flask uses Contexts to make certain variables act like global variables and when the system accesses them, the system can get access to the object for the current thread. In summary, the Contexts can make certain variables globally accessible to a thread temporarily without interfering with the other threads (a multithreaded server needs to handle different requests from different clients at the same time).
