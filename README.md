The project proposes CURT (Coronavirus Unmanned Remote Tester), a robotic system designed to measure a patient’s forehead temperature remotely, reducing direct contact between medical staff and patients during situations such as the COVID-19 pandemic. 
This reduces exposure risk and lowers the physical burden on medical workers who would otherwise wear heavy protective equipment.

To perform temperature measurement accurately, the robot follows a defined “nominal path” across the forehead. 
This path was based on an average forehead length of 130 mm, with upper and lower boundaries considered to account for variation in forehead sizes. 
However, because this path is based on average data, the system may show limitations for individuals with significantly different facial proportions, highlighting a need for adjustable path lengths.

The robot uses an articulated coordinate system to manage its movements. Through mathematical modelling and Denavit-Hartenberg parameters, the robot achieves three forms of motion essential for temperature scanning:
Roll (left-right movement), Pitch (up-down adjustment for different heights), and Yaw (adjusting distance from the forehead)
These movements allow the temperature sensor at the end effector to follow the designed path accurately.

The project also identifies key stakeholders, including manufacturers, hospital administrators, doctors, nurses, and patients, each with different priorities such as cost efficiency, safety, accuracy, ease of use, and seamless integration into hospital systems. 
By refining component cost, programming, and data transfer to medical monitors, CURT can be implemented effectively in real medical environments
