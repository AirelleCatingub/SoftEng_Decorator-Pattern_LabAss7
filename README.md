# SoftEng_Decorator-Pattern_LabAss7
Cimb with Decorator Pattern

## Problem Statement

CIMB is a digital bank that offers GSave and UpSave savings accounts. As with a typical Savings Account, it contains `accountNumber`, `accountName`, and a `balance` for that account.

- **Standard Savings Account**  
  Interest rate: **1%**  
  Benefits: **"Standard Savings Account"**

- **GSave Account**  
  Interest rate: **2.5%**  
  Benefits: Standard Savings Account benefits **+ GCash Transfer**

- **UpSave Account**  
  Interest rate: **4.0%**  
  Benefits: Standard Savings Account benefits **+ with Insurance**

The task is to implement this system using the **Decorator Pattern** so that enhanced features (higher interest rates and additional benefits) can be dynamically added to a base `SavingsAccount` without modifying its core structure.

## Requirements

- Implement the **Decorator Pattern** exactly as specified.
- `BankAccountDecorator` must be an **interface**.
- All classes must provide the following methods (no additional public methods allowed except setters/getters):
  1. `showAccountType()` – Returns "Savings Account", "GSave", or "UpSave"
  2. `getInterestRate()` – Returns the corresponding interest rate as a double (1.0, 2.5, or 4.0)
  3. `getBalance()` – Returns the current balance
  4. `showBenefits()` – Returns the appropriate benefits string
  5. `computeBalanceWithInterest()` – Returns new balance after applying interest
  6. `showInfo()` – Returns formatted string containing account number, name, and balance
- The `Cimb.java` main class must contain **only** the provided code (package declaration allowed) and produce the correct output.
