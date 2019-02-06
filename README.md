# take-a-break
#take a break program written in python, for fun I only added a youtube video to watch when I take a break. Testing purposes time sleep is only 10 sec.

import webbrowser
import time

total_breaks = 2
break_count = 0

print("The program started on " +time.ctime())
while(break_count < total_breaks):
    time.sleep(10)
    webbrowser.open("https://www.youtube.com/watch?v=a01QQZyl-_I")
    break_count = break_count + 1
