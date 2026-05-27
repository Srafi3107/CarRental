# 🚗 MRF Car Rental Management System


A high-performance, enterprise-grade car rental application engineered to demonstrate advanced full-stack software architectures. The system pairs a **zero-dependency custom Java HTTP server** running low-latency request handling with a **premium React 19 frontend** featuring responsive glassmorphism interaction design.

---

## ✨ Key Architectural Features

### 🔐 Multi-Stage Security & RBAC Flow
- **State-Validated Password Recovery**: A robust, multi-stage authentication reset pipeline. Recovery requests submitted via client-side states undergo validation constraints and require explicit administrative validation before credentials are rewritten.
- **Role-Based Access Control (RBAC)**: Strict structural partitioning of application states, completely separating **Customer Workspace** layouts from privileged **Administrative Panels**.

### 🚘 Fleet Orchestration & Booking Engine
- **Dynamic Fleet State Synchronization**: Real-time management of vehicle object states with structural metadata strings and **binary data persistence**.
- **Comprehensive Vehicle Specifications**: Componentized parsing of vehicle operational metrics, capturing tracking vectors including *Fuel Layout, Transmission Type, Seating Constraints,* and *Production Metrics*.
- **Temporal Booking Engine**: Algorithmic availability auditing and automated runtime cost evaluation computed dynamically against calendar duration boundaries.
- **Client Analytical Dashboards**: Detailed operational logs archiving historical user booking patterns, profiles, and state preferences.

### 🎨 Human-Centered Interaction Design
- **Glassmorphism Visual Identity**: Premium user interfaces constructed using componentized dark-theme styling and custom, responsive CSS variable structures.
- **Fluid Micro-interactions**: Zero-lag layout animations and micro-interaction transitions optimized via declarative hooks powered by **Framer Motion**.
- **Real-Time Event Feedback**: Low-latency, non-blocking toast notifications conveying system execution feedback across all asynchronous UI mutations.

---

## 🛠️ Technical Implementation Details

### Backend Architecture (Java Core)
- **Zero-Dependency Web Server**: Built strictly using `com.sun.net.httpserver` to demonstrate a primitive-level grasp of network sockets, multi-threaded request-response patterns, and underlying HTTP protocols without third-party frameworks.
- **Service-Oriented Design (SOA)**: Decoupled code architecture defining clean execution barriers between Request Controllers (Handlers), Core Business Logic (Services), and Structured Data Representations (Models).
- **Asynchronous File Persistence**: Fast, lightweight CSV-backed storage pipelines engineered for zero-config environmental deployments.
- **Unified CORS Middleware**: Explicit Cross-Origin Resource Sharing handling to authorize and filter secure network traffic coming from separate frontend pipelines.

### Frontend Engineering (React 19 Core)
- **Modern Declarative Paradigm**: Constructed utilizing React 19 Function Components, optimized lifecycle hooks, and concurrent rendering elements.
- **High-Performance UI Layer**: Custom Vanilla CSS engine structured cleanly to avoid heavy stylesheet compilation overheard, ensuring excellent frames-per-second scores.
- **Hierarchical State Management**: Centralized handling of user authorization sessions, UI state routing trees, and server fleet data streams.

---


