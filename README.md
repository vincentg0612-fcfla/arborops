# ArborOps + Olive  
### AI-Powered Operations Platform for Tree Service Companies

ArborOps is a fully customized field operations platform built on top of Odoo 19, transformed into a purpose-built system for tree service businesses.  

At the core of ArborOps is **Olive**, an AI assistant that understands real operational context — schedules, crews, jobs, weather, and routing — and turns natural language into actionable decisions.

---

## 🌳 The Problem

Tree service companies operate in highly dynamic environments:

- Crews move across multiple job sites daily
- Scheduling depends on geography, weather, and crew availability
- Estimates, jobs, and routing are tightly coupled
- Existing tools are generic and disconnected

Most ERP systems (including Odoo out-of-the-box) are not designed for this workflow.

---

## 🚀 What We Built

We transformed Odoo 19 into a **vertical SaaS platform for tree service operations**.

### Core System (Odoo → ArborOps)

We extended and rebuilt key Odoo modules to support real-world tree service workflows:

- **Jobs & Work Orders**
  - Location-based job tracking
  - Crew assignments and live status
  - Route-aware scheduling

- **Estimates Pipeline**
  - Visit scheduling
  - Conversion tracking (quoted → won)
  - Integration with job creation

- **Crew & Workforce Management**
  - Crew grouping (Alpha, Bravo, etc.)
  - Time tracking and attendance
  - Role-based access (manager, foreman, crew)

- **Scheduling Engine**
  - Calendar-based operations view
  - Route-aware clustering
  - Travel buffer management

---

## 🫒 Olive — AI Operations Assistant

Olive is not a chatbot.  
She is an **operational interface to the business**.

### What Olive Can Do

- Answer real-time questions:
  - “What do I need to know today?”
  - “What still needs to be scheduled?”
  - “Who is working with me today?”

- Weather-aware insights:
  - Job-level weather risk
  - Forecast-based planning

- Smart scheduling:
  - Recommends optimal job groupings
  - Minimizes travel distance
  - Aligns with existing crew routes

- Task execution:
  - Create reminders
  - Schedule jobs and estimates
  - Trigger backend workflows

---

## 🧠 Architecture

ArborOps combines multiple systems into a unified AI platform:

### Backend
- **Odoo 19 (heavily customized)**
  - Core data model (jobs, crews, estimates)
  - REST APIs for Olive actions
  - Portal system for employees

### AI Layer
- **Azure AI (LLM + Speech)**
  - Natural language understanding
  - Voice conversation capability

### Orchestration
- **n8n**
  - Workflow engine for Olive
  - Scheduling logic
  - Weather integration (Open-Meteo)
  - Routing recommendations

### Mobile App (iOS)
- Built with Swift + MSAL
- Azure-authenticated sessions
- Voice + chat interface with Olive

### Portal
- Custom Odoo SPA
- Employee dashboard
- Embedded Olive assistant
- Real-time operational context

---

## 🔐 Enterprise-Grade Authentication

- Microsoft Entra ID (Azure AD)
- Token-based identity propagation
- Role-aware context (manager, crew, etc.)
- Secure API gateway between systems

---

## 🗺 Intelligent Scheduling System

We implemented a custom scheduling model:

- Haversine-based clustering
- Job proximity grouping
- Route anchoring to existing schedules
- Travel buffer optimization

Olive can:
- Recommend what to schedule next
- Ask for missing inputs (time, crew)
- Execute scheduling via API

---

## 🌦 Real-Time Weather Integration

- Open-Meteo API integration
- Location-based forecasts
- Time-of-day awareness (morning, afternoon, etc.)
- Weather risk surfaced in scheduling decisions

---

## 📱 Cross-Platform Experience

### iOS App
- Native Swift UI
- Voice-enabled Olive assistant
- Real-time operations access

### Web Portal
- Full management dashboard
- Olive chat embedded in UI
- Scheduling + routing tools

---

## 🔥 Key Innovation

This project turns a traditional ERP into:

> **An AI-driven operational control system for real-world field work**

Olive bridges:
- human language  
- business data  
- real-world constraints  

---

## 📸 Product Screens

(See screenshots in repository)

- iOS app (jobs, schedules, Olive assistant)
- Manager portal (calendar, routing, Olive chat)
- Live scheduling workflows

---

## 🏁 Outcome

ArborOps is not a prototype.

It is a working system that:
- manages real operational workflows
- integrates AI into daily decision-making
- replaces multiple disconnected tools with one intelligent platform

---

## 👤 Built By

Garrett Vincent  
Systems Engineer  

---

## 🌐 Future Vision

- Fully autonomous scheduling
- Predictive workload balancing
- Voice-first operations control
- Multi-company deployment

---
