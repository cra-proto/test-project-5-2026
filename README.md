# Test project 5

*description of the project*

**Timeframe** 2026-09-21 - 2026-12-28

## Overview

This repository was created via the **Design Assistant**.  
It contains the template files and in-scope pages needed to get started.

GitHub Pages: [https://cra-test-arc.canada.ca/test-project-5-2026](https://cra-test-arc.canada.ca/test-project-5-2026)

---
## Update procedures

Add information on how to manage your repo here.

---
## Design phase roadmap:

- [x] Initial content inventory and repo setup
- [ ] Prototype: co-design navigation and content
- [ ] SME review and accuracy check
- [ ] Validation usability testing (including accessibility review)
- [ ] Refine prototype (if required)
- [ ] Spot check usability (if required)

**Updated:**  2026-10-05

## Information Architecture
```mermaid
flowchart TD;
    node1(Canada.ca)
    node2(Canada Revenue Agency #40;CRA#41;)
    node3(Payments – CRA)
    node4(Payments to the CRA)
    node5(Make a payment – Payments to the CRA)
    node6(Payment options for the type of payment you are making – Payments to the CRA)
    node7(Questions and answers about payments to the CRA)
    node8(Pay with a debit card through the CRA's My Payment service)
    node9(Pay online with your bank or credit union – Payments to the CRA)
    node10(Pay by scheduled pre-authorized debit #40;PAD#41; through the CRA online services – Payments to the CRA)
    node11(Pay at the counter #40;teller#41; at a bank or credit union – Payments to the CRA)
    node12(Pay at your bank or credit union's ATM – Payments to the CRA)
    node13(Banana)
    node14(Pay through the mail – Payments to the CRA)
    node15(Pay through a third-party payment service provider – Payments to the CRA)
    node16(Pay at a bank or credit union through wire transfer – Payments to the CRA)
    node17(Pay in person at a Canada Post retail location – Payments to the CRA)
    node18(Due dates for amounts you owe – Payments to the CRA)
    node19(Getting debt relief under special circumstances)
    node20(Required tax instalments – Payments to the CRA)
    node21(Interest and penalties on late or incorrect payments)
    node22(Repay COVID-19 benefits)
    node23(Confirm a payment
 – Payments to the CRA)
    node24(Taxes)
    node25(Income tax)
    node26(Personal income tax)
    node27(Claiming deductions, credits, and expenses)
    node28(All deductions, credits and expenses - Personal income tax)
    node29(Line 48500 – Balance owing)
    node1 --x node2
    node2 --> node3
    node3 --> node4
    node4 --> node5
    node5 --> node6
    node5 --> node7
    node5 --> node8
    node5 --> node9
    node9 --> node10
    node5 --> node11
    node5 --> node12
    node12 --> node13
    node5 --> node14
    node5 --> node15
    node5 --> node16
    node5 --> node17
    node4 --> node18
    node4 --> node19
    node4 --> node20
    node4 --> node21
    node4 --> node22
    node4 --> node23
    node1 --> node24
    node24 --> node25
    node25 --> node26
    node26 --> node27
    node27 --> node28
    node28 --> node29

    classDef inscope stroke:#7636ab,stroke-width:3px
    class node4,node5,node6,node7,node8,node9,node10,node11,node12,node13,node14,node15,node16,node17,node18,node19,node20,node21,node22,node23,node24,node29 inscope
    classDef isnew fill:#00706f,color:#fff
    class node13 isnew
    classDef ismoved fill:#eab308,color:#000
    class node10 ismoved
```
