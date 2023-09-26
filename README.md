<p align="center">
<img src="https://i.imgur.com/Ua7udoS.png" alt="Traffic Examination"/>
</p>

<h1>Network Security Groups (NSGs) and Inspecting Traffic Between Azure Virtual Machines</h1>
In this tutorial, we observe various network traffic to and from Azure Virtual Machines with Wireshark as well as experiment with Network Security Groups. <br />


<h2>Video Demonstration</h2>

- ### [YouTube: Azure Virtual Machines, Wireshark, and Network Security Groups](https://www.youtube.com)

<h2>Environments and Technologies Used</h2>

- Microsoft Azure (Virtual Machines/Compute)
- Remote Desktop
- Various Command-Line Tools
- Various Network Protocols (SSH, RDH, DNS, HTTP/S, ICMP)
- Wireshark (Protocol Analyzer)

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)
- Ubuntu Server 20.04

<h2>High-Level Steps</h2>

-Identify the Use Case:

-Determine the specific use case or communication scenario for which you need a high-level protocol. Understand the data exchange requirements, security needs, and other relevant factors.
Select the Appropriate Protocol:

-Choose a high-level protocol that aligns with the use case. Different protocols are designed for various purposes, such as HTTP for web communication, SMTP for email, or FTP for file transfer.
Understand the Protocol's Purpose:

-Familiarize yourself with the primary purpose of the selected protocol. Determine if it is designed for data retrieval, data submission, remote access, or other specific functions.
Learn the Protocol's Structure:

-Study the protocol's structure, including message format, headers, and data fields. Understand how data is organized and transmitted within the protocol.
-Security Considerations:

-Assess the security features and considerations of the protocol. Determine if it provides encryption, authentication, and authorization mechanisms to protect data during transmission.
-Data Encoding and Formatting:

-Understand how data is encoded and formatted within the protocol. Some protocols use standard data formats like JSON or XML, while others have their own custom formats.
-Session Management (if applicable):

If the protocol involves session management (e.g., in a client-server interaction), learn how sessions are established, maintained, and terminated.
-Error Handling:

-Explore how the protocol handles errors and exceptions. Understand the error codes or responses used for diagnosing and resolving issues.
-Implementation or Integration:

-Implement or integrate the protocol into your application or system. Ensure that your software can send and receive data following the protocol's specifications.
-Testing and Validation:

-Test the protocol implementation thoroughly to verify that it functions correctly in various scenarios. Conduct both positive and negative tests to cover different use cases.
-Documentation:

-Create comprehensive documentation for the use of the protocol within your application or system. Include details about how to use it, any specific requirements, and troubleshooting guidance.
-Security Configuration (if applicable):

-Configure security settings such as certificates, keys, and access controls to ensure secure communication when using the protocol.
-Performance Optimization:

-Optimize the protocol's usage for performance by minimizing unnecessary data transfers, reducing latency, and implementing caching mechanisms as needed.
-Monitoring and Logging:

-Set up monitoring and logging for protocol-related events and data exchanges. This helps in diagnosing issues and tracking system behavior.
-Compliance and Standards:

-Ensure that the protocol implementation complies with relevant industry standards and best practices. This may involve conforming to RFCs (Request for Comments) or other specifications.
-Continuous Maintenance:

-Regularly review and update the protocol implementation to address any security vulnerabilities, compatibility issues, or performance bottlenecks.
-Scalability Considerations:

-If your application or system needs to handle increasing loads, evaluate the protocol's scalability and consider architectural adjustments as necessary.
-User Training (if applicable):

-If end-users interact with the protocol directly, provide training and documentation to ensure they understand how to use it effectively.
<h2>Actions and Observations</h2>

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />

<p>
<img src="https://i.imgur.com/DJmEXEB.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</p>
<p>
Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
</p>
<br />
