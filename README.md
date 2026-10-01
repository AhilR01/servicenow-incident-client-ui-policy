# ServiceNow Incident – Client Script & UI Policy

A ServiceNow-based project demonstrating **Client Scripts and UI Policies** to control, validate, and dynamically manage fields on the **Incident** form.

The project was developed and tested in a **ServiceNow Developer Instance**, with implementation evidence captured through screenshots.

---

## 📌 Project Overview

This project focuses on configuring client-side behavior for the ServiceNow **Incident** form.

The implementation demonstrates how **UI Policies** and **Client Scripts** can be used to:

- Control field visibility and state
- Apply mandatory and read-only behavior
- Perform client-side validation
- Respond dynamically to field changes
- Validate data before form submission
- Handle applicable list-edit interactions
- Verify both positive and negative scenarios

---

## 👥 Team Information

| Role | Name |
|---|---|
| **Team ID** | `SWTID-2026-2035` |
| **Team Size** | 5 |
| **Team Leader** | Ahil R |
| **Team Member** | Mohan Das K J |
| **Team Member** | DILIBAN A |
| **Team Member** | Shiva Prakash K R |
| **Team Member** | Venkatraghul M |

**Project Execution:** 28 September 2026 – 01 October 2026  
**Documentation Date:** 03 October 2026

---

## 🏗️ Repository Structure

```text
servicenow-incident-client-ui-policy/
│
├── 1. Ideation Phase/
├── 2. Requirement Analysis/
├── 3. Project Design Phase/
├── 4. Project Planning Phase/
├── 5. Project Development Phase/
├── 6. Project Documentation/
├── Proofs (Screenshots)/
└── README.md
```

### 📂 1. Ideation Phase

Contains the initial project concept, problem understanding, proposed solution, and ideation-related documentation.

### 📂 2. Requirement Analysis

Contains the identified requirements and analysis performed before implementation.

This phase establishes what the Incident form should do and what behavior needs to be achieved through ServiceNow configuration.

### 📂 3. Project Design Phase

Contains the design-related materials explaining the proposed solution and the interaction between the Incident form, UI Policies, and Client Scripts.

### 📂 4. Project Planning Phase

Contains planning-related documentation, milestones, task organization, and project execution planning.

### 📂 5. Project Development Phase

The main implementation phase.

This section contains the project development/configuration work performed inside the **ServiceNow Developer Instance**, including the configured client-side behavior.

### 📂 6. Project Documentation

Contains the final project documentation describing the implementation, configuration, testing, setup, and project outcome.

### 📂 Proofs (Screenshots)

Contains the collected screenshots serving as implementation and testing evidence.

These proofs demonstrate the configured ServiceNow behavior and the completion of the required project activities.

---

## ⚙️ Technology / Platform

- **ServiceNow Developer Instance**
- **Incident Management**
- **UI Policy**
- **UI Policy Action**
- **Client Scripts**
  - `onChange`
  - `onSubmit`
  - `onCellEdit` where applicable

The project is implemented directly within ServiceNow and therefore does **not** require a separate local frontend/backend application.

---

## 🔄 Project Workflow

```text
Incident Form
      │
      ▼
User enters / changes field values
      │
      ▼
UI Policy evaluates conditions
      │
      ├──► Field visibility / mandatory / read-only behavior
      │
      ▼
Client Script executes when applicable
      │
      ├──► Dynamic validation
      ├──► Change-based validation
      └──► Submission validation
      │
      ▼
Validation Result
      │
      ▼
Incident Record Saved
```

---

## 🧪 Testing

The project includes testing of the configured Incident-form behavior, including:

- Positive test scenarios
- Negative test scenarios
- Field-state behavior
- Client-side validation
- Form submission validation
- Reverse-condition testing
- Applicable list-edit behavior
- Screenshot-based evidence

The **Proofs (Screenshots)** folder provides visual evidence of the implementation and testing performed in the ServiceNow environment.

---

## 📸 Project Evidence

The repository contains screenshots covering the relevant stages of:

**Configuration → Execution → Testing → Validation**

These screenshots are maintained separately in:

```text
Proofs (Screenshots)/
```

This keeps the implementation and documentation folders organized while providing a dedicated location for project evidence.

---

## 📚 Documentation

For complete project details, refer to:

```text
6. Project Documentation/
```

The documentation covers the project overview, architecture, setup, configuration, testing, screenshots/demo information, known limitations, and possible future enhancements.

---

## 🎯 Project Outcome

The project demonstrates the use of **ServiceNow UI Policies and Client Scripts** to implement controlled and validated behavior on the Incident form.

The completed repository brings together:

> **Ideation → Requirements → Design → Planning → Development → Documentation → Proof**

in a structured project lifecycle.

---

## 🚀 Future Enhancements

Possible future improvements include:

- Extending validation to additional Incident fields
- Adding complementary server-side validation
- Introducing automated regression testing
- Packaging configuration for controlled instance promotion
- Adding dashboards or reports for Incident data quality

---

## 📅 Project Timeline

| Phase | Period |
|---|---|
| Project Start | 28 September 2026 |
| Development & Testing | 29 September – 01 October 2026 |
| Project Completion | **01 October 2026** |
| Documentation Date | 03 October 2026 |

---

## 👨‍💻 Team

**Team ID:** `SWTID-2026-2035`

Developed as a team project using the **ServiceNow Developer Instance**.

---

## ⭐ Repository Summary

> **A structured ServiceNow project demonstrating Incident-form automation, validation, and field behavior using Client Scripts and UI Policies, supported by complete project documentation and screenshot-based evidence.**
