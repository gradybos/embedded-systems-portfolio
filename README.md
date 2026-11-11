# Grady Bosanko Embedded Systems Portfolio

## BLE Soil Moisture Monitor [[Full Repository]](https://github.com/gradybos/smart-moisture-monitor)

### Project Summmary
A BLE soil moisture monitor that allows me to check the current moisture of the soil as a percentage from my phone.
The motivation for this project was that whenever I try to take care of a plant, I always find myself wondering
when I should be watering it. Watering it too much or too little can easily kill the plant, so having a way to
remotely check the soil moisture content is incredibly helpful.

### Motivation
Additionally, I am always looking to improve my skills as an engineer, and taking on this project allowed me to learn
many new things. On the hardware side, I gained exposure to KiCad, PCB layout design, working with PCB manufacturers, and bringing up
a custom PCB. For firmware, I learned about the nRF Connect SDK, Zephyr RTOS, how to enable ADC channels in Zephyr, how to create
custom board files for the nRF Connect SDK, how to use the nRF Connect BLE stack, and how to use semaphores to improve the
efficiency of a device.

### Technologies Used
* Embedded C
* nRF52840
* nRF Connect SDK
* Zephyr RTOS
* ADC
* Semaphore synchronization
* Bluetooth low energy (BLE)
* GATT
* KiCad
* Schematic Design
* PCB Layout
* Soldering
* Hardware Bring-up
* Component Testing
* Git/Github

### Demo

![Device in plant](https://github.com/gradybos/smart-moisture-monitor/blob/main/images/devicefinal.png)

### Full Project
To see the full project including source code and schematics, [follow this link](https://github.com/gradybos/smart-moisture-monitor).

## USB Driving Simulator System [link]

### Project Summary
A USB powered driving simulator system including steering, pedals, and interrupt-driven buttons. Though many
USB driving simulator systems exist, our team's goal was to create a system which cut back on luxury features 
and focused on performance and precision to cut costs and address an underserved, entry-level market.

### Technologies Used
* Arduino
* ARM Cortex-M
* Teensy 4
* GPIO Interrupts
* PWM
* Git/Github
* Multimeter
* USB serial logging

### Results

### Key Takeaways
This project taught me about the product lifecycle from start to finish. Senior capstone projects at Union College
span across 3 terms. The first term focuses on market research and finding a niche or market that does not have
an existing sufficient solution. By the end of this term, a team has a problem statement, a proposed solution, and
background information on existing solutions in similar spaces. Going into the next term, teams look to flesh out
their proposed solutions. This is done by creating block diagrams, understanding the solution's systems and subsystems,
defining engineering specifications, and eventually comparing and selecting the components that will be included in the
final build. This term concludes with a detailed design including circuit schematics, block diagrams, specifications, and
justifications for component selection. The final term is where the product is physically assembled and benchmarked.

Having the opportunity to experience this process showed me how important it is to make well thought-out decisions in the
field of engineering. Problems can seem daunting at first, but by breaking them down further and further they become much
more manageable. The construction saying "measure twice, cut once" is equally true for component selection as well, since
buying components that do not work as intended wastes money, but more importantly time. In the world of professional engineering,
time is considerably more valuable than money since an engineer's time is expensive, and each day with an unfinished product is
a day that does not profit from that product. Being able to see this holistic process helped me understand these points.
