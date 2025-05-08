# Microservices Demo Project

This project demonstrates a microservices architecture with CI/CD implementation using Jenkins, Gradle, and Git.

## Project Structure
```
microservices-demo/
├── services/
│   ├── user-service/
│   ├── order-service/
│   └── product-service/
├── jenkins/
│   └── Jenkinsfile
└── gradle/
    └── wrapper/
```

## Prerequisites
- Java 17 or higher
- Gradle 8.x
- Jenkins
- Git
- JFrog Artifactory

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/ahmadshajee/microservices-demo.git
```

2. Set up Git configuration:
```bash
git config --global user.name "ahmadshajee"
git config --global user.email "ahmadshajee2016@gmail.com"
```

3. Install required VS Code extensions:
- GitLens
- Gradle for Java
- Jenkins Pipeline Linter
- Docker

## Branching Strategy
We follow GitFlow branching strategy:
- `main` - Production-ready code
- `develop` - Integration branch for features
- `feature/*` - Feature branches
- `release/*` - Release preparation branches
- `hotfix/*` - Production fixes

## CI/CD Pipeline
The project uses Jenkins for CI/CD with the following stages:
1. Build
2. Test
3. Package
4. Deploy

## Contributing
1. Create a feature branch from `develop`
2. Make your changes
3. Create a Pull Request
4. Ensure CI passes
5. Get code review
6. Merge after approval

## License
MIT 