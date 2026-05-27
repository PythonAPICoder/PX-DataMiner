# Cisco PX Cloud DataMiner


## Overview

PX DataMiner is a Python-based automation tool designed to simplify large-scale Cisco Partner Experience (PX) data collection, reporting, and analysis.

It helps partners, customer success teams, and support engineers automate the retrieval of customer and operational data across multiple environments, replacing repetitive manual API queries with scalable, repeatable workflows.

By integrating OAuth authentication, API automation, structured exports, and configurable reporting, PX DataMiner transforms complex data gathering into actionable business intelligence.

---

## Disclaimer

PX DataMiner is an independent automation solution and is not an officially supported Cisco product.

Users are responsible for:

* API credential management
* Responsible rate limit usage
* Compliance with Cisco API policies
* Internal governance requirements

---
## Key Benefits

* Automates large-scale PX data extraction across customers and endpoints
* Reduces manual reporting effort and operational overhead
* Supports structured exports for business analysis (CSV, XLSX, JSON, TSV)
* Improves consistency through repeatable automation
* Enables customer success teams and partners to identify insights faster
* Supports scalable operational workflows for internal and external stakeholders
* Simplifies ongoing reporting, auditing, and data validation

---

## Business Value

PX DataMiner helps organizations:

### Partners

* Accelerate customer data collection
* Improve support readiness
* Standardize recurring operational reports
* Increase efficiency for partner support teams

### Customers

* Gain faster access to actionable environment data
* Improve visibility into operational metrics
* Reduce delays caused by manual reporting processes
* Support better customer success outcomes

---

## Core Features

* OAuth-secured API authentication
* Automated endpoint discovery and querying
* Configurable customer targeting
* Pagination handling
* Rate limiting and retry logic
* Multi-format export support
* Summary reporting
* Modular configuration
* Scalable thread-based execution

---

## Technical Stack

* Python 3.10+
* Requests
* Pandas
* OpenPyXL
* PyYAML
* REST APIs
* OAuth2

---

## Use Cases

* Partner operational reporting
* Customer success analytics
* API-driven data mining
* Support case preparation
* Cross-customer reporting
* Internal workflow automation
* Data validation and auditing

---

## Why PX DataMiner

Manual API data gathering can be:

* Slow
* Inconsistent
* Error-prone
* Difficult to scale

PX DataMiner solves these challenges by delivering:

### Faster Execution

Automates hundreds of repetitive tasks.

### Better Consistency

Standardized outputs across all customers.

### Greater Scalability

Supports multi-customer enterprise operations.

### Operational Efficiency

Frees engineers and teams to focus on analysis instead of data collection.

---

## Installation

```bash
pip install requests pandas openpyxl pyyaml
```

---

## Basic Setup

1. Clone the repository:

```bash
git clone https://github.com/PythonAPICoder/PX-DataMiner.git
```

2. Configure your API credentials in `config.ini`

3. Run:

```bash
python PX_DataMiner.py
```

---

## Output

PX DataMiner generates structured output for:

* Customer summaries
* API endpoint data
* CSV reports
* Excel analysis
* JSON exports
* Error logs
* Audit-ready execution history

---

## Ideal Users

* Cisco Partners
* Customer Success Engineers
* Support Teams
* Automation Engineers
* Operational Analysts
* Technical Account Teams

---


## Bottom Line

PX DataMiner is an enterprise workflow automation solution that helps partners and customers:

### Save Time

### Reduce Manual Work

### Improve Reporting Accuracy

### Scale Operational Intelligence

It transforms API complexity into practical business value through automation.

