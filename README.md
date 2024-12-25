# Core Data Retain Cycle Bug in Objective-C

This repository demonstrates a common bug in Objective-C related to Core Data and memory management.  Improper handling of fetched managed objects can create retain cycles, leading to memory leaks and unexpected application behavior. The `CoreDataRetainCycleBug.m` file contains the buggy code, while `CoreDataRetainCycleBugSolution.m` shows the corrected implementation.