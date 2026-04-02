# 🌿 ArborOps + Olive

**AI Operations Assistant for Field Service Teams**

ArborOps + Olive is a real-world AI-powered operations system designed to help field service teams plan work, communicate faster, and make better decisions using natural conversation.

---

## 🚀 Overview

This project combines a custom-built operations platform (**ArborOps**) with an intelligent assistant (**Olive**) that works across both mobile and web environments.

Olive acts as a role-aware assistant that understands operational context and helps employees take action — not just get answers.

---

## 🧠 Key Capabilities

### 📊 Operations Awareness
- Understands jobs, estimates, crews, schedules, and daily workload
- Summarizes what matters today based on role and context

### 📅 Smart Scheduling
- Identifies unscheduled jobs and backlog
- Recommends what to schedule next using distance and routing logic
- Executes scheduling actions after confirmation

### 🌦️ Weather Intelligence
- Provides forecasts tied to job locations
- Handles natural queries like:
  - “What’s the weather in Clermont tomorrow morning?”
  - “Will it rain during today’s jobs?”

### 🧭 Routing Insights
- Uses geocoding and routing to recommend efficient job order
- Helps reduce travel time and improve crew efficiency

### 🔁 Task & Reminder Automation
- Creates follow-ups and reminders directly in the system
- Functions like a personal operations assistant

### 🗣️ Voice + Chat Interaction
- Supports both text and voice communication
- Integrated with Azure Speech for real-time interaction

### 📱 Cross-Platform Access
- Available in:
  - iPhone app
  - Employee web portal
- Consistent experience across both

---

## 🏗️ System Architecture

- **Frontend:** iOS app + web portal  
- **Authentication:** Azure (MSAL, secure token validation)  
- **AI Layer:** Azure AI + n8n orchestration  
- **Backend:** Odoo (ArborOps operations system)  
- **Weather:** Open-Meteo  
- **Routing & Geocoding:** OpenRouteService  

Olive sits on top of this stack as a **decision and action layer**, not just a chatbot.

---

## 🎯 Purpose

Field service teams often rely on multiple tools for scheduling, routing, weather, and communication.

This system replaces that fragmented workflow with a single interface where users can simply ask:

> “What should I schedule next?”  
> “What do I need to know today?”  
> “Schedule that job tomorrow at 9.”

And get real, actionable results.

---

## 🌐 About This Repository

This repository contains the public-facing showcase site for the ArborOps + Olive system.

It is intended to demonstrate the product experience, capabilities, and architecture — not the underlying private implementation.

---

## 👤 Creator

**Garrett Vincent**  
ArborOps / Olive Branch Tree Care
