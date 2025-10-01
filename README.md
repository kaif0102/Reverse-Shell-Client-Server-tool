# Reverse-Shell-Client-Server-tool
Reverse Shell (Client &amp; Server) is a minimal educational implementation of a reverse shell in Python.
It demonstrates basic remote command execution, file upload/download over a socket, and JSON + base64 encoding for structured data exchange. The code is intended strictly for learning, red-team lab exercises, and defensive research on systems you own or have explicit written permission to test.

Legal / Ethical Notice (READ FIRST)
This project contains code that can be abused to gain remote control of machines. Do not use it against systems you do not own or do not have explicit written permission to test. Unauthorized use is illegal and unethical. Use this code only in isolated lab environments (VMs on an air-gapped network or with explicit authorization) for education, detection, or defensive testing.

Key features

Two scripts: a client (connects out to the listener) and a server/listener (accepts connection).

Remote command execution with shell output returned to the controller.

Directory navigation (cd), file download (from target to controller), and file upload (from controller to target).

JSON framing for reliable message boundaries.

Base64 encoding for binary-safe file transfer.

Simple reconnect logic for client-side persistence.
