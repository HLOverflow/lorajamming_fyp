# lorajamming_fyp

Version 1.0		
Previous FYP Jia Hui's Work (prototype)
delay execution until the clock reach the next minute 0 second mark.

Version 2.0
improve delay execution to every 0, 15, 30, 45 second mark.	~4 times faster in collecting results.
Improved upon, rearranged by Hui Lian  (TCP API interface, multithreading, Object Oriented)
makefile available for easy compilation in one go.
summary:
2 RPIs as sender
1 RPI as receiver
provide commands via TCP port 8000
receiver will log results to output/result.txt

Version 2.1
added a "clear result;" api

Version 2.2
changed most char * to const char * so that it is easier to work with using string.c_str()
Note: 2.2 is not backward compatible to the previous versions due to massive data type changes.
added 'get time' api in milliseconds.

Version 3.0
To be work on.

