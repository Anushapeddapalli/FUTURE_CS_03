# FUTURE_CS_03
# API Security Risk Analysis – Task 3 

##  Overview

This project is a read-only API Security Risk Analysis performed on a public test API. The aim of this task is to understand how APIs work, analyze their security posture, and identify common security risks such as open access, excessive data exposure, and missing protective controls.

## 🎯 Objective

- Analyze a public test API  
- Test API endpoints and inspect responses  
- Check authentication and access control behavior  
- Identify common API security risks  
- Explain the risks in simple terms  
- Suggest basic remediation steps  

## 🔍 Target API

- **JSONPlaceholder** (Public Test API)  
  https://jsonplaceholder.typicode.com  

## 🛠️ Tools Used

- **Postman** – To send API requests and inspect responses  
- **Insomnia** – To test endpoints and view headers and data  

## 📊 Key Findings 

- API endpoints are accessible without authentication  
- User data is openly returned (excessive data exposure)  
- No visible rate-limiting or access control headers were found  
- Error handling is basic and does not restrict invalid requests  

## 📁 Repository Structure

- `report.pdf` / `report.docx` – Full security analysis report  
- `screenshots/` – Evidence of API requests and responses  
- `README.md` – Project overview and details  
This analysis was performed only on a public test API for learning purposes. No real systems were targeted, and no harmful actions were performed.
