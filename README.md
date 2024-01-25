# APC Injection

Another way to run a payload *without having to create a new thread*.


## What is APC

Asynchronous Procedure Calls are a Windows OS system mechanism that enables programs to execute tasks asynchronously while continuing to run other tasks. 
APCs are implemented as kernel-mode routines that are executed in the context of a specific thread.
*Malware can leverage APCs to queue a payload* and then have it execute when scheduled.
