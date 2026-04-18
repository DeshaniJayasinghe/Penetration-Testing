<h1 align="center">Penetration Testing Demonstration</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Course-CTEC%2021052-red" alt="Course Code">
  <img src="https://img.shields.io/badge/Semester-2nd%20Year%201st%20Sem-blue" alt="Semester">
  <img src="https://img.shields.io/badge/Vulnerability-BlueKeep%20(CVE--2019--0708)-yellow" alt="Vulnerability">
</p>

<hr>

<h3>📝 Project Overview</h3>
<p>
  This project is an <b>Individual Assignment</b> for the <b>CTEC 21052: Introduction to Cyber Security</b> course. 
  It illustrates the key phases of a penetration test conducted in a controlled virtual environment, simulating a real-world cyberattack to identify and exploit system vulnerabilities.
</p>

<h3>🛠️ Tools & Environment</h3>
<table>
  <tr>
    <th>Category</th>
    <th>Tool / OS Used</th>
  </tr>
  <tr>
    <td><b>Attacker System</b></td>
    <td>Kali Linux (Penetration Testing OS)</td>
  </tr>
  <tr>
    <td><b>Target System</b></td>
    <td>Windows 7 (IP: 10.0.2.6)</td>
  </tr>
  <tr>
    <td><b>Exploitation Framework</b></td>
    <td>Metasploit Framework</td>
  </tr>
  <tr>
    <td><b>Scanning & Recon</b></td>
    <td>Nmap, Ping</td>
  </tr>
</table>

<h3>🔍 Penetration Testing Phases</h3>
<ol>
  <li><b>Reconnaissance:</b> Active scanning using <code>nmap</code> and connectivity checks via <code>ping</code>.</li>
  <li><b>Vulnerability Assessment:</b> Identification of the <b>BlueKeep (CVE-2019-0708)</b> vulnerability in Remote Desktop Services (RDS).</li>
  <li><b>Exploitation:</b> Using the Metasploit <code>exploit/windows/rdp/cve_2019_0708_bluekeep_rce</code> module to gain unauthorized access.</li>
  <li><b>Post-Exploitation:</b> 
    <ul>
      <li><code>sysinfo</code>: Gathering system details.</li>
      <li><code>screenshare</code>: Live streaming the target's desktop.</li>
      <li><code>getuid</code>: Identifying active user privileges.</li>
    </ul>
  </li>
</ol>

<h3>📂 Project Resources</h3>
<p>You can access the full presentation slides and the assessment guidelines below:</p>

<div align="left">
  <a href="./Penetration%20Testing.pdf">
    <img src="https://img.shields.io/badge/Presentation-Download%20PDF-red?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" alt="Download Presentation">
  </a>
  <a href="./Assessment-Pentest%20(2).pdf">
    <img src="https://img.shields.io/badge/Guidelines-Download%20PDF-blue?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" alt="Download Guidelines">
  </a>
</div>

<br>
<blockquote style="background-color: #fff4f4; border-left: 5px solid #ff0000; padding: 10px;">
  <b>⚠️ Ethical Disclaimer:</b> This demonstration was performed for educational purposes in a strictly controlled virtual environment. Unauthorized access to computer systems is illegal and unethical.
</blockquote>
