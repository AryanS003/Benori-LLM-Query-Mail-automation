# Benori-LLM-Query-Mail-automation
Built an 
1) Automated Mailing system.
2) LLM trained on information available at Benori's official website.

![image](https://github.com/user-attachments/assets/cfe35f5d-e99f-4eb3-ac38-3235829fff13)

Features:
**RAG Pipeline:** Uses all-MiniLM-L6-v2 embeddings and FAISS to retrieve the top three relevant Q&A pairs for each query.

**Prompt Engineering using Gemini API**: Leverages Google Gemini (gemini-1.5-flash) to synthesize the best answer from retrieved context, showcasing prompt engineering.

**Email Automation**: Sends query-response emails via smtplib with a modular email handler, supporting automation.

**Data Handling**: Supports text (benori_data.txt), handling data with headlines.
