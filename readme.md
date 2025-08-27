# DevOps Board Project

A sample DevOps project integrating modern tools and practices.

## Tech Stack

- **Spring Boot**: Backend REST API
- **Jenkins**: CI/CD automation
- **GitHub**: Source code management
- **SonarQube**: Code quality and static analysis
- **Helm**: Kubernetes package management
- **Prometheus**: Monitoring and alerting

## Workflow Overview

1. **Development**: Code is pushed to GitHub.
2. **CI/CD**: Jenkins builds, tests, and deploys the application.
3. **Code Quality**: SonarQube analyzes code for bugs and vulnerabilities.
4. **Deployment**: Helm charts manage Kubernetes deployments.
5. **Monitoring**: Prometheus collects metrics from the application.

## Getting Started

1. Clone the repository:
    ```bash
    git clone https://github.com/VinayVallabhaneni/devops-board.git
    ```
2. Build and run with Spring Boot:
    ```bash
    ./mvnw spring-boot:run
    ```
3. Set up Jenkins, SonarQube, Helm, and Prometheus as per your infrastructure.

## Contributing

Contributions are welcome! Please open issues or pull requests.
