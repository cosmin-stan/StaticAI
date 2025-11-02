# StaticAI
Analyze malware PE using Capstone and Gemini AI

I have been testing for a while the current capabilities of using AI for malware analysis.

I had in mind the following plan:

- using directly a reverse engeering model from Chatgbt
- using a python script that uses capstone to do a disassembly of a binary and then feed the results to Gemini API  
- doing an asm extract from IDA and then feed it to AI