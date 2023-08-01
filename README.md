# Ultrasonic-Distance-sensor

Principle of operation. Ultrasonic distance sensors determine the distance or presence of a target object by firing a pulsed ultrasonic wave at it and then measuring the time it takes for the sound echo to return. The sensor can determine the distance of an object by knowing the speed of sound.

can calculate the distance between two points regardless of shape, color, or surface texture. They may also detect an approaching or retreating item.



![Ultrasonic Distance Sensor_M](https://github.com/MohammedAwadhh/Ultrasonic-Distance-sensor/assets/139158830/beb961b1-f312-4339-bfd4-97484eb0bd6e)





### Basic ingredients
| component | Description |
| ----------- | ----------- |
| LCD | LCD (Liquid Crystal Display) is a type of flat panel display that operates primarily with liquid crystals. LEDs have a wide range of applications for both consumers and companies. |
| Ultrasonics | Ultrasound is simply sound that has a frequency that is higher than 20 kHz and cannot be heard by the human ear. Ultrasound is employed at frequencies up to several GHz at the high end of the spectrum. |
| potentiometer | A potentiometer is a manually adjustable variable resistor with 3 terminals. Two of the terminals are connected to the opposite ends of a resistive element, and the third terminal connects to a sliding contact, called a wiper, moving over the resistive element. |

### The circuit of LCD

The circuit:
  * LCD RS pin to digital pin 12
  * LCD Enable pin to digital pin 11
  * LCD D4 pin to digital pin 5
  * LCD D5 pin to digital pin 4
  * LCD D6 pin to digital pin 3
  * LCD D7 pin to digital pin 2
  * LCD R/W pin to ground
  * LCD VSS pin to ground
  * LCD VCC pin to 5V
  * 10K resistor:
  * ends to +5V and ground
  * wiper to LCD VO pin (pin 3)



### image of potentiometer




![potentiometer](https://github.com/MohammedAwadhh/Ultrasonic-Distance-sensor/assets/139158830/2adbece3-ba08-4180-9b76-c58f0a00cc24)




### The working principle of Ultrasonic

The Ultra Sonic HC-SR04 emits ultrasound at 40,000Hz that travels in the air. If there is an object or obstacle in its path, then it collides and bounces back to the Ultra Sonic module.
The formula distance = speed*time is used to 

calculate the distance.
Suppose, an object is placed at a distance of 10 cm away from the sensor, the speed of sound in air is 340 m/s or 0.034 cm/µs. It means the sound wave needs to travel in 294 µs. But the Echo pin double the distance (forward and bounce backward distance). So, to get the distance in cm multiply the received travel time value with echo pin by 0.034 and divide it by 2.

distance = speed*time/2





### Work at Tinkercad

https://www.tinkercad.com/things/1nt1Da9ISfh-ultrasonic-sensorm/editel



![Ultrasonic Sensor](https://github.com/MohammedAwadhh/Ultrasonic-Distance-sensor/assets/139158830/20c14684-4e24-4aa7-a675-8eafa6285bc1)


