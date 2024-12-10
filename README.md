# Objective-C Memory Leak: Double Retain Bug

This repository demonstrates a subtle memory leak in Objective-C caused by double-retaining an object without a corresponding release.  The `bug.m` file contains the problematic code, while `bugSolution.m` provides a corrected version.

The bug arises from a misunderstanding of manual memory management using `retain` and `release`.  Incorrect handling of these methods, particularly in complex object relationships, can lead to memory leaks that are difficult to diagnose.

This example highlights the importance of careful attention to detail when working with manual reference counting in Objective-C, especially in scenarios involving circular references or deeply nested object graphs.