# Nessus
## Conquering Vulnerabilities: A Beginner's Guide to Nessus Vulnerability Scanner on Windows

In today's interconnected world, cybersecurity is the cornerstone of resilience. Our digital domains, despite their protective measures like firewalls and encryption, can harbor hidden weaknesses – vulnerabilities that act as potential entry points for attackers. These vulnerabilities reside within our systems, applications, and even network devices, posing risks of data breaches, operational disruptions, and significant harm.

<b>Nessus emerges as a vigilant sentinel, ready to safeguard your digital realm.</b> It meticulously probes your systems for known vulnerabilities, serving as an early warning system against potential threats.

<b>Why Nessus stands out:</b>

<b>Comprehensive Detection:</b> Its vast library of plugins ensures thorough scanning, leaving no vulnerability unexposed.

<b>User-Friendly Navigation:</b> Even those without extensive cybersecurity expertise can easily navigate its intuitive interface and guided workflows.

<b>Adaptable to Diverse Needs:</b> From basic scans to in-depth audits, Nessus offers a range of options to suit specific security requirements.

<b>Actionable Intelligence:</b> It not only identifies vulnerabilities but also provides severity ratings, exploit information, and recommended remediation steps, empowering you to take swift and informed action.

With Nessus as your ally, you can transition from a reactive stance to a proactive approach, fortifying your digital defenses. Embark on this journey to discover the power of Nessus and enhance your cybersecurity posture

![1](https://github.com/Jaswanthbommi/Nessus/assets/62924828/14bb92a3-0500-4ba3-8a3b-3623c1550204)

## 1. Installation & Activation:
<b>Download the Nessus Essentials for Windows installer:</b> 

Head over to https://www.tenable.com/downloads/nessus and choose the appropriate download for your Windows 10 architecture (32-bit or 64-bit).

<b>Run the installer:</b> 

Follow the on-screen instructions, accepting the license agreement and choosing an installation directory.

![2](https://github.com/Jaswanthbommi/Nessus/assets/62924828/ae09e530-705d-47d3-ae4b-268cb62f111b)

## 2. Getting Familiar with the Interface:

<b>Dashboard:</b> This is your central hub, displaying scan summaries, vulnerability insights, and overall security posture.

<b>Policies:</b> Here, you configure scan settings like target systems, scan types, and plugin selections.

<b>Scans:</b> This section houses all your scan schedules and results, allowing you to track progress and analyze findings.

<b>Reports:</b> Generate comprehensive reports on vulnerabilities identified, prioritizing remediation efforts.

![3](https://github.com/Jaswanthbommi/Nessus/assets/62924828/6831fae2-1630-4304-aade-985e2c672116)

## 3. Building the Virtual Target:

<b>Obtaining the Windows 10 Image:</b> I downloaded a legitimate Windows 10 ISO file from Microsoft's website, providing the building blocks for my virtual machine.

<b>Setting Up the VM:</b> Using VMWare Player, I configured a new virtual machine and loaded the Windows 10 ISO. I configured the network adapter to be bridged, ensuring it communicated with my actual network for accurate scanning.

![4](https://github.com/Jaswanthbommi/Nessus/assets/62924828/7b0822b0-fe92-4f92-ba8b-66427fe775c7)

<b>Verifying Connectivity:</b> To confirm accessibility, I pinged the virtual machine from outside its environment, validating its presence on the network.

<b>Disabling the Firewall (Within the VM): To ensure scan completion in this controlled testing environment, I temporarily disabled the firewall within the Windows 10 VM.</b> Caution: In real-world scenarios, disabling firewalls is strongly discouraged as it significantly increases security risks. Instead, configure firewall rules to allow necessary traffic for scanning.''

![5](https://github.com/Jaswanthbommi/Nessus/assets/62924828/26e52c89-78e0-4dba-bcc6-f76566761234)


## 4. Configuring your First Scan:

Click <b>"Policies"</b> and then <b>"New Policy."</b>

<b>Name your policy:</b> Choose a descriptive name like "Windows 10 Single Host."

<b>Select targets:</b> Enter IP addresses, hostnames, or network ranges to scan. You can also import target lists from files.

<b>Choose a scan type:</b> Nessus offers various scan types, including Basic Network Scan, Discovery Scan, and Credentialed Scan. Start with a Basic Network Scan for a non-intrusive overview.

<b>Plugin selection:</b> Nessus has a vast library of vulnerability detection plugins. For beginners, keep it simple by selecting the "Basic Security Checks" plugin family.

<b>Review and Save:</b> Double-check your settings and save the policy.

![6](https://github.com/Jaswanthbommi/Nessus/assets/62924828/b0927e08-7053-4295-beb8-8a811050216a)

## 5. Launching the Scan:

<b>Navigate to "My Scans"</b> and click on the Windows 10 Single Host. 

<b>Now Click on the Run Button.</b>

<b>Hit "Launch Scan"</b> and sit back as Nessus gets to work!

![7](https://github.com/Jaswanthbommi/Nessus/assets/62924828/78b485d7-14d0-4847-8f96-b693d972c724)

## 6. Analyzing Scan Results:

<b>Monitor the scan progress:</b> The "Scans" section will show the scan's status and estimated completion time.

<b>Delve into the findings:</b> Once complete, click on the scan name to explore the results.

<b>Vulnerability details:</b> Each identified vulnerability will have a severity rating, exploit information, and recommended remediation steps.

<b>Prioritize and remediate:</b> Focus on high-severity vulnerabilities first and follow the provided guidance to patch or mitigate them.

![8](https://github.com/Jaswanthbommi/Nessus/assets/62924828/f3e026dd-9108-43a7-96e8-efee9af05c43)

<b>The panel of vulnerabilities after remediation on Windows 10 system:</b>

<img width="744" alt="9" src="https://github.com/Jaswanthbommi/Nessus/assets/62924828/1e764a19-6dfa-4f5e-840d-4229d4877330">


## Key Takeaways:

<b>Legacy software poses a significant risk:</b> Outdated software often harbors critical vulnerabilities, highlighting the importance of diligent patch management and prioritizing the removal of legacy applications whenever possible.

<b>Vulnerability scanning and patching are vital:</b> Regular scans, particularly with credentialed access, provide a comprehensive picture of potential weaknesses. Proactive patching helps mitigate these vulnerabilities, but striking a balance with workflow disruptions and ensuring patch safety is crucial.

<b>Happy Scanning!</b>
























