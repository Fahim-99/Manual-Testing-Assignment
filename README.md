# Project Title: EasyPay Mobile Financial Services App

Welcome to the EasyPay Mobile Financial Services (MFS) App documentation. EasyPay allows customers to conveniently pay any merchant or utility bill, with unique features such as cashback rewards and loan facilities. This document outlines the key functionalities, acceptance criteria, and processes for the EasyPay app.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
  - [Payment and Service Charges](#payment-and-service-charges)
  - [Cashback Rewards](#cashback-rewards)
  - [Loan Facility](#loan-facility)
- [Acceptance Criteria](#acceptance-criteria)
- [Test Cases](#test-cases)
- [Bug Reports](#bug-reports)


## Overview

EasyPay is a comprehensive mobile financial services app that offers customers the ability to pay merchants and utility bills with ease. The app includes features like service charges, cashback rewards based on transaction volumes, and loan facilities with flexible repayment options.

## Features

### Payment and Service Charges

- For each payment made through EasyPay, a 1% service charge is deducted from the customer's balance.
- The minimum transaction fee for any payment is 5 tk.

### Cashback Rewards

- Customers receive a 20% cashback for any subsequent payments after they have made transactions totaling 5000 tk for the month, up to an additional 5000 tk.
- If the customer's transactions total 10000 tk or more for the month, they receive a maximum cashback of 30% on further payments.

**Examples:**
- If a customer pays 5000 tk, they will receive a 1000 tk cashback.
- If a customer pays 10000 tk or more, they will receive a 3000 tk cashback.

### Loan Facility

- Customers with a balance of less than 100 tk can apply for a loan of up to 20000 tk.
- If the loan is repaid within 30 days from the loan initiation date, no interest is charged.
- If repayment is not completed within 30 days, a daily interest rate of 1.8% is applied using compound interest on the remaining amount.
- Customers who have already repaid 50% of their existing loan are eligible to apply for another loan.

## Acceptance Criteria

The `Acceptance_Criteria.xlsx` file outlines the conditions that must be met for each feature of the EasyPay app to be considered complete. Each criterion ensures that all project requirements are met satisfactorily.

### Columns
- **Feature**: The specific feature being evaluated.
- **Criteria**: The conditions that must be fulfilled.
- **Status**: Current status (e.g., Met, Not Met, In Progress).
- **Comments**: Additional notes or comments.

[Acceptance Criteria Example](https://docs.google.com/document/d/1b8lT7XqcO9tPj592tIuMNP-eW2QLCUkrONQdR83nh_w/edit?tab=t.0)

## Test Cases

The `Test_Cases.xlsx` file contains all the test cases designed to verify the functionality of the EasyPay app. Each test case includes detailed steps, expected results, and actual results.

### Columns
- **Test Case ID**: Unique identifier for the test case.
- **Title**: A brief title for the test case.
- **Description**: Detailed description of the test case.
- **Steps**: The steps to execute the test.
- **Expected Result**: The expected outcome of the test.
- **Actual Result**: The actual outcome of the test.
- **Status**: The current status of the test case (e.g., Pass, Fail, In Progress).
- **Comments**: Any additional notes or comments.
[ Test Cases Format](https://docs.google.com/spreadsheets/d/1SCvqYnEjzJq-mFIugtWVjaCBjvol-VNzlPRY5KIsIG8/edit?gid=0#gid=0)

## Bug Reports

The `Bug_Reports.xlsx` file logs all identified bugs, providing detailed information for each bug. This helps in tracking the progress of bug resolution and ensures accountability.

### Columns
- **ID**: Unique identifier for the bug.
- **Description**: A brief description of the bug.
- **Steps to Reproduce**: Necessary steps for reproduce
- **Issue Type**: Indicate the issue type(e.g., improvement/ bug)
- **Priority**: Priority for reproduction(e.g., High, Medium )
- **Severity**: The impact level of the bug (e.g., Major, Critical).
- **Actual Result**: What it shows.
- **Expected Result**: What need to be shows.
- **Attachment**: Proven file of testing.

[ Bug Reports Example](https://docs.google.com/spreadsheets/d/17wf8uT834wsgMRdRVWuLSg_33LlGig3tkNkJtDeDYaY/edit?gid=0#gid=0)



