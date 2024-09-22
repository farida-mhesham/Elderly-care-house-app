# Elderly-care-house-app
The Elderly Care House Application is designed to provide a comprehensive and user-friendly system for monitoring and assisting elderly residents in a care house. The application is connected to Firebase for user authentication and data storage, and it uses MQTT for real-time communication between the app and the hardware components.

# Features
1. User Authentication
Login and Sign-Up: Users can create accounts and log in securely using Firebase Authentication. This ensures that only authorized users can access the system.
2. Dashboard
Sensor Monitoring: The dashboard provides real-time monitoring of various sensors installed in the care house:
Heart Rate Sensor: Continuously monitors the heart rate of the elderly.
Light Sensor: Detects the ambient light levels.
Temperature and Humidity Sensor: Monitors the temperature and humidity to ensure a comfortable environment.
3. Puzzle Game
Cognitive Engagement: A puzzle game designed to keep the elderly's brain active and engaged. This feature helps in maintaining cognitive health.
4. Emergency SOS Button
Emergency Alert: An SOS button that the elderly can press in case of an emergency. This sends an alert through MQTT to trigger a buzzer in the hardware, notifying caregivers immediately.
5. Manual Control
Light Control: Allows the elderly to control the lights in their room.
Fan Speed Control: Provides the ability to adjust the fan speed for personal comfort.
Window Control: Enables the opening and closing of windows to regulate ventilation.
