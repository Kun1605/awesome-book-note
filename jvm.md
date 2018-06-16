# Book
![](/imgs/jvm/jvm-book.jpg "《深入理解Java虚拟机 第2版》")

## 目录

- [Java内存区域与内存溢出异常](#OOM "Java内存区域与内存溢出异常")
    - [运行时数据区域](#RUNTIME-AREA)
    - [HotSpot虚拟机对象](#HOTSPOT-OBJ)
    - [总结](#OOM-SUMMARY)
- [垃圾收集器与内存分配策略](#GC-MECHINE-AND-MEMORY-ALLOCATION-STRATEGY)
    - [概述](#GC-OVERVIEW)
    - [引用](#REFERENCE)
    - [垃圾收集算法](#GC-ARITHMETHIC)
    - [HotSpot的算法实现](#HOTSPOT)
    - [内存分配与回收策略](#MEMORY-ALLOCATION-STRATEGY)
- [类文件结构](#CLASS-FILE-STRUCTURE)
- [虚拟机类加载机制](#CLASSLOADER)
    - [类加载的时机](#CLASS-LOAD-TIME)
    - [类加载的过程](#CLASS-LOAD-PROCESS)
    - [验证](#FILE-VALIDATION)
    - [准备](#FILE-PREPARE)
    - [解析](#FILE-ANALYSIS)
    - [初始化](#FILE-INIT)
    - [类加载器](#CLASSLOADER-MECHINE)
- [Java内存模型与线程](#MEMORY-MODEL-AND_THREAD)
    - [物理机的内存模型](#PHYSIC-MEMORY-MODEL)
    - [Java内存模型](#JAVA-MEMORY-MODEL)
    - [Java与线程](#JAVA-AND-THREAD)
- [线程安全和锁优化](#THREAD-SECURITY-AND-LOCK-OPTIMIZE)


#### Java内存区域与内存溢出异常