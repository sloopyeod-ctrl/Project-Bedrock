# Case Study 002

# Engineering Enterprise Detection Capabilities

---

## Executive Summary

Detection engineering is not the process of creating alerts.

Detection engineering is the discipline of providing engineers with meaningful context that enables rapid, informed security decisions.

Throughout this project I focused on engineering detection capabilities that improved operational visibility while reducing investigation effort across cloud infrastructure, Linux systems, identity, authentication, and enterprise security operations.

---

# Problem

Security operations generated large amounts of telemetry, but visibility was fragmented across multiple systems.

Investigations often required manually collecting information from identity platforms, operating systems, authentication logs, cloud services, VPN solutions, and infrastructure monitoring before engineers could determine what actually happened.

This process consumed valuable engineering time while increasing investigation complexity.

---

# Engineering Objective

Design repeatable detection engineering capabilities that improve visibility, reduce investigation time, and provide engineers with actionable operational context.

The objective was never to generate more alerts.

The objective was to improve engineering decision quality.

---

# Environment

• Microsoft Sentinel

• Azure Log Analytics

• Microsoft Entra ID

• Linux Infrastructure

• Windows Endpoints

• VPN Infrastructure

• Azure Cloud

• CMMC Level 2 Environment

---

# Engineering Decisions

Rather than creating isolated alerts, detections were engineered around operational questions.

Examples included:

• Who authenticated?

• Where did authentication originate?

• Was privileged access modified?

• Did administrative roles change?

• Which Linux systems generated security events?

• Which systems stopped reporting?

• Are authentication failures increasing?

• Are privileged accounts behaving differently?

Every detection was designed to answer an engineering question rather than simply produce another notification.

---

# Capabilities Built

Developed more than twenty-seven Microsoft Sentinel detections including:

• Authentication monitoring

• VPN monitoring

• Privileged role changes

• Administrative activity

• Linux authentication

• SUDO activity

• Audit logging

• Vulnerability visibility

• Infrastructure monitoring

• Host reporting

• Security dashboards

• Investigation workflows

---

# Engineering Impact

Improved engineering visibility across enterprise infrastructure.

Reduced manual investigation effort.

Standardized security monitoring.

Improved operational consistency.

Created reusable detection engineering practices supporting long-term organizational maturity.

---

# Lessons Learned

The quality of a detection is determined by the quality of the engineering question it answers.

More alerts do not improve security.

Better context improves security.

Detection engineering should reduce cognitive load rather than increase operational noise.

---

# If I Built This Again

Today I would begin with identity.

Every detection would immediately correlate:

• Identity

• Infrastructure

• Vulnerability

• Threat Intelligence

• Asset Ownership

• Attack Paths

This thinking has directly influenced the architecture of the Unified Security Operations Platform (USOP), where detections become contextual engineering decisions rather than isolated security events.

---

# Engineering Principles Demonstrated

✔ Engineer Systems, Not Tasks

✔ Reduce Cognitive Load

✔ Context Before Noise

✔ Leave Every System Better Than You Found It

✔ Build Foundations
