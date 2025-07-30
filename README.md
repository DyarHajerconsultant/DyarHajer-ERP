# DyarHajer-ERP

This repository contains a comprehensive ERP system featuring a modern user interface and centralized admin dashboard. The system is modular and designed to manage multiple departments—such as Projects, HR, CRM, Accounting, and more—with seamless integration and intelligent automation.

# 🔧 Features:
Clean, responsive UI for users and admins

Centralized dashboard for department management

Modular architecture with interconnected services

AI-driven automation and smart recommendations

Built with Spring Boot (backend) and Angular (frontend)

Scalable structure designed for engineering consulting firms

                        +--------------------------+
                        |      Web Dashboard       |
                        |  (Admin + Engineers)     |
                        +-----------+--------------+
                                    |
                                    v
                        +-----------+--------------+
                        |   API Gateway (Spring)   |
                        +-----------+--------------+
                                    |
    +-------------------------------+--------------------------------+
    |               |                  |                |             |
    v               v                  v                v             v
+--------+     +------------+     +-----------+   +-----------+  +-------------+
| Agent1 |     |  Agent2    |     |  Agent3   |   |  Agent4   |  |    Agent5   |
| Chat   |     | Scheduler  |     | Manager   |   | Analyst   |  | Recommender |
+--------+     +------------+     +-----------+   +-----------+  +-------------+
    |               |                  |                |             |
    v               v                  v                v             v
+-----------------------------------------------------------------------------+
|                              Data Storage (PostgreSQL + Vector DB)          |
|                        + Logs, Projects, Clients, Team, Reports             |
+-----------------------------------------------------------------------------+

الاسم	الوظيفة
# Agent1 - ChatBot	
# Agent2 - Scheduler	
# Agent3 - Project Manager	
# Agent4 - Data Analyst	
# Agent5 - Recommender	

Spring Boot، REST APIs
Frontend	Angular
AI/NLP	OpenAI API (ChatGPT)، LangChain، spaCy، n8n




