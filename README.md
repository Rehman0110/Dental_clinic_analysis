# 🦷 Dental Clinic Analytics Dashboard

> **End-to-End Data Analytics & Business Intelligence Project**

A centralized analytics solution designed to help dental clinic management monitor **marketing performance, lead generation, appointments, treatments, payments, clinics, and revenue**.

---

## 📌 Project Overview

The **Dental Clinic Analytics Dashboard** is an end-to-end Data Analytics and Business Intelligence project built using **Python, ETL, PostgreSQL, SQL, and Power BI**.

The project integrates data from multiple business sources and transforms it into actionable business insights.

The complete business journey is:

**Marketing → Leads → Appointments → Treatments → Payments → Revenue**

The objective is to help management understand:

- Where leads are coming from
- Which marketing campaigns perform best
- How effectively leads convert into appointments
- Which clinics perform best
- Which treatments generate the most revenue
- How appointments and treatments are progressing
- How much revenue is generated
- Where business improvement opportunities exist

---

# 🎯 Project Objectives

The main objectives of this project are:

- Build an end-to-end analytics pipeline
- Centralize data from multiple sources
- Perform ETL on raw datasets
- Clean and validate business data
- Store transformed data in PostgreSQL
- Connect PostgreSQL with Power BI
- Build a business-oriented data model
- Create DAX measures and KPIs
- Develop an interactive Power BI dashboard
- Analyze marketing performance
- Analyze lead and appointment conversion
- Compare clinic performance
- Analyze treatment performance
- Track treatment revenue
- Monitor payment status
- Provide actionable business insights

---

# 🏗️ Project Architecture

```text
                    ┌──────────────────────┐
                    │      Raw Data        │
                    └──────────┬───────────┘
                               │
              ┌────────────────┼────────────────┐
              │                │                │
              ▼                ▼                ▼
        ┌──────────┐     ┌──────────────┐   ┌───────────────┐
        │ leads.csv│     │marketing_ads │   │practice_data  │
        │          │     │    .csv      │   │     .csv      │
        └────┬─────┘     └──────┬───────┘   └───────┬───────┘
             │                  │                   │
             └──────────────────┼───────────────────┘
                                ▼
                    ┌──────────────────────┐
                    │     ETL Pipeline     │
                    │                      │
                    │ Extract              │
                    │ Transform            │
                    │ Validate             │
                    │ Load                 │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │     PostgreSQL       │
                    │  Centralized Storage │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │       Power BI       │
                    │                      │
                    │ Data Model           │
                    │ DAX Measures         │
                    │ Power Query          │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │      Dashboard       │
                    │                      │
                    │ Executive Overview    │
                    │ Marketing & Leads    │
                    │ Clinic & Treatments  │
                    └──────────┬───────────┘
                               │
                               ▼
                    ┌──────────────────────┐
                    │   Business Insights  │
                    └──────────────────────┘
