# AWS Lambda Website with API Gateway

This project demonstrates hosting a **serverless website** using **AWS Lambda** and **Amazon API Gateway**. The Lambda function returns an HTML page with styled content, welcoming users to the site. The website is fully serverless, scalable, and requires no traditional web server.

---

## 🚀 Architecture

Browser → API Gateway → AWS Lambda → Returns HTML/CSS

markdown
Copy code

- **AWS Lambda** → Runs Python code and returns the styled HTML page.  
- **API Gateway** → Exposes the Lambda function as an HTTP endpoint.  
- **Browser** → Renders the HTML as a user-friendly website.  

---

## 📂 Files

- `lambda_function.py` → Lambda code returning styled HTML page.  
- `README.md` → Project documentation.  

---

## ▶️ Steps to Run

1. Create a Lambda function in AWS with **Python runtime**.  
2. Paste the code from `lambda_function.py`.  
3. Create an **API Gateway REST API** and link it to Lambda.  
4. Enable **Lambda Proxy Integration**.  
5. Deploy the API and copy the endpoint.  
6. Open the endpoint in your browser → You’ll see a styled website with:
   <img width="1916" height="958" alt="Screenshot 2025-09-08 000013" src="https://github.com/user-attachments/assets/9c68b001-267b-4cba-a199-fed4a34119f5" />

----
## 👩‍💻 Author

**Prajakta Pandaram**
