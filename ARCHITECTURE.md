# Architecture Diagram

```mermaid
flowchart TD

A[Visitor] --> B[Website Frontend]

B --> C[Homepage]
B --> D[Services]
B --> E[About]
B --> F[Contact]

F --> G[Inquiry Form]

G --> H[PHP Backend]

H --> I[MySQL Database]

J[WordPress CMS] --> H

H --> K[Service Content]
H --> L[Client Inquiries]
H --> M[Business Information]

B --> N[Responsive Design]
B --> O[SEO Optimization]

```
