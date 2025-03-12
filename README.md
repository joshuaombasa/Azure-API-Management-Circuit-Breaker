# Azure-API-Management-Circuit-Breaker


This repository contains an implementation of the Circuit Breaker Pattern in Azure API Management (APIM). The policy is designed to prevent system overload and improve reliability by limiting requests, setting timeouts, and handling failures gracefully.

##  Features
- **Rate Limiting** – Restricts API requests per client to avoid overloading the backend.
- **Retry Policy** – Retries failed requests before returning an error.
- **Timeout Handling** – Ensures slow requests fail quickly.
- **Custom Error Response** – Provides a user-friendly message when the circuit is open.

