# Matrix
Matrix is a compact 4-port USB hub PCB built around the SL2.1s hub controller, featuring two USB Type-C ports and two USB Type-A ports, with proper decoupling and power filtering throughout.

Why I Built Matrix:
I'm constantly juggling hardware at my desk  microcontrollers, dev boards, programmers, peripherals. Every session turned into a cable management nightmare and I kept running out of USB ports at the worst moments. I wanted something small clean, and built with purpose.
Matrix started as a simple idea: what if I just made my own?

What It Does:
Matrix is a compact 4-port USB hub built around the SL2.1s hub controller IC. It takes a single USB input and expands it into two USB Type-C ports and two USB Type-A ports, all on a single small PCB. 

How It All Fits Together:
The SL2.1s sits at the center of the board, managing all four downstream ports. Each port has its own bypass capacitors for clean power delivery. The Type-C ports include CC resistors for proper device detection, and the whole board runs off a single 5V input.

<img width="915" height="491" alt="Screenshot 2026-05-20 175406" src="https://github.com/user-attachments/assets/db318261-9cb8-4b0d-9e2e-a1e5edb2e247" />
<img width="1342" height="752" alt="Screenshot 2026-05-20 185521" src="https://github.com/user-attachments/assets/2ed08da9-ef4e-4b29-a90c-7599e91eccf5" />
<img width="475" height="510" alt="Screenshot 2026-06-10 195925" src="https://github.com/user-attachments/assets/73378501-aa5a-4437-8e2f-74dce09bbab5" />

