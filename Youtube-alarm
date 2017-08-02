# -*- coding: utf-8 -*-
"""
Created on Wed Aug  2 13:43:22 2017

@author: Pardis
"""

# -*- coding: utf-8 -*-
"""
Created on Thu Jul 27 18:00:51 2017

@author: Pardis
"""
import time
import random
import subprocess
links=['https://www.youtube.com/watch?v=fyaI4-5849w','https://www.youtube.com/watch?v=weeI1G46q0o','https://www.youtube.com/watch?v=SC4xMk98Pdc']

current_time=time.strftime('%H:%M')
print(current_time)

alarm_time= input('Set the alarm in this format -->  18:30\n')
print("You have set the alarm for", alarm_time)
while (alarm_time!=current_time):
    current_time=time.strftime('%H:%M')
    time.sleep(1)
else:
    x=random.choice(links)
    subprocess.Popen([r'C:\Program Files (x86)\Google\Chrome\Application\chrome.exe', x]).wait()
    'opens the chosen link in a chrome browser'
    print("it\'s time to wake up!")
