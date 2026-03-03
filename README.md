# Xây dựng ứng dụng tư vấn pháp luật sử dụng AI

Tất cả các microservices: Ghi lại thông tin request (request logs)

Tất cả các microservices: có request_id, code, success, message, data, total

# Tổng quan các microservices

```mermaid
graph TD
    ClientApp[Client App - Web/Mobile] --> API_Gateway[API Gateway]

    API_Gateway --> IAM[IAM Service]
    API_Gateway --> UserDirectory[User Profile Service]
    API_Gateway --> Consultation[Consultation Service]
    API_Gateway --> Communication[Real-time Comm Service]
    API_Gateway --> Docs[Document Service]
    API_Gateway --> Billing[Billing Service]

    Consultation --> AI_Engine[AI & NLP Engine Service]
    Docs --> AI_Engine

    AI_Engine --> LLMs[(LLM APIs - e.g., Gemini)]
    AI_Engine --> VectorDB[(Vector DB)]
```

# Chi tiết các microservices
