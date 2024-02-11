# Healthcare Management System

## Introduction
The Healthcare Management System is a microservices-based application designed to streamline various healthcare-related tasks such as patient management, appointment scheduling, medical records management, billing, and reporting. This README provides an overview of the project structure, services, and setup instructions.

## Microservices Architecture
The system consists of the following microservices:

1. **Patient Service**: Manages patient registration, profile management, and medical history tracking.
2. **Doctor Service**: Handles doctor registration, profile management, and schedule management.
3. **Appointment Service**: Manages appointment scheduling with conflict resolution and notification functionalities.
4. **Medical Records Service**: Deals with medical record creation, retrieval, and update functionalities.
5. **Billing Service**: Handles billing generation, invoicing, and payment tracking functionalities.
6. **Reporting Service**: Provides reporting functionalities for generating insights into patient demographics, appointment trends, and revenue analysis.

## Setup Instructions
1. Clone the repository:


## Additional Components
The system also includes the following components:

- **PostgreSQL Database**: Stores data related to patients, doctors, appointments, and medical records.
- **MongoDB Database**: Stores data related to billing and payments.
- **Grafana**: Used for monitoring and visualizing metrics collected by Prometheus.
- **Prometheus**: Collects and stores metrics from the microservices.
- **API Gateway**: Routes requests to the appropriate microservices and handles load balancing.
- **Message Broker (Kafka or RabbitMQ)**: Facilitates communication between microservices and ensures message delivery.

## Documentation
For detailed documentation, including API specifications, database schema, and deployment guides, refer to the `/docs` directory.

