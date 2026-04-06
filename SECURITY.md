# Security Matrix
| Component | Protocol | Port | Source | Justification |
| :--- | :--- | :--- | :--- | :--- |
| Web Server | TCP | 80 | 0.0.0.0/0 | Public HTTP access |
| App Server | TCP | 443 | 0.0.0.0/0 | Secure HTTPS traffic |
| SSH | TCP | 22 | My-IP-Only | Admin maintenance |
| Database | TCP | 3306 | Web-SG-Only | Internal DB access only |
