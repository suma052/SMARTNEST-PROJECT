# SMARTNEST
## Smart Home Automation and Monitoring System

**Project Author:** Suma  
**Project Type:** IoT / Software Engineering  
**Status:** Starter software prototype and design proposal

SMARTNEST is a modular smart-home project concept for monitoring room conditions and organizing device-control requests. This repository contains a Java console prototype, requirements, test plan, UML/design diagrams, and a LaTeX proposal.

> **Important scope note:** This repository is a learning prototype. It does not connect to real sensors, Wi-Fi devices, relays, or household electrical wiring. Hardware integration is future work and must be performed with suitable supervision and electrical safety precautions.

## Objectives
- Demonstrate Java object-oriented programming and input validation.
- Simulate room temperature and light readings.
- Let users view device status and create simulated control requests.
- Document a future architecture for sensor and microcontroller integration.
- Provide a clear project structure suitable for GitHub and course submission.

## Features in this starter version
- View simulated room sensor readings.
- View simulated light and fan status.
- Request simulated light/fan state changes.
- Input validation and clear messages.
- No real hardware actuation.

## Technology stack
| Layer | Technology |
|---|---|
| Starter application | Java 17+ |
| Future sensor / IoT integration | ESP8266 or ESP32 |
| Future embedded firmware | Arduino C/C++ |
| Future web/mobile interface | To be selected |
| Design diagrams | Mermaid and PlantUML |
| Proposal | LaTeX |
| Version control | Git and GitHub |

## Repository structure
```text
SMARTNEST/
├── README.md
├── .gitignore
├── prototype/
│   └── src/smartnest/
│       ├── Main.java
│       ├── HomeDevice.java
│       ├── SensorReading.java
│       └── SmartHomeController.java
├── diagrams/
│   ├── architecture.mmd
│   └── class-diagram.puml
├── docs/
│   ├── REQUIREMENTS.md
│   ├── DEVELOPMENT_PLAN.md
│   └── TEST_PLAN.md
├── proposal/
│   └── proposal.tex
└── assets/
```

## Run the Java prototype
Install JDK 17 or newer. Open a terminal in the repository root and run:

```bash
javac -d out prototype/src/smartnest/*.java
java -cp out smartnest.Main
```

On Windows CMD or PowerShell, the same commands work if `java` and `javac` are on PATH.

## Build the proposal PDF
Install MiKTeX or TeX Live. Open a terminal in `proposal/` and run:

```bash
pdflatex proposal.tex
pdflatex proposal.tex
```

## GitHub and Canvas submission
1. Create a GitHub repository named `SMARTNEST`.
2. Upload the contents of this folder to the repository root (upload the files inside the `SMARTNEST` folder, not the ZIP itself, if your instructor expects source files).
3. Commit the files.
4. Copy the repository URL, for example `https://github.com/YOUR-USERNAME/SMARTNEST`.
5. Open the relevant Canvas assignment, paste the repository URL into the submission field, and submit. Follow your instructor's exact instructions if they require a ZIP or report PDF instead.

## Limitations and safety
Sensor values are simulated. Device controls only change in-memory simulation values and do not operate real devices. Do not connect the prototype to mains electricity. Any future physical integration should use certified, properly rated hardware and qualified supervision.

## Author
**Suma**

