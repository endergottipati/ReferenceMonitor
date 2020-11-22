# ReferenceMonitor
Implement a Defensive Security System
Created a reference monitor using the security layer functionality in Repy V2. 

A reference monitor is an access control concept that refers to an abstract machine that mediates all access to objects by subjects. 

This can be used to allow, deny, or change the behavior of any set of calls.

This security layer  keeps a backup copy of a file in case it is written incorrectly. 

This is a common technique for things like firmware images where a system may not be able to recover if the file is written incorrectly. 

A valid file must start with the character 'S' and end with the character 'E'. 

If any other characters (including lowercase 's', 'e', etc.) are the first or last characters, then the file is considered invalid.

The three design paradigms are accuracy, security, and efficiency.
