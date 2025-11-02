# StaticAI
Analyze malware PE using Capstone and Gemini AI

I have been testing for a while the current capabilities of using AI for malware analysis.

I had in mind the following plan, test one if each method:

- using directly a reverse engeering model from Chatgbt
- using a python script that uses capstone to do a disassembly of a binary and then feed the results to Gemini API  
- doing an asm extract from IDA and then feed it to AI

I will get a malware sample from malware bazzar and then test each method and compare with official reports. 
The goal is to see if the AI report is getting close to the official analysis report done by humans. 
for example, extract any possible C2 IP  