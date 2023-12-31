# F1 Tyre Temperature System
IOT system, for checking the temperature of the formula 1 cars tyres, using MQTT and CoAP.

Formula 1 racing is a pinnacle of motorsport known for its high speeds, technical expertise, and relentless pursuit of perfection. The performance of a Formula 1 car depends on numerous factors, and tyre temperature is one of the critical parameters that can make a significant difference on the track. Proper tyre temperature management ensures optimal grip, stability, and tyre wear, allowing drivers to push the limits of their cars while maintaining control. Our project focuses on developing an IoT-based solution for monitoring the temperatures of Formula 1 tyres. The system consists of sensor-equipped devices installed on each tyre, capable of collecting temperature data in real-time. These sensors communicate with a central monitoring unit wireless, transmitting the temperature readings for analysis and visualization.

<br>
The deployed sensors in Formula 1 cars and tyre-warmers play a crucial role in enabling com- prehensive monitoring of tyre temperature. These devices are instrumental in capturing real-time data whether the car is on the track or in the box, facilitating automated monitoring and man- agement of temperature. By continuously monitoring tyre temperature, engineers and drivers gain valuable insights into the temperature conditions, empowering them to proactively respond to dynamic changes and ensure optimal tyre temperature conditions.
In addition to providing comprehensive monitoring, our IoT solution incorporates two type of actuators specifically designed for real-time interaction with the devices. These actuators include the tire warmers themselves and the steering wheel lights. Leveraging a centralized server, the collected sensor data is analyzed, interpreted, and used to deliver precise instructions to the relevant actuators. This closed-loop control system enables timely and responsive interventions to maintain optimal tire temperatures, especially to ensure compliance with Formula One regulations, where tire temperatures should not exceed 70 degrees Celsius while inside the warmers. Through our system, teams can confidently stay within the allowed limits defined by the sporting regulations, and drivers can effectively manage tire temperature and minimize tire wear on the track.
<br>

 - Real sensors have been used running ContikiOS
 - A support MySQL database collects data from the sensors
    - Grafana was used to display collected data

<br><br>

*Collaborator: Gabriele Marino*