# Modern Threat Intelligence in Action: NHS Case Study

This repository presents a practical, hands-on guide to modern threat intelligence, using the UK National Health Service (NHS) as a real-world case study. It is designed for cybersecurity professionals, students, and defenders who want to understand how attackers operate—and how to defend against them—using open-source intelligence (OSINT), technical reconnaissance, and analysis of recent incidents.

**Key features:**

*   Step-by-step methodologies for threat intelligence collection, enrichment, and analysis
*   Real-world examples of attacker tactics, mapped to the MITRE ATT\&CK framework
*   Practical demonstrations of tools like Shodan, theHarvester, Hunter.io, VirusTotal, and crt.sh
*   Screenshots and evidence from actual reconnaissance activities
*   Case study of the 2024 Synnovis ransomware attack and its impact on NHS operations
*   Actionable mitigation strategies for healthcare and other critical sectors

While the NHS is the focal example, the strategies, risks, and recommendations are universally applicable to any organization seeking to strengthen its cyber resilience against ransomware and advanced threats.

📑 Content


Intro
    
      🎯 Purpose of the Report
      Key Findings
    

  Introduction to Threat Intelligence
   
       Definition and Key Concepts
       Importance for Organizations
       High-Level Summary
    


  Threat Intelligence Lifecycle
    
       Overview of the Lifecycle
       3.1 Collection
       3.2 Enrichment & Processing
       3.3 Analysis
       3.4 Dissemination
      📊 Threat Intelligence Lifecycle Summary Table
    
  

  Threat Intelligence Sources and Tools
    
      🔎 Major Cyber Threat Intelligence Sources
      🛠️ Practical Tools for Threat Intelligence
      🤝 Advisory and Professional Groups
      📊 Threat Intelligence Sources and Tools Summary Table
    

  Google Dorking: Concepts and Applications
    
      🔍 Introduction to Google Dorking
      ⚠️ Why Google Dorking Matters for Cybersecurity
       Legal & Safety Rules
       Core Google Dorking Operators (Cheat Sheet)
    
  

  Practical Google Dorking for NHS Reconnaissance
    
      🔐 Searching for Exposed Credentials
      📂 Searching for Backup Folders
      🔑 Searching for Login or Admin Pages
      📝 Searching for Exposed Log File
      ⚙️ Searching for Sensitive Configuration Files
      ❗ Searching for Error Messages
      🔗 Searching for Exposed APIs
      📄 Searching for Public Documents
      📧 Searching for Staff Emails & Pages
      🌐 Searching for Subdomains
      🧪 Searching for Dev/Test Endpoints
      💻 Searching for Leaked Code on GitHub
      ☁️ Searching for Exposed Cloud Storage
      🔓 Searching for Leaked Credentials (Pastebin)
      🗄️ Searching for SQL Database Dumps
      📉 Searching for Expired Certificates
      📑 Searching for PDF Metadata
      🔎 Searching for Third-Party Mentions
      📊 Analytical Simulation: Google Dorking Findings on NHS.uk
    
  

  Passive Reconnaissance with theHarvester
  
      🎯 Purpose and Methodology
      ⚙️ Setup and Execution Steps
      📊 Interpreting Results: Emails, Hosts, IPs, URLs, People
      📂 Evidence Workflow and Folder Structure
      🧨 Example Attack Kill Chain
      🔗 Next Steps: Enrichment with Other Tools
    


  Email Exposure and Breach Analysis
    
      📧 Using HaveIBeenPwned for Breach Verification
      🛡️ Security Recommendations for Breached Accounts
    
 
   Staff Email Enumeration and Role Mapping
   
      📧 Using Hunter.io for Staff Info
      🔗 Cross-Validation with LinkedIn and Other Tools
      🛡️ Mitigation Strategies
    


  Infrastructure and Service Exposure Analysis
    
     🌐 Investigating IPs on Shodan.io
     ⚠️ Technical Findings and Risks
     ✅ Recommendations for Service Hardening
  

 Certificate Transparency and Subdomain Mapping

      📜 Using crt.sh for Certificate Analysis
      ⚠️ Risks of Legacy and Forgotten Systems
      🧭 MITRE ATT&CK Mapping

  Indicators of Compromise (IOCs) and Malware Analysis
  
      📂 Understanding IOCs
      🧪 Finding Samples on MalwareBazaar
      🧬 Analyzing Samples on VirusTotal
      🧭 MITRE ATT&CK Techniques Observed
 

  Case Study: Qilin Ransomware Attack on Synnovis/NHS
    
      📖 Overview of Qilin (Agenda)
      🕒 Timeline of the Synnovis Incident
      🔍 Attack Preparation and Reconnaissance
      🚪 Initial Access and Exploitation
      📤 Data Exfiltration and Impact
      🛡️ Mitigation and Security Recommendations
      ⚠️ Vulnerabilities and Contributing Factors
      💻 Ransomware-as-a-Service Model
      🏥 Why Synnovis/NHS Was Targeted
      🧭 Attack Sequence and MITRE Mapping
      💔 Impact on Patient Care and Operations
      🔄 Recovery and Lessons Learned
 

  Post-Incident Analysis and Recommendations
    
      ⚠️ Vulnerabilities Identified
      ✅ Preventive Measures Going Forward
      🔗 Supply Chain and Third-Party Risk Management
      🏢 Organizational and Cultural Measures
    


  Conclusion
  
  
