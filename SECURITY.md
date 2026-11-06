# Security Policy

## Supported Versions
The `master` branch is currently receiving security updates to ensure safe containerized execution and secure client-server network handling.

## Reporting a Vulnerability
As the primary security maintainer for this project, I take vulnerabilities seriously. This includes:
* Arbitrary code execution risks within the Docker container.
* Exposed environment variables or unsafe volume mapping.
* Packet spoofing or client-injection vulnerabilities related to the game client connection.

Please report exploits or security vulnerabilities through GitHub's private vulnerability reporting on this repository (Security tab → Report a vulnerability). If that option is unavailable, open a pull request or leave a comment on this repository and I will follow up there. Do not post exploit details in a public issue, to prevent zero-day abuse.
