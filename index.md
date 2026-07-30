# Hexabee

The Hexabee is a modified version of the Freenove Hexapod Robot. It is a six legged robot designed to move and look similar to a bee. Each leg is made up of three servos which can be controlled through a computer program, an iphone app, or a physical remote control. The body of the Hexabee is a 3d printed bee modeled using CAD. It's capable of displaying the distance of any obstacles it detects through the ultrasonic sensor and the current humidity and temperature through the DHT11 sensor.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Alice L. | Lynbrook High School | TBD | Incoming Sophmore

![Headstone Image](BlueStampProjectPic.jpg)
  
# Final Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/IYq5nveivSs?si=xY_JI1r71WWYH0K6" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE
### Description
### Challenges
### Next Step


# Second Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/AfRUrXuUrDk?si=9Ig_jzEa9r7GMSKy" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone
### Description
### Challenges
### Next Step

# First Milestone

<iframe width="560" height="315" src="https://www.youtube.com/embed/Yec_EKpSPK0?si=HAmwGK7f6RO3Eiup" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project

### Description
By following the set of instructions that came with the Freenove Hexpod Robot, I was able to complete the assembly and calibration for the body, legs, and servos of the robot and set up the Arduino IDE and the Processing software. The kit already came with prewritten code for the Freenove Hexpod Robot library, so all I had to do was upload the example codes to my robot. The Processing software was used to run the prewritten computer program that would be used to calibrate and control my robot through a USB cable or Wi-Fi module. I also set up the physical remote control that is connected to the hexapod through a wireless module. 
### Challenges
### Next Step

# Starter Project Milestone

## Retro Arcade Console

<iframe width="560" height="315" src="https://www.youtube.com/embed/C0KbTLukOyM?si=TB4xxQ1_YjlOvbIA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

### Description

Before the main project, we had to work on a starter project. Mine was the retro arcade consol which had a tedious amount of soldering pins and wires. I started out by soldering on the buttons and displays, which wasn't the most difficult. The real challenge was getting Hershey's Kisses-shaped solder joints and waiting for the solder to heat up, which felt longer than the actual soldering process itself. I then had to solder all the wires on to connect the battery case to the board and finished by assembling the case. 

### Challenges

The project itself was quite straightforward, until I realized I had soldered on the 6 pin component on the wrong way. I then proceeded to spend the next half an hour struggling to desolder this component turning my board into a burnt mess. However, I did learn of many disoldering ways including the solder sucker, solder wick, and as a last resort, brute forcing it out. Eventually, by using numerous disoldering techniques, I was able to remove the component, which was beyond usable at that point. I replaced it with a new one and made sure that I wouldn't make the same mistake soldering it on again.

### Next Step

Once I finished the starter project, I would be able to move onto my main project, the Hexapod, where I would learn more skills and come across even more difficult challenges.

# Schematics 
Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. 

# Code
Here's where you'll put your code. The syntax below places it into a block of code. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize it to your project needs. 

```c++
void setup() {
  // put your setup code here, to run once:
  Serial.begin(9600);
  Serial.println("Hello World!");
}

void loop() {
  // put your main code here, to run repeatedly:

}
```

# Bill of Materials
Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. 

| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| Freenove Hexapod Robot Kit | Hexapod Robot Base | $126.99 USD | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://store.freenove.com/products/fnk0031?variant=43034490110150"> Link </a> |
| Ultrasonic Sensor | Detecting distance | $3.36 USD per piece | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/Ultrasonic-2cm-450cm-Interface-Compatible-Raspberry/dp/B0GL8NJCVT/ref=sr_1_3_sspa?crid=NKKZC1Q62JB6&dib=eyJ2IjoiMSJ9.eqTALHM8pOp6RiYX3iy9K-MvzhafEKee88ft1CTWtWOb4LNq68VS1E7_Y6KdP5jwLhbT5wbWuV636T5pFtR5WnSmJ9RZ5lab8hYE5ESM_X30woLaNFeb6_2HSssmaNVmazfdoNouSdg45mmLOTdgVgNPW5ybADfFxF3daJE62J-F9Ztg4-yty62xIyZaGvQHWxtUoHFcd4RmtXFFip4X38zXw96ORkrjkQVUWe6vLUI.3-YSmvws2EEVWfhN7RcH0wtvYihLUwrme8vOsDFBKXY&dib_tag=se&keywords=Ultrasonic+Sensors+hc+sr04&qid=1785436739&sprefix=ultrasonic+sensors+hc+sr04%2Caps%2C181&sr=8-3-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&psc=1"> Link </a> |
| DHT11 3 Pin Sensor | Collecting humidity and temperature data | $3.00 USD per piece | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/BOJACK-Temperature-Humidity-Digital-Raspberry/dp/B09TKTZMSL/ref=sr_1_6_sspa?dib=eyJ2IjoiMSJ9.SR80wzYQct2PFw8GneEJJfGLB7gbkBRmRZ6MBkibfs3C02lpr2NzxHovDXm15C3vQ7P7OCiRdsZz4LFAhoiYjqpA3c9Nh1RV1XZRFKEI0ARDBYpqSAbnO1w2sjIiY0Y6X97-l8xQeF_ejL71uS-rCSJndWYZNrN9eYtKPow7xP6zgraaPwaJfWKNqZwZvFwyRFteU9Mn0SjD6TXdygEeBEP-Y3O9VF0pjyA_n94-xyI.i8bbrF9i0zvFxYftYQNZdmiOKiWjloKaQch0D8aAAZA&dib_tag=se&keywords=dht11%2Bsensor&qid=1785436791&sr=8-6-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9tdGY&th=1"> Link </a> |
| DHT11 4 Pin Sensor | Collecting humidity and temperature data | $1.99 USD per piece | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/](https://www.amazon.com/JESSINIE-DHT11-Digital-Temperature-Sensor/dp/B0BLG7R99R/ref=sr_1_7?crid=17UNSCYEEYMWD&dib=eyJ2IjoiMSJ9.rUhI0DglR1CncDz6S55DQKU7fqk4qTK4v_PWk62IUgmH0loCxbA55W9WI9-ZFfMkHO-ILWipurnqthPA7fYkjZ4inYMPrO6nCAu5AYNDIzo8qzQZbbR93rldxLX-aVTVxFP_tFT2oan_ScJpQo6nC_-LwphzlcY50lvuV9A5MG2mv_2jIUqZkr8djjO3cc3DvclJHGqmewo5bJJ-72Ro_4Aij3dsR7IVxMFfbMq6-Sg.5ifND2UMcG1FCtxEvhjp4mzY82GmHRDqnsFIlYBvx7M&dib_tag=se&keywords=dht11+4+pin+sensor&qid=1785437259&sprefix=dht11+4+pin+senso%2Caps%2C196&sr=8-7"> Link </a> |

# Other Resources/Examples
One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components.
- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/)
- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/)
- [Example 3](https://arneshkumar.github.io/arneshbluestamp/)

To watch the BSE tutorial on how to create a portfolio, click here.
