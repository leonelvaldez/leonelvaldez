# Hi, I'm Leonel Valdez

I'm a second-year Robotics and Intelligent Systems student at Constructor University in Bremen, Germany. I'm originally from Mexico City, where I did my IB diploma before moving to Germany for university.

I chose robotics because for me it's the perfect combination of software and hardware. I've always been close to the area through robotics clubs and competitions growing up, so studying it felt like the natural choice. Right now I'm most interested in perception, manipulation and autonomous systems, and I'm starting to get more into the AI and machine learning side of things as well.

I'm currently looking for a summer internship in robotics, open to software, perception, embedded or anything in between.

---

## What I'm currently working on

My main project right now is a computer vision module for a robotic Memorama card game using a Kinova dual-arm robot. The idea is that the robot plays the game against a human player. It lifts boxes with both arms, uses the wrist cameras to identify the cards glued underneath, and decides whether it found a matching pair.

I originally built this as a personal project to practice real-time shape detection using computer vision, and later adapted it as the vision component for our university game pipeline. I built it using OpenCV. The pipeline does adaptive thresholding, contour-based quad detection, perspective warp to get a clean top-down view of the card, and MSE template matching across 4 rotations to handle any card orientation. I also wrote the ROS node that connects it to the Kinova wrist camera feed.

I kept the approach classical and lightweight because the set of shapes is small and fixed (8 card types), and I wanted something I could actually debug and tune while working on the robot. It works well in practice, though lighting conditions can still affect the MSE threshold depending on the setup.

Check it out here: [card-detector-kinova-robot](https://github.com/leonelvaldez/card-detector-kinova-robot)

More projects coming soon.

---

## Technical skills

Languages and tools I use regularly:
- Python, C/C++, Assembly (AVR/ARM)
- ROS (Noetic), OpenCV, NumPy, rosbag, RViz
- Linux/Ubuntu, Git
- ATmega328/AVR, PWM, ADC, interrupt routines, circuit prototyping
- SQL (MariaDB), Flask, LaTeX
- scikit-image, scikit-learn

---

## A bit more about me

I speak Spanish (native), English, German and French, which has been useful living in Germany and working with people from a lot of different places. 
Outside of university I won the 2024 GDG Ideathon in Bremen and built an ESP32-based aquatic farming robot in a 48-hour hardware hackathon. That one was exhausting, but it was a really fun experience and a good chance to apply things I had learned in class with a great team.

If you want to get in touch: leonel.valdezc@gmail.com

LinkedIn: [linkedin.com/in/leonelvaldez](https://linkedin.com/in/leonelvaldez)
