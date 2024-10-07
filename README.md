# Splunk-Defense

## Objective

Theis projects aim was to take on the role of a SOC analyst to design and implement an advanced security monitoring solution for a fictional company, known as Virtual Space Industries (VSI), using Splunk. The project focuses on configuring and analyzing server logs from Windows and Apache environments to detect suspicious activities, enhance incident response, and optimize security posture. By developing custom reports, alerts, and dashboards, the project delivers real-time monitoring capabilities. Simulated attack data is used to assess and fine-tune the system, ensuring comprehensive protection against potential threats.

### Skills Learned

- Log Analysis: Learning to extract and analyze logs from Windows and Apache servers to identify unusual activities.
- Splunk Setup: Configuring Splunk to create reports, dashboards, and alerts for real-time system monitoring.
- Security Monitoring: Building a system to monitor and protect critical infrastructure using automated alerts and dashboards.
- Threat Detection: Identifying and responding to cyberattacks by analyzing attack data and adjusting system settings.
- Data Visualization: Creating charts and dashboards to visualize server activity and detect security threats.
- Report Creation: Generating reports to track important metrics like login attempts and server requests.
- Automation: Setting up automated alerts to quickly detect suspicious activities.
- Tool Enhancement: Using a Splunk add-on to improve threat tracking and system defenses.
- Attack Simulation: Testing the system with simulated attacks to evaluate and improve its effectiveness.
- Presentation Skills: Summarizing findings and making recommendations for security improvements in a clear presentation.

### Tools Used

- Splunk: For monitoring, analyzing logs, and setting up alerts.
- Windows Server Logs: To track server activity like logins and security events.
- Apache Web Server Logs: For analyzing web server traffic and request patterns.

## Steps

This divided into two distinct parts: Part 1 – Defensive Security and Part 2 – Monitoring & Analyzing Attacks. In this role, I act as a Security Operations Center (SOC) analyst for Virtual Space Industries (VSI), a company that specializes in virtual-reality software. VSI suspects that a competitor, JobeCorp, might attempt cyberattacks to disrupt its business. My objective is to first design a monitoring solution using Splunk, and then assess its effectiveness by analyzing simulated attack logs.
 
Part 1: Defensive Security

I focued on designing and configuring a monitoring solution to safeguard VSI’s critical systems, specifically its Windows Server and Apache Web Server. 
Here is a breakdown of the steps I took. 
1.	Loading and Analyzing Logs:
o	I start by uploading VSI’s standard operational logs from both the Windows Server and the Apache Web Server into Splunk. These logs represent regular, expected server activity and serve as a baseline to identify any unusual patterns later on.
2.	Creating Reports, Alerts, and Dashboards:
o	Reports: I design reports that display essential metrics, including activity success and failure rates, as well as severity levels for the Windows Server. On the Apache server side, I generate reports to monitor HTTP request types and identify high-traffic referrer domains.
o	Alerts: I set up automated alerts to detect and respond to suspicious activities in real-time. For instance, on the Windows Server, alerts are triggered for anomalies such as high volumes of failed logins, unexpected successful logins, or any account deletions. For the Apache server, I configure alerts to detect excessive HTTP POST requests or access from countries outside the U.S.
o	Dashboards: I create customized, interactive dashboards for each server. These dashboards include visualizations such as line charts, bar graphs, and heat maps to give VSI an intuitive, real-time overview of server activity. I also include time-range filters to facilitate dynamic analysis over various periods.
3.	Installing a Splunk Add-On:
o	To enhance monitoring capabilities, I install an add-on from Splunkbase that provides additional security features. This add-on allowed me to track specific threat vectors and enhance VSI’s ability to respond proactively to potential threats.
 
Part 2: Monitoring and Analyzing Attacks

I simulated an attack scenario by loading and analyzing newly provided logs that represent attacks targeting VSI’s systems. This phase is dedicated to evaluating how well the monitoring solution can detect and respond to these attacks.
1.	Loading and Analyzing Attack Logs:
o	I loaded the attack logs for both the Windows Server and the Apache Web Server into Splunk and by comparing this data with the baseline, I better understood the nature of the attacks and assessed the effectiveness of the monitoring setup.
2.	Reviewing Reports, Alerts, and Dashboards:
o	Report Analysis: I reviewed the reports created in Part 1 and compared the baseline data with the attack data to identify any unusual changes, such as spikes in failed logins or an increase in certain HTTP methods. This helped me detect patterns that correlated with the attack.
o	Alert Analysis: I tested whether the alerts I configured earlier were triggered by the attack logs, determining if the threshold settings I selected were appropriate.
o	Dashboard Analysis: I updateed the dashboards with the attack data, using visualizations to analyze any abnormalities in signature counts, user activities, and HTTP requests. This helped me identify new attack patterns, such as the unexpected geographic locations or the unusual user agents accessing the servers.

The last thing I did was compile my findings into a presentation that summarized the effectiveness of the monitoring solution and highlighted the suspicious activities that were detected. I also provided recommendations for strengthening VSI’s security posture.

<a href="https://github.com/ThatBrownGuy101/Splunk-Defense/blob/main/Splunk-Defense%20Presentation.pptx">Splunk-Defense Presentation</a> and <a href="https://github.com/ThatBrownGuy101/Splunk-Defense/blob/main/Splunk-Defense%20Questions.pdf">Splunk-Defense Questions</a>
 
Through this project, I developed valuable experience in building and testing a monitoring system, creating custom reports and alerts, and analyzing data to detect cyber threats. These skills are essential in implementing effective defensive security measures and ensuring a quick, informed response to incidents.

