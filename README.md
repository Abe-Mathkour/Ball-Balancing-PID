# Ball-Balancing-PID
Objective: Balance a ball within a specific area moveable platform.

The project uses the following components:
- Base (Shown below)
- Platform (Shown Below)
- 2 Servo Motors
- 2 Linkage Arm
- 2 smooth bearing balls
- Smartphone camera

The instructions on how to assemble will follow once complete.
<img width="1442" height="525" alt="Screenshot 2026-03-23 143027" src="https://github.com/user-attachments/assets/6caa326c-2a6f-4318-ad72-171352090a6b" />

Design Choices of the base: The base features 4 extending arms from the center with matching extrude cut to fit the servo motors with a snug fit. Only 2 servos are used but additional slots are available incase drilling fails or fatigue occurs. A pitch and fork design was used to prevent yaw movement. The height of the pivot was decide as a functional balance between the power and precisions the servo motors could handle.

Design Choices of the platform: The platform is 22cm by 22cm as a trade-off between weight and area allowing enough time for servos to calibrate changes or shifts if neccesary.


Update #1 i've changed the motion of the servos to prevent yaw rotation entirely, however, its introduced a new motion dynamic that I havent accounted for. Here is the current progress. <img width="1919" height="963" alt="image" src="https://github.com/user-attachments/assets/5c1e959a-30e2-4396-8350-4d79ef35858e" />
