# AI Lifecycle Open Source Project

This project provides a stable, standardized baseline for participating labs to contribute AI security tools in a consistent and reusable manner. Our goal is to secure the entire AI lifecycle—from training data inspection to agentic deployment.

## Project Overview
- **Standardized Specifications**: Definition of **directory structures and JSON file contracts** to ensure seamless tool interoperability.
- **Security Tools**: Specialized toolsets developed by various labs, covering data sanitization, vulnerability detection, and attack mitigation.
- **AIBOM Integration**: Automated generation and mapping of AI Bills of Materials (AIBOM) for comprehensive risk assessment.
- **E2E Demo**: A lightweight, Docker-first workflow designed to test the entire integrated pipeline with minimal setup.

---

## Repository Structure

### Framework & Specifications
* **ai-lifecycle-spec**: Definitions for standard directory structures, JSON schemas, and example I/O payloads.
* **ai-lifecycle-demo**: End-to-end runnable demo environment (Docker-based).

### Core Security Tools
Each tool adheres to the project’s **standard directory and JSON specifications** while focusing on a specific security domain.

| Repository Name | Description | Research Organization |
| :--- | :--- | :--- |
| **[T1-Data-Sanitization](https://github.com/IoTcube-AIbom/T1-Data-Sanitization)** | Training Data Poisoning Inspection & Sanitization Report. | SKKU |
| **[T2-AI-Model-Vulnerability-Detection](https://github.com/IoTcube-AIbom/T2-AI-Model-Vulnerability-Detection)** | Post-Training Model Vulnerability & Backdoor Detection. | SKKU |
| **[T3-AI-Agent-Vulnerability-Detection](https://github.com/IoTcube-AIbom/T3-AI-Agent-Vulnerability-Detection)** | Scenario-Based Vulnerability Detection for Agentic AI Systems. | SKKU |
| **[T4-AIBOM-Generation](https://github.com/IoTcube-AIbom/T4-AIBOM-Generation)** | Automated AIBOM Generation (Model, Library, and Dependency Scanning). | Korea Univ. |
| **[T5-AIBOM-based-Vulnerability-Detection](https://github.com/IoTcube-AIbom/T5-AIBOM-based-Vulnerability-Detection)** | AIBOM-Based Vulnerability Mapping & Risk Impact Assessment. | Korea Univ. |
| **[T6-Attack-Mitigation](https://github.com/IoTcube-AIbom/T6-Attack-Mitigation)** | Feasibility Assessment of Countermeasure Policies by Attack Scenario. | Korea Univ. |
| **[TTA-repo](https://github.com/IoTcube-AIbom/TTA-repo)** | [저장소 설명 입력] | TTA |
| **[MCCAAi-repo](https://github.com/IoTcube-AIbom/MCCAAi-repo)** | [저장소 설명 입력] | MCCAAi |
| **[CSSA-repo](https://github.com/IoTcube-AIbom/CSSA-repo)** | [저장소 설명 입력] | CSSA |
---

## Getting Started

1.  **Understand the Specs**: Start with **ai-lifecycle-spec** to review the required **directory structures** and **JSON file formats**.
2.  **Run the Demo**: Use **ai-lifecycle-demo** to experience how all tools integrate based on the shared specifications.
3.  **Explore Tools**: Visit individual **T\*- repositories** for specific implementation details and technical stacks.

## Contributing
We welcome contributions from participating labs and external collaborators. To ensure efficient collaboration:
- Please keep pull requests **small and focused**.
- Include **tests** whenever applicable.
- Ensure all tool outputs remain **fully compatible** with the defined directory and JSON specs.
- For major design proposals, please open an issue or discussion first.

## Communication
- For technical discussions, please use **GitHub Issues/Discussions** in the relevant repository.
- For cross-lab coordination, please reach out to the **designated contacts** listed in the project notes.

## License
Unless otherwise stated, repositories in this organization are released under the license specified within each individual repository.
