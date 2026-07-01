# Artificial-Intelligence-Automated-Cybersecurity-Checking-Tool

this project helps to check the risks to LLMs and Ai systems by automating a Threat Modelling & Guardrail System 

for this threat modelling project I am setting a target AI system, mapping possible threats and proposing mitigations for the possible threats. 


1. My target AI system

Human Resource Chatbot an example of this is an AI powered automated system to streamline and automate HR tasks, like answering FAQ’s, Guiding the onboarding process.



2. Mapping Possible Threats

Researching the MITRE ATLAS and the OWASP top 10, gives you a better understanding of how people might exploit ai systems. 


3. Analysing The STRIDE Threat Modelling Methodology 

Stride stands for, Spoofing, Tampering, Repudiation, Information Discloser, Denial Of Service and Elevation of Privilege.  

How something like this could work in practice? 

Model the system, creating a data flow diagram to map out how the data moves, Identify Threats, Apply the STRIDE Framework and brainstorm how attackers might exploit the system. 


4.  Proposed Mitigations in the scenario of an “AI Human Resource Chatbot” 

My proposed mitigations include a multi layered approach to keeping an AI human resources chatbot safe. Sanitisation so filtering out unknown or specific language eg “ignore previous instructions” before they reach the LLM, also implementing guardrails deploying specific tools to block jailbreak attempts in real time. Ensuring the chatbot only access specific tools it needs avoid giving the chatbot unrestricted access to tokens and admin rights. Limit sessions by short lived and scoped API keys. All of these previous ideas can be combined with continuously monitoring and surveillance following on with security best practices.   

