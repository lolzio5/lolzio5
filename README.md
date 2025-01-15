# Welcome to Lolézio's profile!

I'm an Electronics and Informations Engineering student at Imperial College London, with a passion for developing AI applications to increase efficiency of processes.

![C++](https://img.shields.io/badge/C%2B%2B-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/Python-FFD43B?style=for-the-badge&logo=python&logoColor=blue)
![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)

## Quick stats
![Lolézio's GitHub stats](https://github-readme-stats.vercel.app/api?username=lolzio5&show_icons=true&theme=radical&hide_rank=true&hide=issues,stars)

[![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=lolzio5&layout=compact&theme=vision-friendly-dark)](https://github.com/anuraghazra/github-readme-stats)

## About me
I come from France, but have lived in Vienna, Austria and London, United Kingdom.

I speak French, English, Spanish and German.

I love travelling and have been to 36 countries/territories so far!

## Experience
- Data Science Intern at Equinor
  - Used Natural Language Processing (NLP) to automatically find a relevant document betweens thousands
  - Implemented a custom Selenium web scraper to dynamically load webpages and extract data to form a document database
  - Using Retrieval Augmented Generation (RAG), leveraged an LLM to generate an answer to a question based on relevant documents extracted from the database using NLP
  - Hosted the solution in the cloud using Docker and Kubernetes
  - Created a ChatBot type application using HTML/CSS/JavaScript and Python for an easy interface
 
## Notable Projects
- [FPGA Accelerator for parallel computing](https://github.com/lolzio5/JABBAL)
  - Implementation of Conway's Game of Life on a PYNQ-Z1 FPGA board using custom hardware
  - User Interface using Computer Vision to detect drawing movements and pause signals
  - Real time evolution of a 1280x720 grid at a maximum of 200 000 evolutions per second
  
- [32-Bit RISC-V ISA CPU Design and Implementation](https://github.com/lolzio5/Team05-RISCV-Final)
  - Fully functional CPU with pipelining, data cache and automatic hazard handling and branch prediction
  - Use of SystemVerilog, C++ and RISC-V ISA
  - Comprised of a Program Counter, Control Unit, Hazard Handling Unit, Data Memory RAM, Instruction Memory ROM, Data Cache and Pipeline Registers
 
- [2 Player Flight Simulator with wireless FPGA controller](https://github.com/lolzio5/theflyingproject)
  - Features 2 DE10-Lite FPGA controllers, using switches, buttons and onboard accelerometer to control a plane
  - FPGA controllers wirelessly connect to AWS EC2 instance to asynchronously process inputs and output next plane state
  - State of both planes rendered in the same 'world' with Unreal Engine 4 to provide smooth gameplay
  - The goal of the game is to use the FPGA as a joystick to control and race the other plane through a portal
  - Time taken is recorded and stored as a highscore in a DynamoDB AWS database

- [Remote Controlled Rover](https://github.com/saturn691/Fyrryx)
  - Functioning rover robot capable of movement in 4 directions
  - Remote controller with Wifi communication
  - Capable of measuring magnetic fields, decode radio signals and decode infrared signals
  - Dual Arduino board with I2C protocol for multi-threaded control, sensing and filtering
  - 3D Printed frame

- [Autonomous search-and-rescue quadcopter](https://github.com/lolzio5/uavproject)
  - 4-rotor Drone capable of detecting and avoiding obstacles autonomously
  - Use of the YOLOv3-tiny convolutional neural network to automatically locate obstacles in field of view
  - Custom made algorithm using simple trigonometric principles to find the shortest path around the obstacle
  - Designed to travel from a Point A to a Point B as fast as possible in Alpine search-and-rescue operations
  
- [RISC-V ISA C-Language Compiler](https://github.com/lolzio5/c-compiler)
  - Implemented in 48 hours
  - Implemented functions and function calls, variables, data types, arithmetic and boolean operations
  - Capable of compiling a C-90 program into RISC-V Assembly
