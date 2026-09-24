# Azure Functions Cost Optimization

## Overview

Modernized an ETL process by replacing it with a lightweight microservices implementation built on Azure Functions.

This case study is a sanitized representation of professional work. Client names, source code, internal architecture, credentials, and operational details are intentionally omitted.

## Context

The existing ETL implementation supported a data-processing workflow but had a high operating cost for its workload. The goal was to reduce the cost of the process while keeping the required behavior and making the solution easier to evolve.

## Challenge

- Reduce the recurring cost of the existing data-processing implementation.
- Preserve the required workflow and integrations.
- Move toward a smaller, independently deployable architecture.
- Keep the implementation aligned with the team's Azure delivery practices.

## Solution

The ETL implementation was replaced with a set of Azure Functions-based microservices. The solution separated processing responsibilities into smaller components and used Azure-native services to support execution and integration.

The work included evaluating the existing flow, defining the replacement approach, implementing the services, and supporting their delivery through the team's cloud and CI/CD practices.

## Outcome

The approximate cost of the implementation changed from **USD 300** to **USD 0.60** for the comparable workload.

The resulting design also provided smaller deployment units and a clearer separation of processing responsibilities. The exact workload, billing period, and percentage reduction are not published because they are part of the original client context.

## Role and contribution

- Analyzed the existing ETL approach and its cost profile.
- Designed the replacement using Azure Functions and microservices principles.
- Implemented and supported the new services.
- Contributed to deployment and operational practices in Azure.

## Technologies

Azure Functions · Microsoft Azure · Microservices · ETL modernization · CI/CD

## Confidentiality

This case study intentionally excludes client identifiers, proprietary code, internal URLs, credentials, customer data, and detailed production architecture.
