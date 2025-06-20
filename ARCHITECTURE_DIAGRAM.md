graph TD
    A[Client (Web/App)]
    B[API Gateway / Backend]
    C[Service Layer<br/>(Microservices)]
    D1[AI/ML Engine]
    D2[Data Layer]
    D3[3rd Party Integrations]
    E1[Relational DB<br/>(PostgreSQL/MySQL)]
    E2[NoSQL DB<br/>(MongoDB)]
    E3[Cache (Redis)]
    E4[File Storage<br/>(S3/Azure Blob)]
    F1[Travel APIs<br/>(Amadeus, Skyscanner, etc.)]
    F2[Maps/Directions<br/>(Google Maps, Mapbox)]
    F3[Payment Gateways<br/>(Stripe, PayPal)]
    G[Cloud Hosting<br/>(AWS/Azure/GCP)]
    H[Containerization<br/>(Docker)]
    I[Orchestration<br/>(Kubernetes)]
    J[Monitoring<br/>(Prometheus, Grafana)]

    A --> B
    B --> C
    C --> D1
    C --> D2
    C --> D3
    D2 --> E1
    D2 --> E2
    D2 --> E3
    D2 --> E4
    D3 --> F1
    D3 --> F2
    D3 --> F3
    C --> G
    C --> H
    C --> I
    C --> J
