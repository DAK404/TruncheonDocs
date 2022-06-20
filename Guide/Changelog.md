# Truncheon: Katana Update Changelog

This is the first update to Truncheon, providing many changes,
improvements in the aspects of security, performance and program
flexibility.

All the changes made in Katana's codebase, compared to the original.

For more detailed information, please check the GitHub commits.

---

# What's new in v1.1.0 "Katana"

| Criteria | Detail
| --- | --- |
| Started on | 14-Feb-2022 |
| Status | Under Development |
| Update Type | Major, Important |
| Code Availablity | GitHub Repository |
|  |  |


## Additions

These are the additions made to the code, improving Truncheon.

* **Abraxis Integrity Verification**: A new logic has been added to verify the Kernel Files right before it boots. This means that if a file has been tampered with, the Kernel will refuse to boot, and will resort to boot into repair mode.

* **Repair Mode**: A new logic that can help in dealing with issues related to Kernel files failing integrity checks. It can scan for bad files, download the latest build off the internet,  install it and try to fix the errors found.

* **Tulzscha Tools**: Brand new tools have been introduced, which are user-friendly and easy to work with. The tools are of 2 types: Interactive and Silent. While Interactive mode has a UI where the user can interact and perform a specific task, the silent tools are designed to work with text editors and help in running tasks easily, simplifying the overall workflow.

* **Custom IOStreams**: A new API is available that can help in color coding the outputs and make sure that different messages have can be shown with a specific color code. The different streams available are listed below:

```
[ INFORMATION ] THIS IS USED TO DISPLAY AN INFORMATION
[  ATTENTION  ] THIS IS USED TO DISPLAY IMPORTANT EVENTS
[   WARNING   ] THIS IS USED TO DISPLAY WARNINGS
[    ERROR    ] THIS IS USED TO REPORT AN ERROR

THIS IS A Normal Print Stream to print a normal message :)
```
* **Kernel Prober**: This is included in the Program Launcher that shall check if the specified Kernel is bootable or not. This will help users to check if the Kernel exists, is it bootable and will help to debug issues with Kernel booting up.

## Improvements

These are the areas which have been improved, or the areas of the program which have been improved.

* **Better Scripting System**: The scripting feature is getting an update, which means that the code and the performance have been optimized. This also means that there need not be individual implementations to add scripting functionalities to a new module introduced.

* **Better API Flexibility**: The APIs are now more flexible, has a better implementation and can be used efficiently across workflows. This helps in code debugging and code readability.

* **Better Code Standards**: By rewriting many modules and addressing code line by line, the logics and implementations adhere to standards now. This means that the code readability has been improved, whilst reducing redundancy.

* **More User Friendly Interface**: The program is now more user-friendly, thereby, allowing people to understand the context and help in achieving usability and efficiency over consuming extensive amounts of resources to understand workflows.

* **Fixed Code Issues**: At rare cases, the code would result in a strange outcome, and not perform the desired action. These issues have been fixed.

* **Optimized Resource Usage**: The code has been optimized. It performs better whilst utilizing a small resource footprint.

## Deletions and Deprecations

These are things that have been removed from or deprecated in the program.

* **Unsafe Code Structures**: Sometimes, the code would have statements that may or may not cause memory leaks, redundancy and anomalous results. These statements have been removed and the code for those have been rewritten to make sure that the code is stable.

* **Login Authentication API**: The older login authentication program called `LoginAPI.java` has been removed and rewritten to optimize the way it works. It can also help if someone prefers to write their own program on top of it too!

* **Redundant Code And File Management Scripting Logics**: Well, removed these so that... a better logic could be implemented in its place.

* **Redundant Tools**: Older tools are gone for good. Newer tools are easier to use and work with. Should you want the older tools, please check commit history and extract it from there.

---

# Notes

Monthly changelogs are not yet implemented here, since the program is still under development. It shall be added once it is complete.

---