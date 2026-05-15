# Access_Control
- This repository contains my submission for the Google Cybersecurity Certificate activity following its given situation.

# Summary :
- On October 3, 2023, a system event was recorded involving a login from the IP address 152.207.255.255, associated with a user in a Legal/Administrator role. During this activity, Robert Taylor Jr, who is listed as an administrator, was identified as having accessed payroll systems. This is notable because his contract officially ended in 2019, yet his account was still active and able to interact with sensitive systems in 2023. The situation highlights several security and access-control concerns. Ideally, user accounts should automatically expire after 30 days of inactivity or at the end of their contractual period. Contractors should also be restricted to only the minimum necessary business resources to reduce risk exposure. In addition, the incident emphasizes the importance of enforcing stronger authentication controls, such as enabling Multi-Factor Authentication (MFA), to help prevent unauthorized or unintended access to sensitive systems like payroll.

# Authorization / Authentication :
# Note(s) : 
Identifies the threat.
- The event occurred on 10/03/23 and involved a user with a Legal/Administrator role. The login was made from a computer using the IP address 152.207.255.255.

# Issue(s) :
Authorization issues.
- Robert Taylor Jr holds an administrator role. Although his contract ended in 2019, his account was still active and was used to access payroll systems in 2023.

# Recommendation(s) :
How could have prevented this kind of incident.
- User accounts should be configured to expire after 30 days of inactivity. Contractors should be granted only limited access to necessary business resources. Multi-Factor Authentication (MFA) should be enabled to strengthen account security.

# Conclusion :
- This activity shows the risks of poor account and access management, where a former contractor’s administrator account remained active and was still able to access sensitive payroll systems long after the contract ended. It highlights the need for strict enforcement of account expiration, regular access reviews, and limiting contractors to only necessary resources. Implementing controls like automatic account deactivation and Multi-Factor Authentication (MFA) is essential to reduce the risk of unauthorized access and protect critical systems.
