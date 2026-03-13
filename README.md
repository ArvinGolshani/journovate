# 📈 Journovate | Graph-Based Trading Journal & Performance Intelligence Platform

<img src="assets/logo.png" alt="Journovate Logo" width="200">

[![Laravel](https://img.shields.io/badge/Laravel-12-red?logo=laravel&logoColor=white)](https://laravel.com/)
[![React](https://img.shields.io/badge/React-Frontend-blue?logo=react&logoColor=white)](https://react.dev/)
[![Inertia.js](https://img.shields.io/badge/Inertia.js-Modern%20SPA-purple)](https://inertiajs.com/)
[![PostgreSQL](https://img.shields.io/badge/PostgreSQL-Database-blue?logo=postgresql&logoColor=white)](https://www.postgresql.org/)
[![Redis](https://img.shields.io/badge/Redis-Cache-red?logo=redis&logoColor=white)](https://redis.io/)
[![Vite](https://img.shields.io/badge/Vite-Build%20Tool-yellow?logo=vite&logoColor=white)](https://vitejs.dev/)
[![Status](https://img.shields.io/badge/Status-MVP%20In%20Progress-success)](#project-status)

---

## 📖 Table of Contents

1. [About the Project](#about-the-project)  
2. [The Problem](#the-problem)  
3. [The Solution](#the-solution)  
4. [Core Features](#core-features)  
5. [System Architecture](#system-architecture)  
6. [Modules](#modules)  
7. [Tech Stack](#tech-stack)  
8. [Screenshots](#screenshots)  
9. [Project Status](#project-status)  
10. [Future Vision](#future-vision)  
11. [Developer](#developer)

---

## 📌 About the Project

**Journovate** is a **graph-based trading journal and performance intelligence platform** designed to help traders understand not only **what they traded**, but also **why they traded**, **how they felt**, **which market conditions existed**, and **how closely their actions matched their trading plan**.

Unlike traditional trading journals that focus mainly on numbers, Journovate is built to capture the **full decision-making context** behind each trade — including strategy, setup, trigger, market conditions, news, emotions, thoughts, decisions, and results.

The goal is to transform trading journaling into a system for **self-awareness, behavioral analysis, and long-term performance improvement**.

---

## ❗ The Problem

Most trading journals only record basic trade data such as:

- entry and exit
- profit and loss
- position size
- win rate

But trading performance depends on much more than statistics.

In real trading, outcomes are also affected by:

- market structure and conditions
- whether the trade matched the trader’s plan
- emotional state during execution
- impulsive or disciplined decisions
- repeated psychological patterns
- reactions to news or external pressure

Because these factors are usually not captured properly, traders struggle to identify the **real reasons** behind poor performance or inconsistency.

---

## ✅ The Solution

Journovate solves this problem by providing a **modular and graph-driven platform** where traders can journal their trades together with all important surrounding factors.

The platform allows users to:

- define their own trading plans
- build custom market condition structures
- record strategies, setups, and triggers
- log trades with real execution context
- capture thoughts, emotions, decisions, and results
- connect all these elements through a flexible graph structure
- analyze deviations between ideal conditions and actual behavior
- generate data that can later power intelligent coaching and AI-based insights

---

## 🎯 Core Features

- **Trading Journal:** Record trades with full execution details  
- **Trading Plan Management:** Define ideal trading conditions and rules  
- **Strategy / Setup / Trigger System:** Structure execution logic clearly  
- **Market Condition Customization:** Build flexible personal market condition models  
- **Psychology Tracking:** Record thoughts, emotions, decisions, and outcomes  
- **News Logging:** Attach important market news or events to trades  
- **Risk Management Support:** Track capital and risk-related decision structures  
- **Graph Relationships:** Store logical connections between concepts and events  
- **Deviation Analysis:** Compare actual trades against ideal trading plan conditions  
- **Scalable Architecture:** Designed for future analytics, pattern recognition, and AI integration  

---

## 🧠 System Architecture

Journovate is built around a **graph-oriented domain architecture**.

Instead of storing everything as isolated flat records, the platform models trading knowledge and trading behavior as **nodes and edges**.

This makes it possible to represent:

- conceptual relationships  
- actual trading events  
- behavior patterns  
- plan-vs-reality deviations  
- reusable analysis structures  

### Main architectural ideas:

- **Node / Edge Graph Engine**
- **Modular domain design**
- **Context-rich trade registration**
- **Plan vs Actual comparison**
- **Structured data for future AI analysis**
- **Flexible and scalable backend for complex trader behavior analysis**

This architecture is especially useful for identifying repeated behavioral patterns and building intelligent feedback systems in later stages.

---

## 🧩 Modules

Journovate consists of multiple connected modules. Each module is designed to handle one part of the trader’s workflow.

### 1. Trading Plan Module
Defines the trader’s ideal execution framework.

Examples:
- ideal market conditions
- preferred strategy context
- psychological requirements
- rule-based execution expectations

### 2. Strategy Module
Organizes the trader’s execution logic in three layers:

- **Strategy**
- **Setup**
- **Trigger**

This structure helps separate broad strategic ideas from specific execution signals.

### 3. Market Condition Module
Allows traders to define and store their own market condition structures in a flexible way.

Examples:
- trend state
- volatility condition
- liquidity environment
- session behavior
- custom filters defined by the user

### 4. Trade Module
The central module where actual trades are recorded and connected to all related context.

A trade can be linked to:
- strategy / setup / trigger
- market conditions
- psychological events
- news
- risk management models
- trading plan references

### 5. Trader Psychology Module
Captures internal trader experience around the trade.

Includes:
- thoughts
- emotions
- decisions
- results

This module is designed to support future behavioral pattern analysis and psychological reporting.

### 6. News Module
Stores relevant market news or external events that may have influenced the trade.

### 7. Risk Management Module
Represents the trader’s money and risk handling logic, including the structure behind position sizing or management decisions.

### 8. Graph Engine
The underlying data relationship layer that connects modules through nodes and edges.

This enables the platform to move beyond CRUD-style records and toward meaningful interconnected analysis.

---

## 🛠 Tech Stack

### Backend
- **Laravel 12**
- **PHP**
- **Modular architecture**
- **Service / Action based backend structure**

### Frontend
- **React**
- **Inertia.js**
- **JavaScript / TypeScript-ready architecture**
- **Tailwind CSS**

### Database & Infrastructure
- **PostgreSQL**
- **Redis**
- **Vite**
- **Docker / Laravel Sail**

---

## 🏗 Development Approach

This project is being developed as a serious long-term product, not just a small practice application.

The development process focuses on:

- clean architecture
- modular backend design
- scalable data modeling
- maintainable frontend structure
- future readiness for analytics and AI integration

A major focus of the project is designing a backend that can support both:

1. **traditional product functionality**
2. **advanced behavioral and language-based analysis in the future**

---

## 📸 Screenshots

> Screenshots will be added soon.

---

## 🚧 Project Status

Journovate is currently in active development.

### Current status:
- core platform architecture designed
- major modules implemented at foundation level
- strategy module completed in detail
- graph-based system integrated into project direction
- MVP is in progress

This repository represents an ongoing product with a strong focus on:
- trader journaling
- behavioral analysis
- context-aware trade tracking
- future AI-powered coaching features

---

## 🔮 Future Vision

Journovate is planned to evolve beyond a journal into an intelligent trader improvement platform.

Future goals include:

- pattern detection in trader behavior
- psychological reporting
- weekly and monthly performance summaries
- plan adherence analysis
- similarity matching between trades and market conditions
- intelligent prompts and coaching suggestions
- AI-powered trade reflection assistance
- personalized trader development insights

The long-term vision is to build a platform that acts as a **smart trading companion**, helping traders improve with both data and reflection.

---

## 👨‍💻 Developer

**Arvin Golshani**  
Software Developer | Founder of Journovate

- GitHub: [github.com/ArvinGolshani](https://github.com/ArvinGolshani)

Journovate is one of my main long-term software projects and reflects my strong interest in:

- software engineering
- scalable backend architecture
- product design
- behavioral data modeling
- intelligent systems

---

## ⭐ Notes

This repository is part of my portfolio and demonstrates my practical experience in building a complex real-world web platform using modern technologies and structured software design principles.
