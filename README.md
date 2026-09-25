<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/profile-header-dark.svg">
  <source media="(prefers-color-scheme: light)" srcset="assets/profile-header-light.svg">
  <img src="assets/profile-header-light.svg" alt="Abstract system diagram with connected nodes, circuit paths and a circular robotics motif" width="100%">
</picture>

# Ian Mondelaers

**Software Engineer · Backend and full-stack systems · Robotics**

I build software with an eye for clear boundaries, maintainability and the trade-offs behind each design decision. My public work spans real-time applications, reliable automation, browser engineering and robotics simulation. I'm completing a Bachelor's in Applied Computer Science at AP Hogeschool Antwerpen, with a Robotics minor.

<a href="https://www.linkedin.com/in/ian-mondelaers/"><img src="assets/linkedin-button.svg" alt="LinkedIn profile" height="36"></a> <a href="mailto:mondelaers.ian@gmail.com"><img src="assets/email-button.svg" alt="Email Ian" height="36"></a>

## Engineering focus

- **Software architecture** — clear boundaries and explicit trade-offs.
- **Backend systems** — data modelling, authorization and real-time delivery.
- **Reliability** — deterministic behaviour, failure recovery and testing.
- **Robotics and intelligent systems** — simulation work today; AI and agentic systems are an area I'm exploring.

## Selected engineering work

### [Concord](https://github.com/DenGian/concord)

*Real-time systems · Authorization · Application architecture*

A full-stack community platform built with Next.js, TypeScript and PostgreSQL. Authorization is checked at the data boundary, while cursor-paginated history and Server-Sent Events handle messaging; the README also documents the single-instance limit of its in-memory event hub.

### [Image Converter](https://github.com/DenGian/image-converter)

*WebAssembly · Browser systems · Product engineering*

A browser-based batch converter that keeps files on the user's device. Web Workers move conversion and ZIP creation off the main thread; codec checks, resource limits, accessibility reviews and cross-browser tests shape the product around real browser constraints.

### [Smart Light Controller](https://github.com/DenGian/smart-light-controller)

*Reliability · Failure recovery · Automated testing*

A .NET smart-light simulation with deterministic scheduling across midnight. Replaceable time and output boundaries make failure thresholds, safe-mode shutdown and recovery testable without a physical device or live time service.

### [Roomba Webots Digital Twin](https://github.com/DenGian/roomba-webots-digital-twin)

*Robotics · Autonomous navigation · Simulation*

A Python and Webots robotic-vacuum simulation. A state machine coordinates LiDAR-assisted obstacle avoidance, carpet-aware cleaning and battery-aware docking; its navigation uses simulator-provided position data.

## Professional practice

During a six-month full-stack software engineering internship at HolonCom in 2025, I worked across a .NET ecosystem on shared libraries, testing, CI/CD and deployment tooling. I kept a public [engineering internship journal](https://holoncom-blog.vercel.app/) documenting that work.
