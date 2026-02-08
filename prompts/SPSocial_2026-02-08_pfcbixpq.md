# WEB Application Development Prompt

## Application Type: Web Application
## Category: Frontend Development
## Template: SPSocial

---

**IMPORTANT**: This is a comprehensive development prompt for building a web application. Follow ALL guidelines, standards, and precautions outlined below for optimal code quality, security, and maintainability.

## Project Description
Linked in post generator

## 🎯 Project Overview

**Description**: Linked in post generator

**Key Features to Implement**:


**Development Approach**: Follow the guidelines and standards outlined in this prompt to ensure high-quality, maintainable, and secure code.

## 📋 Project Reference Documents

> **Note for AI coding tools**: Read the full documents referenced below for complete context before implementing.

### Product Requirements Document (PRD)

# Project Requirements Document: LinkedInBlog Generator

## 1. Introduction

The LinkedInBlog Generator is a tool designed to create LinkedIn posts for a given topic. Each generated post should include a title, body, and footer. This project aims to simplify the process of generating structured LinkedIn content by automating the creation of these components, thus saving time and ensuring consistency for users who regularly engage their professional network on LinkedIn.

...

📄 **Full document**: @docs/prd.md

---

### Technology Stack & Architecture

# Technology Recommendations for LinkedInBlog Generator

## 1. Frontend Technologies

### React
- **Justification**: React is a widely adopted JavaScript library for building user interfaces. Its component-based architecture allows for reusable UI components, making it ideal for a project that requires dynamic and responsive user interfaces. React's large ecosystem and active community support ensure longevity and ease of finding resources or tools to complement the project.

### Tailwind CSS
...

📄 **Full document**: @docs/techstack.md

---

### Frontend Implementation Guide

# LinkedInBlog Generator Frontend Implementation Guide

This guide provides a detailed implementation strategy for creating a LinkedInBlog Generator, focusing on the frontend development. It includes component structure, state management, UI/UX guidelines, and code examples.

## 1. Component Structure

The application will be structured using reusable React components. Below are the key components needed to implement the features:

### Components

...

📄 **Full document**: @docs/frontend.md

---

### Requirements Specification

# Project Overview

The LinkedInBlog Generator is a tool designed to assist users in creating LinkedIn posts based on a given topic. The generated post should include three main components: a Title, a Body, and a Footer. The intention is to streamline the process of crafting professional and engaging content suitable for LinkedIn's platform.

# Functional Requirements

1. **Title Generation**
...

📄 **Full document**: @docs/requirements.md

---

### Application Flow & User Journeys

# LinkedinBlog Generator System Flow Documentation

## 1. User Workflows

### Overview
This section describes how users will interact with the LinkedinBlog Generator system to create LinkedIn posts.

### User Journey
1. **Login**: Users authenticate themselves via the system's login interface.
2. **Input Topic**: Users input a specific topic they want to generate content for.
3. **Content Customization**: Users might optionally customize the format or specific elements of the content.
...

📄 **Full document**: @docs/flow.md

---

### Backend Implementation Guide

```markdown
# LinkedinBlog Generator Backend Implementation Guide

**Version:** 1.0  
**Date:** 2/7/2026

---

## 1. API Design

### Key Endpoints

1. **Create Post**
   - **Method:** POST
   - **Endpoint:** `/api/posts`
   - **Payload:**
     ```json
     {
       "topic": "string",
       "title": "string",
       "body": "string",
       "footer": "string"
     }
     ```
   - **Response:**
     ```json
     {
       "postId": "string",
       "status": "success"
     }
     ```

...

📄 **Full document**: @docs/backend.md

---

### Project Status & Progress

# Project Status Tracking Template: LinkedInBlog Generator

## 1. Implementation Phases

### Phase 1: Requirement Analysis and Design
- Understand the requirements for generating LinkedIn posts (Title, Footer, Body).
- Design the architecture of the LinkedInBlog Generator.

### Phase 2: Development
- **Feature 1:** Title Generation
  - Develop algorithms to generate engaging and relevant post titles.
- **Feature 2:** Body Content Creation
...

📄 **Full document**: @docs/status.md

---

### diagram_sequence

Certainly! Below is a sample LinkedIn post for the "LinkedinBlog Generator" project, along with a markdown file containing Mermaid.js sequence diagrams for the key user flows.

---

### LinkedIn Post

**Title:** Enhancing Software Architecture with Mermaid.js Sequence Diagrams

**Body:**
...

📄 **Full document**: @docs/diagram_sequence.md

---

### diagram_component

Certainly! Below is a LinkedIn post that includes a title, body, and footer. Following the post, you'll find a markdown file containing a Mermaid.js flowchart as per your requirements.

---

**Title: Simplifying Architecture with Component Diagrams**

**Body:**
...

📄 **Full document**: @docs/diagram_component.md

---

### diagram_architecture

Certainly! Below is a LinkedIn post with a title, body, and footer, followed by the markdown code containing the Mermaid.js diagram for a high-level system architecture.

---

**Title:** Crafting a Robust System Architecture with Mermaid.js

**Body:**

...

📄 **Full document**: @docs/diagram_architecture.md

## 🏗️ Architecture Guidelines

**Pattern**:
- Component-based architecture, Container/Presentational component pattern, Custom hooks pattern, Compound component pattern

**Description**:
- Application architecture pattern

**Structure**:
- **directories**: Component-based architecture, Container/Presentational component pattern, Custom hooks pattern, Compound component pattern
- **files**: Unidirectional data flow, Props down, events up pattern, Context for global state, Server state vs client state separation
- **conventions**: File-based or declarative routing, Protected routes for authentication, Lazy loading for route components, Proper error handling for routes

**Data Flow**:
- Unidirectional data flow, Props down, events up pattern, Context for global state, Server state vs client state separation

**State Management**:
- React State

**API Design**:
- RESTful

## 📋 Development Guidelines



## 📏 Coding Standards



## 📚 Required Libraries and Dependencies



## 🔒 Security Considerations



## ⚡ Performance Guidelines



## ✨ Best Practices

## 🧪 Testing Guidelines
  
  

## 🚀 Deployment Guidelines
  
  

## ⚠️ Critical Precautions



## 🛠️ Implementation Instructions

Build a responsive web application with modern frontend framework. Ensure cross-browser compatibility and accessibility.

### Development Workflow
1. **Setup**: Initialize project with proper structure and dependencies
2. **Core Implementation**: Build core functionality following architecture guidelines
3. **Security**: Implement security measures as outlined above
4. **Testing**: Write comprehensive tests for all components
5. **Performance**: Optimize based on performance guidelines
6. **Documentation**: Document all APIs, components, and deployment procedures
7. **Deployment**: Follow deployment guidelines for chosen platform

### Quality Checklist
- [ ] All security requirements implemented
- [ ] Performance optimizations applied
- [ ] Comprehensive test coverage achieved
- [ ] Code follows all coding standards
- [ ] Documentation is complete and accurate
- [ ] Deployment configuration is ready

---

## 📚 Final Notes

**Remember**: This prompt contains comprehensive guidelines for building a high-quality application. Prioritize security, performance, and maintainability throughout the development process.

**Code Quality**: Follow all coding standards and best practices outlined above.
**Security First**: Never compromise on security requirements.
**Performance**: Optimize early and measure continuously.
**Testing**: Maintain high test coverage and quality.

**Good luck with your development!** 🚀