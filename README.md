# POPA Health AI

POPA Health AI is a comprehensive, AI-driven patient engagement platform designed for modern healthcare. Leveraging cutting-edge technologies, the platform provides personalized health recommendations, appointment management, and a virtual health assistant to answer patient queries and deliver actionable insights.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Architecture](#architecture)
- [Technology Stack](#technology-stack)
- [Project Structure](#project-structure)
- [Setup & Installation](#setup--installation)
- [Deployment](#deployment)
- [CI/CD Pipeline](#cicd-pipeline)
- [Contributing](#contributing)
- [License](#license)

## Overview

POPA Health AI integrates a robust FastAPI/Python backend with a modern React-based frontend to create a secure, scalable, and user-friendly patient engagement system. The platform seamlessly integrates with wearable devices (Apple HealthKit, Fitbit, Garmin) and EHR systems (FHIR/HL7) to collect and analyze patient data, providing healthcare professionals with real-time insights and patients with personalized recommendations.

## Features

- **Conversational AI:** Leverages Large Language Models (LLMs) for natural language processing and virtual health assistance.
- **Predictive Analytics:** Uses AI to monitor patient health data and generate personalized recommendations.
- **Secure APIs:** FastAPI backend with JWT-based authentication and advanced encryption for data privacy.
- **Modern Frontend:** React-based UI with animated dashboards and interactive elements.
- **Device & EHR Integration:** Connects to wearable devices and EHR systems to pull comprehensive health metrics.
- **Scalable Infrastructure:** Deployed on AWS using Kubernetes (EKS), with Infrastructure as Code (Terraform) and a robust CI/CD pipeline using GitHub Actions.

## Architecture

The system is designed with a microservices approach:

- **Backend:** FastAPI service handling secure API endpoints, authentication, and AI/ML services.
- **Frontend:** A React application providing a dynamic, user-friendly dashboard.
- **Integration Modules:** Services to connect with wearable device APIs and EHR systems using FHIR/HL7 standards.
- **Infrastructure:** AWS cloud deployment using EKS for container orchestration and Terraform for Infrastructure as Code.
- **CI/CD:** Automated builds, tests, and deployments using GitHub Actions.

## Technology Stack

- **Backend:** Python, FastAPI, SQLAlchemy, JWT
- **Frontend:** React, Vite, Tailwind CSS, Framer Motion
- **AI/ML:** Integration with LLMs (e.g., OpenAI API) and custom predictive analytics models
- **Cloud & Infrastructure:** AWS (EKS, RDS, S3), Terraform, Kubernetes
- **CI/CD:** GitHub Actions, Docker, AWS ECR

## Project Structure

