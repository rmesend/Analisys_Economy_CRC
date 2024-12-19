# Breadcrumbs: Analysis_Economy_CRC

**Breadcrumbs: Analysis_Economy_CRC** is a data exploration and analysis project focused on economic indicators at the canton and province levels within a given year. This repository provides scripts, notebooks, and documentation to understand and utilize the provided dataset. The dataset includes key variables related to economic activity, business size, payroll information, and import/export data, structured by administrative divisions such as provinces and cantons.

## Table of Contents
- [Overview](#overview)
- [Data Description](#data-description)
- [Data Fields](#data-fields)
- [Getting Started](#getting-started)
- [Repository Structure](#repository-structure)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Overview
This project aims to facilitate an understanding of regional economic metrics. The dataset includes indicators like number of workers, payroll, income, exports, imports, and other parameters that provide a comprehensive snapshot of economic conditions. By analyzing these data, one can identify trends, perform comparative analysis between different cantons or provinces, and potentially guide policy-making or economic planning.

## Data Description
The dataset at the heart of this repository is structured to reflect annual economic activity. Each record corresponds to a particular administrative unit (canton) and includes details about business characteristics, workforce, and financial metrics.

Typical use cases for this data include:
- Conducting time-series analysis of economic growth.
- Comparing workforce and payroll trends across regions.
- Examining the relationship between business size and income.
- Evaluating the impact of exports and imports on local economies.
- Identifying correlations between classification codes (CIIU) and economic performance indicators.

## Data Fields
The primary fields in the dataset are as follows:

- **year**: The year of the observation.
- **size**: A classification of business size (e.g., small, medium, large).
- **CIIU_class**: The CIIU (International Standard Industrial Classification of All Economic Activities) class code.
- **province_code_x**: Code representing the province (source field).
- **canton_code**: Code representing the canton.
- **UJ_quantity**: Quantity of business units (Establishments).
- **workers_number**: The number of employees/workers associated with the unit.
- **payroll**: Total payroll amount associated with the workers.
- **income**: Total income reported by the business units.
- **exports**: Total exports value.
- **imports**: Total imports value.
- **province**: The name of the province.
- **province_code_y**: Code representing the province (alternative or merged source).
- **canton**: The name of the canton.

**Note**: Fields like `province_code_x` and `province_code_y` may be redundant or derived from different sources. They might need cleaning or merging steps during analysis.

## Getting Started
1. **Clone the repository**:
   ```bash
   
   git clone https://github.com/rmesend/Analisys_Economy_CRC.git
