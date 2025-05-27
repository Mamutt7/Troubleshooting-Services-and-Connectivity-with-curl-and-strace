# Troubleshooting-Services-and-Connectivity-with-curl-and-strace

Scenario:
A customer reports that a web application on their RHEL server isn’t reachable. Your job is to use basic Linux troubleshooting skills and diagnostic tools to investigate the issue—just like a Red Hat Support Engineer would!

Task 1: Install and Start a Simple Web Server (httpd)
Description:
You’ll set up a simple Apache web server so you can test connectivity and diagnose issues.
![image](https://github.com/user-attachments/assets/7808e192-8606-44b7-8b9e-31e5d7c6b55c)
![image](https://github.com/user-attachments/assets/7439e820-5ba0-41e3-95c7-6fecca2c0655)
![image](https://github.com/user-attachments/assets/ae276394-639d-46c9-8d4a-44fb16313cd2)

Task 2: Check Firewall Rules and Open HTTP Port (80)
![image](https://github.com/user-attachments/assets/e3e66d2f-3504-48c8-8e9b-137c8a4440ae)
![image](https://github.com/user-attachments/assets/71da0949-9133-4a0e-a74f-6417cc4b503b)

Task 3: Test Local Connectivity with curl
![image](https://github.com/user-attachments/assets/a321ee8e-fe5d-4f70-a18a-63a285a2c365)
![image](https://github.com/user-attachments/assets/5fe5089c-3716-4c96-a526-6b37ab323b26)

Task 4: Troubleshoot with strace
Description:
Let’s simulate a simple investigation using `strace` to see what happens behind the scenes when you run `curl`.

![image](https://github.com/user-attachments/assets/d8a08e74-41f6-444c-8f4b-b0100bd6c29d)
![image](https://github.com/user-attachments/assets/296b2af4-e828-4691-bbba-91410dafbade)

Task 5: Stop the Web Server and Simulate a Service Outage
![image](https://github.com/user-attachments/assets/682ed0f7-70d6-423a-ad46-3dda831f898e)

Task 6: Start the Web Server Again and Clean Up
![image](https://github.com/user-attachments/assets/1054975f-1b85-491c-88b0-d4626129e5ff)

Key Takeaways
- Installed and managed a basic web server with systemctl.
- Configured firewall rules with firewall-cmd.
- Used curl to test connectivity (core diagnostic skill!).
- Got a glimpse of how strace reveals what’s happening under the hood.
- Simulated a real-world outage and resolved it.

