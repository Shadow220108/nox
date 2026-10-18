---
title: Nox    
author: Shadow
description: A USB 3.0 Hub supporting upto 5 GBps 
created_at: 2026-10-18
---


## Starting with Research and picking the components - 2.5 Hours
I am building a usb hub ( and name it nox ) I want it to be USB 3.0 and reach high speeds unlike the previous
USB Hub which I made. It is my first time designing something to carry high speed data signals, so I started 
with the research today

Things which I planned to have in it :  
- It is gonna be 4 ports, 2x USB-A and 2x USB-C  
- 5 Gbps speed  
- Powered through USB-C so it can power the stuff you plug into it.

  I read through this document from texas intrsuments
  <img width="837" height="752" alt="image" src="https://github.com/user-attachments/assets/746cecb6-d1b7-4917-a8ff-bc82dd1a41be" />
to know more about the USB-C and how do I power the USB hub, this helped me in deciding the ICs which I will use for my hub

<h4> Deciding the chip </h4>  

I looked at few chips ( mainly 3 ) options for a 4-port, 5 Gbps hub:  

- TUSB8041   
- Microchip USB5744  
- VIA Labs VL817  

I am going with TUSB88041 cause T1 has a really detailed datasheet and a reference design which I will be taking help of while designing
