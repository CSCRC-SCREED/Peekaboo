# Peekaboo

**Title:** Defeating Evasive Malware with Peekaboo: Extracting Authentic Malware Behavior with Dynamic Binary Instrumentation

**Author(s):** Gaber, M., Ahmed, M., & Janicke, H.

**Description:** Cyber-attacks continue to evolve, increasing in frequency and sophistication where Artificial Intelligence (AI) is becoming essential in detecting modern malware. However, the accuracy of AI in malware detection is dependent on the quality of the features it is trained with. Static and dynamic analysis of malware is limited by the widespread use of obfuscation and anti-analysis techniques employed by malware authors, where if an analysis environment is detected the malware will hide its malicious behavior. However, Dynamic Binary Instrumentation (DBI) allows deep and precise control of the malware sample, thereby facilitating the extraction of authentic features from sophisticated and evasive malware. We developed Peekaboo, a DBI tool to defeat the anti-analysis techniques and extract authentic behavior from live malware samples. We collected 18,527 malware samples across ransomware, spyware, trojans, botnets, worms, Advanced Persistent Threats (APT) and post exploitation tools where every sample includes type, family, and variant information, for example Ransomware-WannaCry-SHA256. We also collected 1,973 benign software samples for analysis.This dataset contains the results for each sample, that were run for up to 15 minutes, to observe not only the anti-analysis techniques used but also its complete behavior. For each malware sample, the network traffic, every opcode that is executed and every evasive technique that is used are captured.

**Testbed Design:** 

![image](https://github.com/CSCRC-SCREED/Peekaboo/assets/19281294/82b4e2ef-a331-41ec-ad49-054101dba4fc)

**Paper URL:** https://doi.org/10.21203/rs.3.rs-4279929/v1
