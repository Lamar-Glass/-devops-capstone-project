# DevOps Capstone Project — Customer Accounts Microservice

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-green.svg)](https://shields.io/)

## Project Overview

This repository contains the **Customer Accounts microservice** built as part of the
[**IBM-CD0285EN-SkillsNetwork DevOps Capstone Project**](https://www.coursera.org/learn/devops-capstone-project)
course, which is part of the
[**IBM DevOps and Software Engineering Professional Certificate**](https://www.coursera.org/professional-certificates/devops-and-software-engineering).

The project applies modern DevOps practices end-to-end:

- **Agile Planning** — sprint plans, product backlog, and user stories managed with GitHub Issues and Projects
- **Test Driven Development (TDD)** — RESTful service developed with unit tests written first
- **Continuous Integration (CI)** — GitHub Actions workflow for linting, testing, and security scanning
- **Kubernetes Deployment** — application deployed to Kubernetes/OpenShift
- **Continuous Delivery (CD)** — automated DevOps pipeline for delivery

## Customer Accounts Microservice

A RESTful API that manages customer accounts:

| Method | Endpoint             | Description                          |
|--------|----------------------|--------------------------------------|
| GET    | `/accounts`          | List all customer accounts           |
| GET    | `/accounts/<id>`     | Read a customer account              |
| POST   | `/accounts`          | Create a new customer account        |
| PUT    | `/accounts/<id>`     | Update a customer account            |
| DELETE | `/accounts/<id>`     | Delete a customer account            |

## Author

**Lamar Glass**

## License

Licensed under the Apache License. See [LICENSE](LICENSE)
