# On Premise Agent Releases
This repository holds the previous and latest releases of the On-Premise Agent for Marval's chatbot. 

The On-Premise Agent is an alternative way for us to provide interoperability between the chat system and Marval, primarily intended for those that don't have an instance of MSM accessible to the internet. 

Rather than directly requesting resources from MSM, the chatbot server maintains a persistent connection with an On-Premise Agent that runs on the IIS Server (or elsewhere on the local network). This means that no firewall rule configuration is required. The system is end-to-end encrypted and uses RSA to verify connection authenticity.
