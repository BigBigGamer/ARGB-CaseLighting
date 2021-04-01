# ARGB-CaseLighting
PC case ARGB lighting for builds with no ARGB 3 pin headers on motherboard, based on ESP32 and control through Flutter-based application

# What is it
This project is to give full control of ARGB fans, LED strips, and anything that has a 3-pin ARGB connector (let's call them ARGB devices) via desktop application for PCs based on motherboards without built in 3-pin ARGB connector.

Control of signals sent to ARGB devices is done via ESP32 board with Micropython, which will receive instruction for colors and color schemes from desktop app. The desktop app is created using Flutter.
