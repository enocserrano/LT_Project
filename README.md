# Proyect-LT
PoC legal intake y risk

##Problem
Legal requests often arrive through multiple channels, without clear priority or proper context, wich leads to poorly managed legal risk.
##PoC Target
To classify legal request since intake stage and assign an explainable risk level.

##Scope
-Personal Proof of Concept
-No real data
-Not Advanced Machine Learning
-focused on explainability and low cost

##This not
-A product
-A productive system
-A definitive solution

## Risk Classification Logic (Initial)

### Request Types
-Contract
-Authority Request
-Customer Issue
-Litigation
-Compliance

### Risk Levels
-Low
-Medium
-High

### Initial Risk Rules
-Authority request (regulators, courts, goverment entities): +5
-Litigation-related terms (lawsuit, claim, summons): +7
-Explicit deadlines (24h, 48h, immediate): +3
-Financial exposure mentioned: +4
-Reputational risk indicators: +3

### Risk Thresholds
-0-3 --> Low
-4-6 --> Medium
-7+ --> High


