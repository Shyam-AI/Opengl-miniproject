# ABSTRACT

The aim of this project is to create simulation of process scheduling in Operating system (Round Robin and Shortest Job First) . The project provides a beautiful graphical interface for interaction between human and the system.

The main objective of the project is to visualise how processes are scheduled in an operating system in the form of computer graphics . The project shows how process are first in the ready queue(RAM) and then they are executed by CPU.

The process scheduling algorithms are not very intuitive. It sometimes becomes hard to visualise how processes are scheduled and executed. Thus the main interest of this project is to make learners get clear understanding of the process scheduling algorithms(Round Robin and Shortest Job First) .

The project has been built using OpenGL library.The demonstration of the process scheduling has been shown in the form of Gantt chart. Inaddition to Gantt chart average waiting time,Turnaround time is also printed on the terminal. 

# Computer graphics 

Computer graphics are found in almost every industry; individuals in all demographic, geographic, racial, political, and religious groups benefit from them. When picking up a magazine or newspaper, watching television, going to the movies, or taking a drive down the street, images produced by computer graphics are seen.

# OpenGL
OpenGL is a software interface to graphics hardware. This interface consists of about 150 distinct commands that you use to specify the objects and operations needed to produce interactive three-dimensional applications. OpenGL is designed as a streamlined, hardware-independent interface to be implemented on many different hardware platforms. To achieve these qualities, no commands for performing windowing tasks or obtaining user input are included in OpenGL
 
OpenGL is an actively developed API. New versions of the OpenGL specifications are regularly released by the Khronos Group, each of which extends the API to support various new features. The details of each version are decided by consensus between the Group's members, including graphics card manufacturers, operating system designers, and general technology companies such as Mozilla and Google.

# OpenGL Graphics Architecture

<img src="https://github.com/Shyam-AI/Opengl-miniproject/blob/master/cgl-images/architecture.jpg" width="200px" height="auto">

# About the project

# Introduction

	Simulating CPU scheduling algorithms – Round Robin and Shortest Job first .
CPU Scheduling is a process of determining which process will own CPU for execution while another process is on hold. The main task of CPU scheduling is to make sure that whenever the CPU remains idle, the OS at least select one of the processes available in the ready queue for execution. The selection process will be carried out by the CPU scheduler. It selects one of the processes in memory that are ready for execution.
Types of Scheduling
i) Pre-emptive.
	In Preemptive Scheduling, the tasks are mostly assigned with their priorities. Sometimes it is important to run a task with a higher priority before another lower priority task, even if the lower priority task is still running.
ii)Non-Pre-emptive.
	In this type of scheduling method, the CPU has been allocated to a specific process. The process that keeps the CPU busy will release the CPU either by switching context or terminating. It is the only method that can be used for various hardware platforms. That's because it doesn't need special hardware (for example, a timer) like preemptive scheduling.
CPU scheduling criteria : 
	A CPU scheduling algorithm tries to maximize and minimize the following:
	
 <img src="https://github.com/Shyam-AI/Opengl-miniproject/blob/master/cgl-images/schedulig%20criteria.jpg" width="200px" height="auto">


Types of CPU scheduling Algorithm
There are mainly six types of process scheduling algorithms
1.	First Come First Serve (FCFS)
2.	Shortest-Job-First (SJF) Scheduling
3.	Shortest Remaining Time
4.	Priority Scheduling
5.	Round Robin Scheduling
6.	Multilevel Queue Scheduling


# Objectives
Importance of CPU scheduling : The aim of CPU scheduling is to make the system efficient, fast, and fair.Whenever the CPU becomes idle, the operating system must select one of the processes in the ready queue to be executed.
Knowledge of CPU schedulng is very important. Visualising the scheduling of the processes is not very intuitive.Each scheduling algorithms has its own approach to better utilise CPU and to schedule the processes. Thus,mostly concepts remain unnoticed.
  Thus the main motive of our project is to simulate two scheduling algorithms using OPENGL . We try to display how CPU schedule the process using various algorithms in the form of graphics.So that learning and interpreting the scheduling algorithms becomes intuitive and fun. We are trying to simulate two scheduling algorithms namely : Round Robin and Shortest Job First


# Project flow 
The interaction with the windows is initialized using glutInit() OpenGL API.The display mode-double buffer and depth buffer is,various callback functions for draeing and redrawing, for mouse and keyboard interfaces, input and calculate functions for various mathematical calculations, the window position and size are also initialized and create the window to display the output.
<img src="https://github.com/Shyam-AI/shredder-machine/blob/master/shredder-proj-plan.png" width="800px" height="auto">

# Output screenshots

1) Round Robin
<img src="https://github.com/Shyam-AI/Opengl-miniproject/blob/master/cgl-images/round%20robin.jpg" width="250px" height="auto">

2) Shortest Job First
<img src="https://github.com/Shyam-AI/Opengl-miniproject/blob/master/cgl-images/shortest%20job.jpg" width="250px" height="auto">

3) Average waiting and turn around time
<img src="https://github.com/Shyam-AI/Opengl-miniproject/blob/master/cgl-images/terminal%20image.jpg" width="250px" height="auto">

