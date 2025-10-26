# Software Quality & Testing Projects — Selenium Testing & AgerShipment

**Course:** Software Quality and Testing (CSC4271)  
**Projects:** Selenium IDE Testing (Mid Project) and AgerShipment (Final Project)

[![Usage: Run tests locally](https://img.shields.io/badge/Usage-Run%20tests%20locally-blue)](#usage)  
[![Tool: Selenium IDE](https://img.shields.io/badge/Tool-Selenium%20IDE-orange)](#tools-used)  
[![Project: AgerShipment](https://img.shields.io/badge/Project-AgerShipment-green)](#final-project---agershipment)  
[![Status: Reported Tests](https://img.shields.io/badge/Status-Tested%20(see%20reports)-informational)](#test-summary)

---

## Table of Contents
1. [Executive Summary](#executive-summary)
2. [Files Analyzed](#files-analyzed)
3. [Mid Project — Selenium Testing](#mid-project---selenium-testing)
4. [Final Project — AgerShipment](#final-project---agershipment)
5. [Test Coverage & Artifacts](#test-coverage--artifacts)
6. [Reproducing Selenium Test Steps](#reproducing-selenium-test-steps)
7. [Locating Tests in Final Report](#locating-tests-in-final-report)
8. [Limitations](#limitations)
9. [Authors & Acknowledgement](#authors--acknowledgement)
10. [Appendix: Quick References](#appendix-quick-references)

---

## Executive Summary

This repository contains two course projects for the **Software Quality and Testing** course:

- **Mid Project:** Focused on browser-based testing using **Selenium IDE** (Chrome extension). Demonstrates test recording and execution for multiple modules (Register, Login, Admin, User, Merchant).  
- **Final Project (AgerShipment):** A full-fledged **Test Plan and Execution Report** for an e-commerce web application, including requirement mapping, test case design (FR_1–FR_17), execution results, pass/fail criteria, and limitations.

Both documents were analyzed directly and represent authentic testing work.

---

## Files Analyzed

- `mid-project-selenium-testing.pdf`: Selenium IDE installation and recorded test screenshots.  
- `final-project-agershipment.pdf`: Comprehensive test plan and results for AgerShipment.

---

## Mid Project — Selenium Testing

### Overview
The mid-project showcases the use of **Selenium IDE** for automated UI testing through browser extension. The PDF includes:

- Installation of Selenium IDE via Chrome Web Store.
- Creation of a Selenium project and multiple test cases.
- Recorded test examples and results with screenshots.

### Modules Tested
1. **Register Module:** Valid/invalid inputs (wrong name, username, existing email, wrong confirm password, empty fields).  
2. **Login Module:** Valid credentials, invalid username/password.  
3. **Admin Module:** Dashboard, user management (edit/delete), invalid email.  
4. **User Module:** Buy ticket (valid/empty), profile edit, order list.  
5. **Merchant Module:** Edit hotel/bus/air/launch details (valid/empty).

### Tool Used
- **Selenium IDE (Chrome Extension)**

---

## Final Project — AgerShipment

### Overview
**AgerShipment** is an e-commerce platform for computer hardware (laptops, GPUs, CPUs, etc.). The final report provides a full **Test Plan (TP_AgerShipment_v1.0)**, requirements, testing approach, test cases, and execution results.

### Key Components
- **Requirements:** Functional (FR_1–FR_17) and non-functional.  
- **Testing Approach:** Unit, Integration, System, and Acceptance Testing.  
- **Test Deliverables:** Test Plan, Test Cases, Test Scripts, Test Summary Report, Execution Log, Defect Log, RTM.  
- **Test Tools:** Sublime Text, XAMPP, Selenium IDE, Visual Studio Test Professional.  
- **Results:** Most functional tests passed; "Place Order" marked as *Fail* (feature under development).

---

## Test Coverage & Artifacts

| Area | Coverage | Evidence |
|------|-----------|-----------|
| Selenium IDE UI Testing | Register, Login, Admin/User/Merchant modules | Screenshots in mid-project PDF |
| Manual + Automated Planning | FR_1–FR_17 Test Cases | Final report tables |
| Tools | Selenium IDE, XAMPP, Sublime, Visual Studio | Final report (Section 6.2) |
| Limitations | Payment, API, Email/SMS, Load, Cross-browser | Explicitly listed in final report |

---

## Reproducing Selenium Test Steps

Follow the same steps shown in the mid-project PDF:

1. **Install Selenium IDE (Chrome Extension):** Add via Chrome Web Store.  
2. **Open Selenium IDE:** Access from Extensions.  
3. **Create Project & Test Cases:** Use the Selenium IDE UI.  
4. **Record Steps:** Navigate to target site, fill forms, submit actions.  
5. **Run Tests:** Observe results matching expected outcomes (screenshots provided).

---

## Locating Tests in Final Report

- Test Cases **FR_1–FR_17** appear in the Test Case Table (pages ~19–36).  
- Screenshots and proof images are at the end of the report.  
- Pass/Fail criteria and deliverables listed in sections 8–9.  
- Approval meeting photos (QA Engineer: *Md. Salman Arefin*) also included.

---

## Limitations

Explicit limitations from the final report:

- Payment and refund transaction tests excluded.  
- Third-party API testing (shipping, tax, currency) skipped.  
- Email/SMS end-to-end automation not performed.  
- Performance and load testing excluded.  
- Limited cross-browser/device testing (Chrome, Firefox only).

---

## Authors & Acknowledgement

**Team (AgerShipment):**  
- Sakib Al Mahamud (21-45655-3)  
- Nimur Islam Joy (21-45656-3)  
- Md. Sakibul Haque Tanmoy (21-45659-3)  
- Saikot Kundu (22-46615-1)

**Industry Personnel:**  
- Md. Salman Arefin — Software QA Engineer, Fronture Technologies

---

## Appendix: Quick References

- **mid-project-selenium-testing.pdf:** Selenium IDE installation, project creation, test recordings.  
- **final-project-agershipment.pdf:** Test Plan, Requirements (4.1), Attributes (4.2), Test Cases (FR_1–FR_17), Criteria (8), Deliverables (9), Proofs.

---

© 2025 — Software Quality & Testing Projects Repository
