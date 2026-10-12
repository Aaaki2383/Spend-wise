# SpendWise — Desktop Finance Dashboard

## 1. Project Overview

**Project type:** UI/UX Design  
**Platform:** Desktop web application  
**Role:** UI/UX Designer  
**Tools:** Figma  
**Design approach:** Existing design system with custom components

SpendWise is a personal finance dashboard concept designed to help users understand their spending, manage monthly budgets, review transactions, and track savings goals in one place.

The goal is to present financial information in a clear, organized interface that reduces the effort required to understand where money goes and how spending aligns with personal goals.

*This is a portfolio concept, not a production financial product.*

## 2. Problem Statement

Personal finance information can become difficult to manage when transactions, spending limits, and savings goals are spread across different views or tools. Users may have difficulty identifying spending patterns, understanding how much budget remains, or determining whether they are making progress toward their financial goals.

SpendWise explores how a centralized desktop dashboard can make this information easier to understand and act on.

## 3. Design Goals

- Present essential financial information at a glance.
- Make transaction history easy to search and review.
- Help users understand budget limits and remaining funds.
- Visualize savings progress clearly.
- Maintain consistency across screens through reusable components.
- Design an accessible, responsive-ready interface.

## 4. Target Users

The initial concept is intended for individuals who want a simple way to review everyday spending, organize monthly budgets, and monitor savings goals.

Potential users include students, early-career professionals, and people managing several spending categories.

These are assumed user groups for the concept and should be validated through research before making stronger claims about user needs.

## 5. Design System Used

**Starting system: Material Design 3**

I used Material Design 3 as the foundation for the interface, drawing on its design conventions for typography, color, buttons, form controls, component states, and spacing.

### What the system gave me

- Established patterns for buttons, fields, navigation, and interactive states.
- A consistent approach to typography and visual hierarchy.
- Reusable component conventions that reduce inconsistency.
- Guidance for interaction feedback and component behavior.
- A foundation for building and maintaining related screens.

Using an established system helped me focus on the financial dashboard's information hierarchy and user workflows rather than inventing every interface pattern from scratch.

## 6. What the System Did Not Give Me

The general design system did not fully address the specific requirements of a personal finance dashboard.

### Finance-specific components

Generic cards and progress indicators did not completely cover budget status, spending summaries, savings goals, and financial data presentation.

### Dense transaction tables

Transaction history required a specialized layout for merchant names, dates, categories, transaction types, and monetary values.

### Financial status communication

Budget warnings needed clear visual distinctions between normal spending, approaching a limit, and exceeding a limit. Color alone would not provide sufficient clarity.

### Dashboard information hierarchy

The system provided general layout conventions, but it did not determine which financial metrics should receive the most attention or how they should relate to each other.

## 7. How I Addressed the Gaps

I retained established interaction patterns and created additional components for the product's specific needs.

- **Summary cards:** Created reusable cards for total balance, income, and expenses.
- **Budget indicators:** Designed progress states for normal, near-limit, and over-budget conditions.
- **Transaction rows:** Organized transaction details into a consistent, scannable layout.
- **Savings goal cards:** Added target amounts, progress indicators, and target dates.
- **Financial status labels:** Used descriptive text and icons alongside color to communicate status.
- **Consistent component structure:** Used Auto Layout, reusable components, and variants to keep the interface maintainable.

The intention was to extend the design system only where necessary while preserving its underlying conventions.

## 8. Key Screens

### Overview Dashboard
Provides a summary of balances, income, expenses, spending trends, category breakdowns, and recent transactions.

### Transactions
Allows users to review transaction history and locate entries using search and filters.

### Budgets
Displays monthly spending limits, amounts spent, remaining funds, and budget status.

### Savings Goals
Shows target amounts, current savings, progress, and target dates.

### Add Transaction
Provides a focused form for entering transaction details and receiving validation feedback.

## 9. Accessibility and Usability Considerations

The design should be evaluated against the following considerations:

- Maintain readable text sizes and sufficient contrast.
- Use descriptive labels for form fields and actions.
- Avoid relying on color alone to communicate financial status.
- Provide visible focus states for keyboard navigation.
- Use consistent navigation and predictable interactions.
- Make monetary values and transaction details easy to scan.
- Provide clear validation and confirmation feedback.

These are design objectives to verify during implementation and testing, not claims of completed accessibility certification.

## 10. Prototype and Evaluation Plan

The Figma prototype will demonstrate navigation between the main dashboard sections, transaction search and filtering concepts, opening the add-transaction modal, and editing budget or savings information.

A proposed usability evaluation would ask participants to:

1. Identify how much they spent during the month.
2. Find a specific transaction.
3. Determine how much remains in a selected budget.
4. Locate a savings goal and interpret its progress.
5. Complete the add-transaction flow.

Evaluation would focus on task completion, errors, navigation clarity, and participant feedback.

Results and design changes should be documented after testing is actually conducted.

## 11. Reflection

This project explores the balance between consistency and product-specific design requirements. An existing design system provides a strong foundation, but applying it effectively also requires identifying where generic components fall short.

The key design decision is to preserve familiar interaction patterns while introducing specialized components for financial information, making the dashboard more appropriate for its intended workflows without creating unnecessary visual inconsistency.

## 12. Future Improvements

- Conduct user interviews and usability testing.
- Validate the information hierarchy using research findings.
- Test responsive layouts for tablet and smaller screens.
- Improve keyboard accessibility and contrast where necessary.
- Explore data visualization alternatives for different user needs.
- Refine components based on evaluation results.
