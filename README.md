# Odoo Loyalty Module Reengineering

This repository contains our reengineering work on the **Odoo loyalty and sale_loyalty modules**, undertaken as part of the *Software Reengineering* course at the **University of Antwerp**. Our goal was to overcome specific limitations in the existing Odoo loyalty system by improving the flexibility and functionality of loyalty rule creation.

> 📄 For a complete and detailed explanation of our analysis, decisions, and implementation process, refer to the official report: [**[SFTW] Odoo Loyalty Reengineering**](./[SFTW]%20Odoo%20Loyalty%20Reengineering.md)


---

## 📚 Table of Contents

- [Odoo Loyalty Module Enhancement](#Odoo-Loyalty-Module-Enhancement)
- [Tool Analysis](#tool-analysis)
- [Installation](#installation)
- [License](#license)
- [Credits](#credits)

Reference Material from Odoo
- [Odoo](#odoo)
- [Getting Started with Odoo](#getting-started-with-odoo)


---

## Odoo Loyalty Module Enhancement

This project modernizes the core logic of Odoo’s loyalty module by introducing multi‑category support and configurable logical conditions for point application—features previously limited to a single category per rule. Vendors can now define reward schemes that:

- Apply points when **either** of multiple product categories is present in an order.  
- Apply points only when **all** specified categories are included.  

Key improvements include:

- ✅ **Multiple product category support** per loyalty rule  
- ✅ **Logical condition configuration** (`AND` / `OR`) for precise reward logic  
- ✅ **Refactored codebase** for enhanced maintainability and extensibility  
- ✅ **Comprehensive documentation** to streamline onboarding and future contributions  

## 🛠 Tool Analysis

To ensure a systematic and maintainable reengineering effort, we used several analysis tools across five areas:

1. **Code Metrics & Visualization**  
   - Analyzed code structure and complexity.
2. **Code Duplication Detection**  
   - Identified redundant segments for refactoring.
3. **Refactoring Opportunities**  
   - Improved long or complex methods for maintainability.
4. **Test Coverage Evaluation**  
   - Assessed and enhanced test effectiveness.
5. **Repository Mining**  
   - Identified key maintainers and contributors for potential collaboration.

## ⚙️ Installation

1. Set up Odoo by following the official installation guide available in the [Getting Started](https://www.odoo.com/documentation/) section of the Odoo documentation.
2. Clone or copy this repository and integrate the modified loyalty module files into your Odoo custom add-ons directory.
3. Restart the Odoo server and update the app list.
4. Install or upgrade the `sale_loyalty` module via the Odoo interface to apply the enhancements.

> 💡 Note: Ensure that dependencies for the `sale_loyalty` module are properly installed before proceeding.
## 📜 License
This project is for educational and research purposes only. Please refer to individual file headers or model licenses as applicable.

## 👥 Credits


Developed by students of the University of Antwerp for the Software Reengineering course.

Pablo de Vicente Abad - Tool Analysis & Technical Reporting

Elias Sarikasis - Development & Testing

Serge Demeyer, Mutlu Beyazit, Onur Kilincceker - Academic Guidance

----

[![Build Status](https://runbot.odoo.com/runbot/badge/flat/1/master.svg)](https://runbot.odoo.com/runbot)
[![Tech Doc](https://img.shields.io/badge/master-docs-875A7B.svg?style=flat&colorA=8F8F8F)](https://www.odoo.com/documentation/master)
[![Help](https://img.shields.io/badge/master-help-875A7B.svg?style=flat&colorA=8F8F8F)](https://www.odoo.com/forum/help-1)
[![Nightly Builds](https://img.shields.io/badge/master-nightly-875A7B.svg?style=flat&colorA=8F8F8F)](https://nightly.odoo.com/)

## Odoo
----

Odoo is a suite of web based open source business apps.

The main Odoo Apps include an <a href="https://www.odoo.com/page/crm">Open Source CRM</a>,
<a href="https://www.odoo.com/app/website">Website Builder</a>,
<a href="https://www.odoo.com/app/ecommerce">eCommerce</a>,
<a href="https://www.odoo.com/app/inventory">Warehouse Management</a>,
<a href="https://www.odoo.com/app/project">Project Management</a>,
<a href="https://www.odoo.com/app/accounting">Billing &amp; Accounting</a>,
<a href="https://www.odoo.com/app/point-of-sale-shop">Point of Sale</a>,
<a href="https://www.odoo.com/app/employees">Human Resources</a>,
<a href="https://www.odoo.com/app/social-marketing">Marketing</a>,
<a href="https://www.odoo.com/app/manufacturing">Manufacturing</a>,
<a href="https://www.odoo.com/">...</a>

Odoo Apps can be used as stand-alone applications, but they also integrate seamlessly so you get
a full-featured <a href="https://www.odoo.com">Open Source ERP</a> when you install several Apps.

## Getting started with Odoo
-------------------------

For a standard installation please follow the <a href="https://www.odoo.com/documentation/master/administration/install/install.html">Setup instructions</a>
from the documentation.

To learn the software, we recommend the <a href="https://www.odoo.com/slides">Odoo eLearning</a>, or <a href="https://www.odoo.com/page/scale-up-business-game">Scale-up</a>, the <a href="https://www.odoo.com/page/scale-up-business-game">business game</a>. Developers can start with <a href="https://www.odoo.com/documentation/master/developer/howtos.html">the developer tutorials</a>
