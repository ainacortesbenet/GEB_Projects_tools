# Practica Projectes - Aina Cortes i Maria Garcia

### Description of the work done
In this lab session, we have done a first approach on working with arduino. Firstly, as we had never used github before, we had to learn the basics following the steps to copy the teacher's main project to our account. Then, we were able to learn how ESP32 worked. We made a new test project for our ESP32 board and wrote a short code to make the small LED on the board blink. We sent the code to the ESP32 and checked the screen to see if it worked.

After that, we worked on getting 3D movement data from the sensor into a computer simulation. In the class, we sent the Endowrist_IMU code to the ESP32 and then we opened the 3D_Orientation file in the RoboDK program and ran a Python script. We saw a 3D object on the computer move exactly how we moved the sensor in our hand.

Finally, we simulated everything on our laptops. We installed the robodk tools, opened the RoboDK simulation, and ran a Python script with sliders on the screen. This script acted like the real sensor. By running the receiving script at the same time, we moved the 3D object in RoboDK using the sliders. It was exactly like what we did in class with the real board.

### Questions

- Is the plane 3D object in roboDK moving properly?
Yes, the plane moved correctly. When we moved the real sensor in class, the plane in RoboDK moved at the same time and copied our movements perfectly.

- What you have made to properly verify the orientation angles Roll, Pitch and Yaw?
To make sure the angles were correct, we tested them one at a time. First, we moved only the Roll to see the object tilt side-to-side. Then, we tested Pitch to see it tilt front-to-back. Finally, we tested Yaw to see it spin. 
  
- Change the 3D object orientation to "surgical_needle". What you have to change in the python code?
To change the object, we just needed to change a small text in the Python script. We found the line that said item = RDK.Item('plane') and changed the word 'plane' to 'surgical_needle'. Here are two images of the surgical needle.
<img width="1366" height="679" alt="image" src="https://github.com/user-attachments/assets/441d1052-8263-4e92-868d-83f64130fd72" />
<img width="1366" height="696" alt="image" src="https://github.com/user-attachments/assets/8d5fab18-4534-4668-9963-7deb169a3e8c" />


### Conclusion
We think that this lab was a very good introduction to organizing our projects. Since we had never used GitHub before, it was all new to us, but we see why it is so useful for saving code and working together. In our project we will need to use an ESP32 and connect it with RFID technology, so we think that this lab session and mainly the part of setting up the Arduino  will be very useful for our project. We also believe that this knowledge will be useful when we start working on our TFG, since it will probably include coding documents that we have to store and share in GibHub.

