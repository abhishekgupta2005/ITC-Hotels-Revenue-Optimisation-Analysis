Problem Statement:

  ITC Hotels needs a centralized way to analyze financial performance and booking patterns across multiple luxury properties. With varying room categories, occupancy levels, and cancellation rates, stakeholders lack clear, real-time visibility into key drivers of revenue and customer behavior. This project builds an interactive multi-page Power BI dashboard to track revenue, occupancy, and cancellations, enabling data-driven decisions to optimize revenue and improve guest experience.

Dataset Overview

  This project uses a star-schema style Power BI data model built around hotel booking and occupancy analytics. The dataset contains fact tables for Bookings (booking dates, status, platform, guests, revenue/realized revenue, refunds, ratings) and Occupancy (capacity, check-in date, successful bookings). These are connected to dimension tables including Hotels (property details, city, category) and Rooms (room class/category mapping). Relationships are primarily one-to-many from dimensions to facts, enabling filtering and slicing by property, time, and room category.

Solution

  To address ITC Hotels’ need for real-time performance insights, I developed an interactive multi-page Power BI dashboard that consolidates data across bookings, occupancy, hotels, rooms, and calendar dimensions. The report provides end-to-end visibility into key KPIs such as revenue, RevPAR/ADR, occupancy trends, booking behavior, and cancellations/refunds, with drilldowns by property, city, room category, and time period. This enables stakeholders to identify demand patterns, reduce cancellations, optimize pricing and inventory decisions, and improve overall customer experience.
