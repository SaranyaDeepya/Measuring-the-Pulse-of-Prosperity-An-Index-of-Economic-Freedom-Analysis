Project Design Phase – Economic Freedom Analysis
Overview

This phase defines the user journey, system workflow, technical architecture, and functional requirements for the project “Measuring the Pulse of Prosperity: An Index of Economic Freedom Analysis.”
The goal is to design a structured platform that enables policymakers and researchers to analyze economic freedom data using visualization and analytics tools.

1. Customer Journey Map

The customer journey outlines how users interact with the platform from discovery to decision-making.

Key Stages

Discover

Need: Understand economic trends

Action: Search reports and government sources

Pain Point: Scattered and outdated data

Opportunity: Unified interactive dashboard

Explore

Need: Country-wise and yearly comparisons

Pain Point: Manual chart browsing and repetitive work

Solution: Filter-enabled economic freedom platform

Engage

Need: Correlate economic freedom with GDP

Pain Point: Manual dataset merging

Solution: Pre-built correlation and trend visualization

Decide

Need: Prepare stakeholder reports

Pain Point: Lack of storytelling clarity

Solution: Tableau story points with captions

These stages are described in the journey table provided in the document.

Customer Journey Map

2. Data Flow Diagram

The data flow explains how information moves through the system.

Workflow

User uploads CSV/JSON datasets

Data stored in Google Drive or Local storage

Cleaning and transformation using Python & Pandas

Processed data used to design Tableau dashboards

Story templates generate Tableau Story Points

Stakeholders access insights via Tableau Public/Server

The diagram on page 1 shows the complete pipeline from data upload to stakeholder interaction.

Data Flow Diagram

3. Solution Requirements
   Functional Requirements

Key system capabilities include:

User Registration and Confirmation

Data Ingestion & Validation

Economic Freedom Index Calculation

Interactive Visualizations (Bar, Line, Scatter, Maps)

Trend Analysis and Country Comparisons

Reporting & Export (PDF, HTML, PNG)

Authentication and Role-Based Access

Advanced Search and Filter Features

These features are listed in the functional requirement table.

Solution Requirements

Non-Functional Requirements

System quality attributes include:

Usability with intuitive interface

Security and data protection

Reliability and accuracy

High performance during processing

Availability and scalability

Maintainability and modular design

The non-functional requirement table on page 3 outlines these constraints.

Solution Requirements

4. Technology Stack & Architecture
   Technical Components

User Interface: HTML, CSS, JavaScript, Angular/React

Application Logic: Java or Python

AI Services: IBM Watson STT and Watson Assistant

Database: MySQL / NoSQL

The architecture table on page 1 lists component-wise technologies used in the system.

Technology Stack

Architecture Characteristics

Open-source frameworks

Secure authentication and encryption

Scalable multi-tier architecture

Load-balanced and distributed deployment

Performance optimization using caching/CDNs

The characteristics table on page 2 describes scalability, security, and performance considerations.

Technology Stack

Tools & Technologies

Tableau Dashboard & Story Points

Python & Pandas for Data Processing

Web Technologies (HTML/CSS/JS)

Cloud Storage & Databases

IBM Watson Services

Design Outcome

This design phase ensures:

A clear user journey for policymakers and researchers

Structured data flow from ingestion to visualization

Strong technical architecture

Scalable and secure analytics platform
