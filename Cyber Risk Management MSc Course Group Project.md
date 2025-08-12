<h1>Cyber Risk Management</h1> 

Incident Management & Implementation of GRC frameworks for Streamline Studios Infrastructure
This is a reflection on a team project I participated in during my MSc Cyber Security studies. The assignment was part of the "Cyber Risk Management" module, where we analysed cyber security incidents faced by a fictional organization (Streamline Studios), assessed its GRC framework, and developed improved solutions for better data governance.

The team collaborated weekly on the assignment deliverables both in person and virtually via Microsoft Teams. Each week, we presented our findings in person, with each member presenting their respective parts. In addition to group assessment, we were individually assessed based on our contributions posted on the online forum of our learning portal
Introduction Data Breach & Mitigations

Streamline Studios, headquartered in Austin, Texas, operates internationally in London, UK; Mumbai, India; and Sao Paulo, Brazil. Initially, we analysed a data breach at the firm’s Sao Paulo branch, caused by weak encryption standards and a poorly maintained ISMS (Information Security Management System), leading to unauthorized disclosure of user data. In our analysis, we identified the firm’s failure to comply with ISO/IEC27001, GDPR, and the Brazilian data protection act. We highlighted infrastructure flaws, financial impacts, corrective measures, and proposed solutions to mitigate future breaches.

We then examined the breach's causes, noting that Streamline Studios struggled with GDPR compliance, especially in the UK following Brexit. This led to the creation of frameworks for improved data governance and compliance, aligning with ISO/IEC27001, GDPR, and COBIT 5. I proposed solutions included implementing strong information security policies, appointing a Data Protection Officer (DPO), conducting risk assessments, performing regular audits for ISO27001, GDPR, and PCI-DSS compliance, ensuring an effective ISMS, and using strong encryption for data both in transit and at rest.

In analysing the firm's inadequate GDPR compliance, I supported the team in identifying failures such as not conducting a Data Protection Impact Assessment (DPIA) for current and future data processing, which could have highlighted operational weaknesses. The firm also failed to implement data retention policies ensuring the privacy of sensitive data, including data classification, retention periods, review, and disposal procedures. I proposed solutions for GDPR compliance included appointing a data governance committee (e.g., IT, Legal, and Compliance representatives), assigning roles like data custodians, data owners, and data stewards, and documenting evidence of best practices such as records of stored data, consent, and data processing methods.

COBIT 5 proposals included identifying the needs of internal and external stakeholders to improve IT governance, implementing technical controls like automated data retention tools, creating a single integrated framework incorporating PRINCE2 for project management, applying ITIL for IT service management, and using RISK IT (from ISACA) for risk management and regular review of data retention strategies.
In addition to the data breach and GDPR non-compliance in some European branches, Streamline Studios faced other threats, including a phishing attack and poor encryption standards in certain branches, leading to a man-in-the-middle (MITM) attack.

<h1>Phishing Attack & Mitigations</h1>
Streamline Studios experienced a phishing attack due to the lack of access control policies for its internal systems. We assessed the causes of the attack and proposed solutions based on the NIST Cybersecurity Framework (CSF) to strengthen preventative measures and improve security awareness. We recommended providing regular security awareness training for employees and implementing phishing detection technologies, such as web scanners (Google Safe Browsing, VirusTotal) and spam filters like DMARC.

I assessed the firm's needs against the NIST CSF to prevent future threats, analysing the functions of Identify, Protect, Detect, Respond, and Recover. I focused on the Protect and Detect functions for phishing mitigation, recommending the implementation of multifactor authentication (MFA). The Protect function emphasizes that MFA strengthens access control, adding a critical layer to prevent unauthorized access. The Detect function, through MFA, provides monitoring and logging capabilities to identify suspicious login attempts linked to phishing. The Respond function also ensures that MFA limits unauthorized access, reducing the impact of a data breach by restricting the ability of criminals to exploit compromised credentials.

<h1>MITM Attack & Mitigations</h1>

Streamline Studios faced a MITM attack due to poor encryption standards in its data centres in India. We were tasked with recommending best practices for encryption based on ISO/IEC27001 and NIST CSF. The inadequate encryption implemented for its data centres, led to data exposure, both in transit and at rest, with cybercriminals exfiltrating data. This resulted in a loss of customer confidentiality and trust, as the firm failed to properly manage users' digital rights under GDPR.

<h1>ISO/IEC27001</h1>

I supported the team in proposing ISO/IEC27001 best practices, including using strong cryptographic algorithms for encrypting data in transit and at rest, as outlined in Annex 8.24. We recommended conducting risk assessments to determine confidentiality, integrity, and non-repudiation for appropriate cryptographic solutions. Additionally, we advised regular security audits on information transfer under the information exchange policy, checking for weak encryption as per Annex 5.14, and communicating the policy to employees with security awareness training. We also recommended using digital signatures in electronic communications to mitigate MITM attacks.

<h1>NIST CSF</h1>
The NIST CSF best practices included applying the "Protect" function, implementing safeguards such as data encryption to mitigate MITM attacks. This covered techniques like Simplified Security Controls, which apply strong encryption standards to credentials in databases, and deploying secure web-based vulnerability disclosure portals using encryption protocols. We also advised using Advanced Encryption Standards (AES) and the principle of least privilege for all employees. Furthermore, Streamline Studios was advised to implement Transport Layer Security (TLS), specifically TLS 1.3, for more secure online communications.

<h1>Conclusion</h1>
To conclude, we explored the significance of various standards and frameworks, including ISO/IEC 27001, GDPR, NIST CSF, and COBIT, in providing established best practices to address and mitigate security threats faced by Streamline Studios, such as data breaches, phishing attacks, and man-in-the-middle (MITM) attacks. These frameworks offer structured approaches to enhance data protection, ensure compliance, and strengthen cybersecurity. By adopting the recommended mitigations based on these frameworks, Streamline Studios can improve its security posture, reduce vulnerabilities, and be better equipped to prevent future attacks and breaches, safeguarding both their data and customer trust.




