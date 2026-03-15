### Brute Force

Security Level: Low

Payload:
Username: admin
Password: password

Result:
Login successful.

!(screenshots/BruteForce_low.png)

Explanation:
The application allows unlimited login attempts without implementing rate limiting or account lockout mechanisms. This enables attackers to guess credentials through brute force attacks.
