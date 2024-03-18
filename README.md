# Arduino-based Obstacle Avoidance Robot

This project is an Arduino-based obstacle avoidance robot that utilizes ultrasonic sensor readings to detect obstacles and navigate around them. The robot incorporates a servo motor for scanning and two DC motors for movement.

## Features
- Real-time distance measurement using an ultrasonic sensor and servo motor for scanning.
- Obstacle detection, avoidance, and navigation algorithms.
- Control of DC motors using the AFMotor library.
- User-friendly interface for easy control and customization.

## Dependencies
- Arduino IDE
- AFMotor library
- NewPing library
- Servo library

## Getting Started
1. Install the required libraries in the Arduino IDE.
2. Connect the ultrasonic sensor, servo motor, and DC motors to the Arduino board.
3. Upload the code (`obstacle_avoidance_robot.ino`) to the Arduino board.
4. Observe the robot as it navigates around obstacles.

## Usage
The robot will move forward until it encounters an obstacle. When an obstacle is detected:
- It stops.
- Moves backward.
- Scans the area to the left and right using the servo motor.
- Chooses the direction with the greater distance and turns accordingly.

## Contributing
If you'd like to contribute to this project, please follow these steps:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature/add-new-feature`).
3. Make your changes.
4. Commit your changes (`git commit -am 'Add new feature'`).
5. Push to the branch (`git push origin feature/add-new-feature`).
6. Create a new Pull Request.

## License
This project is licensed under the [MIT License](LICENSE).

## Acknowledgements
- Inspiration: [Provide inspiration/source if any]
- Libraries: AFMotor, NewPing, Servo
