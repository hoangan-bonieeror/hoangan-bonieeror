# An Nguyen

**Software Developer | Full-Stack & Robotics Automation**

Building software that bridges web applications, embedded systems, and industrial automation.

---

## About Me

I'm An Nguyen, a Software Developer with 2+ years of experience at Unitec Solution Vietnam, where I built full-stack web applications (Angular, Python/Flask) and embedded systems (Python, Raspberry Pi) for industrial automation. My work spans robotics control (AMR/AGV using ROS2, SLAM, Nav2), real-time environmental monitoring, and factory process automation.

I enjoy solving problems that require both clean software architecture and reliable hardware integration, particularly in robotics and industrial IoT contexts. I'm also currently expanding into data engineering, building personal projects around ETL pipelines, database design, and API-driven data ingestion.

---

## Skills

**Frontend:** Angular, TypeScript, HTML/CSS

**Backend:** Python, Flask, REST APIs, Node.js, Express.js

**Robotics & Automation:** ROS2 (Python, C++), SLAM, Nav2, AMR/AGV systems

**Embedded/Firmware:** Python, Raspberry Pi 5, GPIO/sensor integration, C++

**Data Engineering:** ETL pipelines, pandas, SQLAlchemy, SQL schema design, API data ingestion

**Systems & Integration:** Real-time data monitoring, biometric hardware integration, full-stack system architecture, CMS development

**Other:** Git, CI/CD, SQL, PostgreSQL, SQLite, MySQL, SQL server

---

## Experience

### Software Developer — Unitec Solution Vietnam Company
**June 2023 – November 2025** (2 years 5 months)

- Developed full-stack web applications using Angular and Python/Flask for industrial robotics control (AMR, AGV)
- Built embedded firmware in Python for factory alert and monitoring systems using Raspberry Pi
- Worked on robotics automation research and development using ROS2 (Python and C++)
- Maintained and extended production systems based on evolving client requirements across multiple factory automation projects

---

## Projects

### Professional Projects

#### 1. AMR Fleet Management & Navigation System
Developed a full-stack website and companion firmware for controlling Autonomous Mobile Robots (AMR) in a facility. The system serves two core functions: environment mapping using SLAM, allowing clients to scan and generate new facility maps, and autonomous navigation using Nav2, enabling collision-free robot movement across saved maps. Built an interface where clients can place points and define routes connecting them, which the robot follows autonomously. Handled both the web application (Angular/Flask) and the robot-side firmware integration.

**Tech Stack:** Angular, Python/Flask, ROS2 (Python, C++) — SLAM, Nav2

---

#### 2. Factory LED & Audio Alert System (Firmware)
Designed and built an embedded alert system from scratch to warn factory staff when temperature or humidity readings exceeded configurable thresholds. The system uses a 3-LED indicator (red for temperature, yellow for humidity, green for normal range) alongside a speaker for audible alerts. Implemented the firmware logic so red/yellow LEDs activate and green deactivates when thresholds are exceeded, and the reverse when readings return to normal. Thresholds themselves are configured through a separate web platform, with this system consuming those values to drive real-time hardware alerts.

**Tech Stack:** Raspberry Pi 5, Python, GPIO control, speaker/audio output

---

#### 3. Real-Time Environmental Monitoring Dashboard
Maintained and extended a web application for real-time monitoring of temperature and humidity across multiple factory areas, each tracked via a dedicated Raspberry Pi sensor node. Implemented new features allowing clients to configure and adjust temperature/humidity thresholds per area, and to modify monitored areas as facility layouts changed. Built live charting to visualize sensor trends over time, and handled ongoing maintenance and feature updates based on evolving client requirements.

**Tech Stack:** Angular, Python/Flask, Raspberry Pi, real-time charting

---

#### 4. AGV Route Planning & Control Website
Built a full-stack website for controlling Automated Guided Vehicles (AGV), allowing clients to define points and create routes connecting them. The system sends these routes to the AGV, directing it to follow the specified path through the facility. Focused on an intuitive point-and-route interface so non-technical facility staff could configure robot movement without manual programming.

**Tech Stack:** Angular, Python/Flask, AGV control integration

---

#### 5. Canteen Meal Automation & Fingerprint Verification System
Developed a full-stack website to automate meal registration and distribution in a factory canteen. Line leaders register meal orders on behalf of their workers ahead of time, eliminating manual meal-tracking at the counter. During meal times, workers verify their identity via fingerprint scan before receiving their meal — the system checks the scan against the registered order and blocks distribution if there's a mismatch, ensuring each worker receives exactly the meal they were assigned. This automated a previously manual, error-prone process and reduced meal distribution errors and disputes on the canteen floor.

**Tech Stack:** Angular, Python/Flask, fingerprint/biometric hardware integration

---

### Personal Projects

#### 6. Salary Management System *(In Development)*
Full-stack application for automated salary calculations and customizable payroll configuration. Calculates net pay based on basic salary, deductions, advances, bonuses, and insurance profiles. Implemented a customizable policy engine allowing business users to define payroll rules and calculations dynamically.

**Concept Focus:** Customizable policy engine for dynamic payroll rule configuration

**Tech Stack:** Angular, Express.js, Node.js, REST APIs, SQL

---

#### 7. Coco Studio *(In Development)*
A dual-sided web platform featuring a public showcase landing page for clients and a secure administrative portal to manage blogs, draft articles, and stage content publication. Designed and built a custom content management system (CMS) with draft/publish staging mechanisms.

**Concept Focus:** Custom CMS with draft/publish staging workflow

**Tech Stack:** Angular, Express.js, Node.js, CMS Development, SQL

---

#### 8. CSV to Database Pipeline
Built an ETL pipeline that extracts data from public NYC taxi trip CSV files, cleans and transforms it using Python (pandas), and loads it into a PostgreSQL or SQLite database. Focused on data cleaning, schema design, and building a repeatable, reliable ingestion process from raw public data to a structured relational database.

**Skills Demonstrated:** ETL fundamentals, data cleaning, SQL schema design

**Tech Stack:** Python, pandas, SQLAlchemy, PostgreSQL

**Stretch Goal:** Scheduled with a cron job for automated recurring runs

---

#### 9. API Data Ingestion Pipeline
Developed a pipeline that fetches weather data from the OpenWeatherMap free API on a schedule, stores it incrementally in a database, and supports SQL queries and dashboarding on top of the collected data. Focused on building a reliable incremental loading process and a clean data model suited for time-series analysis.

**Skills Demonstrated:** API consumption, incremental loading, data modeling

**Tech Stack:** Python (requests), SQLite/PostgreSQL, optionally Metabase/Tableau Public

**Stretch Goal:** Basic data quality checks (null checks, row count alerts)

---

## Contact

📧 **Email:** hoangan726@gmail.com  
🔗 **LinkedIn:** https://www.linkedin.com/in/tran-hoang-an-nguyen-3168751a6/  
🌐 **Portfolio:** https://hoangan-bonieeror.github.io/portfolio/  
🐙 **GitHub:** https://github.com/hoangan-bonieeror
