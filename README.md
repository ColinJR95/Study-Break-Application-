# Study-Break-Application-in Python
import time
import webbrowser

total_breaks = 4
break_count = 0

print ('This program started on ' + time.ctime())
while (break_count < total_breaks):
    time.sleep(60*60)
    webbrowser.open("https://www.youtube.com/watch?v=oEUIcRcobbg")
    break_count = break_count + 1
