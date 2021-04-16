# SDLC Activity Based Learning
![Flames](                  https://github.com/man36725/Mini_Project/blob/main/1_Requirements/flames.jpeg            )

Visit [Pages for Report -optional](using github.io option)

Build | Code Quality | Unity | Git Inspector
|---------|------------|-----------|----------------
[![C/C++ CI](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/c-cpp.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/c-cpp.yml) [![Windows-C/C++ CI - Build Status](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/windows-c-cpp.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/windows-c-cpp.yml)| [![Static Cppcheck](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/cppcheck.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/cppcheck.yml) [![Dynamic Valgrind](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/CodeQuality_Dynamic.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/CodeQuality_Dynamic.yml)| [![Unity - Unit Testing](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/unity.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/unity.yml)| [![Git Inspector](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/gitinspector.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/gitinspector.yml)|[![coverage](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/gcov.yml/badge.svg)](https://github.com/ARJ051097/MiniProject-LTTS-256139/actions/workflows/gcov.yml)


## Folder Structure
Folder             | Description
-------------------| -----------------------------------------
`1_Requirements`   | Documents detailing requirements and research
`2_Design`         | Documents specifying design details
`3_Implementation` | All code and documentation
`4_Test_plan`      | Documents with test plans and procedures

## Contributors List and Summary

SF Id. |  Name   |    Features    | Issuess Raised |Issues Resolved|No Test Cases|Test Case Pass
-------|---------|----------------|----------------|---------------|-------------|--------------
`265039` | Lanka Maneesh Kumar  | Feature A, B etc    | X No     | X No   |X No   |X No     
   

| Feature Id | Feature |
| -----------|---------|
|F_01| Option to load older saved data |
|F_02| Save data to file if only new data is added |
|F_03| Update data in list and file(if in file) |
|F_04| Deleting record automatically updates Record file and Index File |
|F_05| New records gets saved in file at program shut down |
|F_06| Before program shut down all memory is freed and clean |
|F_07| Used Binary File System for quick access to files |
|F_08| Search of Data is possible from both List and file |
|F_09| Dynamic memory allocation and deallocation implemented |

## Challenges Faced and How Was It Overcome
| No. | Challenge | Solution
|-----|-----------|--------
|1. | Code Crashed without any error message (Segmentation Fault) | GDB tool helped to pin point the Invalid Read 
|2. | After program shut down, there was no way to recover data | Implemented File System |
|3. | IOWITHOUTPOSITIONING Error | Check if fseek() != -1 between consecutive read and write calls
|4. | Structure Padding causing write to uninitialized location(Still Reachable code error) | Won't Fix, need help
|5. | Requirement gathering proved to be challenging, mainly ageing | Read multiple Research papers to find about history of management systems 
|6. | gcov generating *.gcda and *.gcno files in different directory than object file | added few extra steps in make file under coverage, made a copy of .c file in current directory and ran coverage then deleted all the unnecessary files.

## Learning Resources
1. [markdownCheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)
2. [markdownBasics](https://guides.github.com/features/mastering-markdown/)
3. [git inspector](https://github.com/ejwa/gitinspector.git)
4. [github workflow](https://docs.github.com/en/actions/learn-github-action)

