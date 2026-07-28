# Threat Emulation & Flows (`.afb`)

## Overview
This repository contains machine-readable Attack Flow Builder (`.afb`) artifacts, threat emulation scenarios, and structured adversary campaign models based on STIX 2.1 standards. It serves as a centralized collection for mapping threat actor techniques, tracking attack chains, and supporting detection engineering workflows.

## Repository Structure
* **`campaigns/`**
  * Contains structured `.afb` JSON files and their supporting png files mapping specific threat group campaigns, attack flows, and tactics.
* **`documentation/`**
  * Overview guides, mapping matrices, and integration notes for visualizing and testing attack paths using the Attack Flow Builder framework.

## Usage
1. Import `.afb` files directly into the **Attack Flow Builder** interface to visualize, validate, or modify adversary behavioral models.
2. Cross-reference the mapped techniques with your telemetry and SIEM logging rules to verify defensive coverage and alert detection logic.
