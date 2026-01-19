![Ultrasonic3](https://github.com/user-attachments/assets/f121063b-8e30-4328-98a7-146b89c36b71)

![Ultrasonic1](https://github.com/user-attachments/assets/49abdc6e-51f3-4693-95df-686d9365ce95)

I explored several Unreal Engine 5 scenes where the data drives both a widget’s background color and the noise amount of a Niagara particle effect.

![UltrasonicAnim_1](https://github.com/user-attachments/assets/bdd9d0b1-c47d-4a69-bef8-0c53ed7a026c)

![UltrasonicAnim_2](https://github.com/user-attachments/assets/6327057e-3855-4397-a2be-7bdf24fb2520)

On the Unreal Engine side, most of the logic was implemented directly in the Level Blueprint. The diagram below illustrates the approach: Niagara logic is highlighted in red, while the widget logic is shown in yellow, where incoming values drive a Material Parameter applied to an Image component in UMG.

![Blueprint](https://github.com/user-attachments/assets/b581f33b-4c79-4c64-ae42-1846d2a1f693)


