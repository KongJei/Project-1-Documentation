# Project-1-Documentation
Your name: Jei Kong

KAIST ID: 20190030

Email: kongj0531@kaist.ac.kr

Title of your project: J's Rabbit doll

Short description of the project:

J's Rabbit doll shows user's stress level by 'heart gauge' shown in number of brigthen neopixel(1 to 10). And can get relieve of stress by punching and shaking, and can get relax by holding hand with the J's Rabbit doll. By accelerometer in microbit, it detects punching and shaking(punching for short time in action, while shaking for longer time in action). And by force sensor, it detects holding hand. J's Rabbit doll not only detects whether or not action happens, but also detects how strong the action is, which is also shown by the number of neopixel led brightening. By punching and shaking, 'heart gauge' goes down, while by holding hand, it goes up. Which makes possible for users to keep track of how much they have stress today.

Image1, Image2, Image3 in the zip folder are pictures of circuit(breadboard, microbit, sensors, neopixel, battery, etc).

Instructions for users:

Users should just punch, shake, hold hand the J's Rabbit doll, and see 'heart gauge' shown by red leds from heart shape modeling.

If user punches the J's Rabbit doll, it detects the action then the blue leds will be shown and the number of blue leds is decided by the strength of the punch. And that amount of number of leds are lost in 'heart gauge'. 

If user shakes the J's Rabbit doll, it detects the action then the green leds will be shown and the number of green leds is decided by the power of the shake. And that amount of number of leds are lost in 'heart gauge'.

If users hold hands with the J's Rabbit doll which is a force sensor, it detects the action, then the yellow leds will be shown and the number of yellow leds is decided by the power of holding hand. And that amount of number of leds are added in 'heart gauge'.

If 'heart gauge' is high, user can recognize today was the happy day, but if low, today was the rough stressful day.

In order to prevent unmeaningful movement happened accidently in J's Rabbit doll, I set some limits for the J's Rabbit doll to detect only meaningful action. But it sometimes don't detect the action when the action doesn't effect strong enough. Then, the user can just try again with stronger power or hit or shake more directly to the microbit which is inside the doll.

Acknowledgements:

I got inspiration from two things. One is a 'punch machine', and the other is 'Enter Key Cushion'.

I get help from Technician Jung Teacher at the Audi Lab. He helps me soldering, and some wire connection issues 

[OPTIONAL] Images/Additional material link: https://a360.co/3kU3cxp
this is my 3d modeling (fusion) assembly (shape of a heart)

[OPTIONAL] Comments:
Write here any comments you might want to tell to the instructor or TAs.
