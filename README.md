 AI-Resume-Screening-Automation-with-n8n
Automates resume screening by extracting PDFs from Gmail, analyzing them with AI, and sending instant accept/reject emails. Reduces manual effort, speeds up hiring, and ensures every candidate gets a timely response.
🔧 Workflow Overview
1. Gmail Trigger  
   Automatically detects incoming emails containing resumes.

2. Get Message 
   Fetches the full email content and attachments.

3. Extract from PDF 
   Parses and extracts text from resume files (PDF format).

4. AI Screening (OpenAI / LLM) 
   Analyzes the resume based on predefined criteria (skills, experience, relevance).

5. Conditional Logic (IF Node) 
   Determines whether the candidate is a good fit.

6. Automated Email Response
   - Sends acceptance/next-step email for qualified candidates  
   -  Sends rejection email for unqualified candidates  
Features
- Fully automated resume screening
- AI-powered candidate evaluation
- Real-time email processing
- Customizable screening criteria
- Reduces manual HR workload significantly

 Use Cases
- HR teams screening high volumes of applications
- Startups automating early hiring stages
- Recruitment agencies improving response time

 Tech Stack
- [n8n](http://localhost:5678/workflow/LgDpMvOcykIZBFXh)Workflow automation
- Gmail API – Email trigger & response
- OpenAI / LLM – Resume analysis
- PDF Parser – Text extraction
