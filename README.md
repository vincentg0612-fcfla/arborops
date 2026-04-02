# ArborOps + Olive

ArborOps is a full tree service operating system built by transforming Odoo 19 into a vertical platform for jobs, estimates, routing, scheduling, employee operations, emergency response, and an AI assistant named Olive.

Olive is the secure assistant layered on top of ArborOps. She works across the native iPhone app and the manager portal, helping teams summarize daily work, find scheduling gaps, recommend route-aware decisions, create reminders, schedule jobs, support forecasts, and respond to emergencies.

## What this repository contains

This repository contains the public showcase website for ArborOps + Olive. It is intended to show:

- how a generic Odoo 19 deployment was transformed into a tree-service-specific operating system
- the mobile and manager-portal product experience
- Olive’s role as a real operational assistant rather than a generic chatbot
- the emergency response system tied to job, crew, and employee medical context
- the architecture connecting Odoo, Azure AI, Azure Speech, n8n, weather data, and scheduling intelligence

## Core features highlighted

- Native iPhone app for employees and managers
- Manager portal with dashboard, calendar scheduling, and route configuration
- Olive AI assistant in both mobile and portal experiences
- Weather-aware and route-aware operational assistance
- Reminder creation and schedule execution after confirmation
- Emergency declaration workflow with push alerts, job context, medical details, and rapid escalation

## System summary

- Backend: custom Odoo 19 / ArborOps
- Orchestration: n8n
- Assistant reasoning: Azure AI
- Voice: Azure Speech
- Weather + geocoding: Open-Meteo
- Route planning support: internal logic + route configuration
- Clients: native iPhone app + manager portal
