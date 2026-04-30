# ApplyGo

[![Status: Discontinued](https://img.shields.io/badge/Status-Discontinued-red.svg)](DISCONTINUE.md)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

ApplyGo is an AI-powered job search and recruitment platform. This project was developed as a student initiative to streamline the hiring process using machine learning and microservices architecture.

## Architecture Overview

The system is divided into three primary ecosystems, each handling a specific domain of the application.

### 1. ApplyFlash (Frontend)
Built using the Flutter framework, providing cross-platform support for mobile and web.
- ApplyFlashUser: Interface for job seekers to browse and apply for positions.
- ApplyFlashAdmin: Interface for recruiters to manage listings and track applicants.

### 2. ApplyFlick (Machine Learning)
Python-based backend focusing on AI modules for intelligent matching and ranking.
- JobAlign: Profile matching using content-based filtering.
- ResuRankX: Resume ranking system powered by deep learning.
- TrendVisor: Market trend analysis using LSTMs and Transformers.
- SkillMorph: Ideal candidate profile generation.

### 3. ApplyFlow (Backend Services)
Java Spring Boot microservices providing a robust and scalable infrastructure.
- Core Services: User Management, Community Features, and System Configuration.
- Infrastructure: API Gateway and Service Registry for service discovery.
- Deployment: Containerized environment using Docker Compose.

## Key Features

- Intelligent Job Matching: Connects the right talent with the right opportunities.
- Resume Ranking: Ranks applicants based on skill relevance and job descriptions.
- Microservices Scalability: Modular backend for easy maintenance and scaling.
- Cross-Platform Access: Unified experience across Android, iOS, and Web.

## Project Structure

- ApplyFlash/: Flutter source code for user and admin applications.
- ApplyFlick/: Python scripts and ML model implementations.
- ApplyFlow/: Java source code for microservices and Docker configurations.
- Project Plan.txt: Initial development roadmap.
- ML models.txt: Detailed descriptions of the AI modules.

## Status

This project is officially discontinued. It remains available as an open-source reference for students and developers interested in full-stack AI applications.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

Copyright (c) 2025 Parth Thakor
