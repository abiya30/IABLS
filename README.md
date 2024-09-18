Intrusion Alert Based Login System (IABLS)
IABLS is a web-based security framework designed to safeguard login systems by live monitoring and intrusion attempts, such as brute force attacks. The system incorporates real-time surveillance through a web camera and raises an alarm for the legitimate user against unauthorized access.

Key Features
Intrusion Detection: It identifies malicious login attempts in real-time, such as brute-force attacks.
Real-Time Monitoring: Uses a webcam to capture the image of the intruder when it detects unauthorized access.
User Alerts : It sends instant alerts to the legitimate user by email or other communication channels when there is an intrusion detected.
Secure Login: It enhances the security aspects of a login page by not allowing any probable unauthorized access and alerting the users ahead.
Login Page Monitoring -the system is permanently monitoring the login page for strange trends like mass failed login attempts
Intruder Detection- if the system detects an intrusion event, such as brute force attempt, it immediately acts to switch on the web camera
Image Capturing the system captures an image of the suspected intruder through the linked up webcam.
User Alert: An alert along with the picture of the intruder, is sent to the original user, informing him of the suspicious activity.

Installation and Setup
      Clone the repository
      Install dependencies
              pip install -r requirements.txt
      Run the application
              python app.py
Technologies Used
Python: The backend logic for Intrusion Detection as well as management of alerts.
Flask: This is a web application framework.
OpenCV: It captures the images from the web camera.
SMTP: This is used for sending alerts to mail ids of users.
Database: It keeps the user login attempts and intruder details.

Future Extensions
Multi-Factor Authentication: Using MFA in a different hierarchy for securing the login system.
AI Integration: Better capability to detect sophisticated threats using AI. Means, that can identify between the wrongful attempt of intrusion and actual attempt of intrusion.


Contributions are most welcome! Do open an issue or even a pull request if you have any suggestions or improvements.


