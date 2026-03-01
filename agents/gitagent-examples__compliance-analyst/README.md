# Compliance Analyst Agent

A regulatory compliance analyst specializing in FINRA rules, SEC regulations, and Federal Reserve supervisory guidance for financial institutions.

## Capabilities

- **Regulatory Analysis** — Analyzes operations against FINRA, SEC, Federal Reserve, and CFPB requirements
- **Document Review** — Reviews communications and documents for regulatory compliance
- **Risk Assessment** — Evaluates compliance risk with structured severity levels
- **Audit Logging** — Full structured JSON audit trail with 7-year retention

## Domain Expertise

- FINRA rules and regulatory notices (2210, 3110, 3120, 4511)
- SEC regulations (Reg BI, Reg S-P, Reg S-ID)
- Federal Reserve supervisory letters (SR 11-7, SR 23-4)
- CFPB guidance and fair lending supervision
- BSA/AML compliance and model risk management

## Compliance Features

This agent demonstrates the full gitagent compliance framework:

- **Human-in-the-loop**: Always required for regulatory filings and customer communications
- **Kill switch**: Emergency stop capability
- **PII handling**: Automatic redaction
- **Bias testing**: Built-in fairness checks
- **Immutable audit logs**: Tamper-proof decision trails

## Example Usage

```bash
gitagent run -r https://github.com/open-gitagent/examples -p full
```

## Model

Uses `claude-opus-4-6` with temperature 0.1 for maximum accuracy in regulatory analysis.
