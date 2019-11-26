# EEE3095S_Prac3
I2C and PWM
----
Task:
----
Before connecting to the internet for the ﬁrst time, you may have noticed that the time on your Pi is a little strange. This is because the Pi doesn’t have what is called an RTC (real time clock). Instead, it relies NTPD (Network Time Protocol Daemon) to fetch, set and store the date and time. However, this might be problematic as you may not always have an internet connection, and if your Pi doesn’t have the correct localisation options, you may end up with the wrong time due to timezone settings. It’s possible to add an RTC to the Raspberry Pi to hold the system time correctly, but for this practical we’re simply going to interface with the RTC using I2C, and set the time using buttons and interrupts.
