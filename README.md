# MediBook Clinic — Manual QA Testing

## Project Overview

This repository contains a complete manual QA testing project for the **MediBook Clinic** practice application on QATools Playground.

The goal of the project was to validate the main clinic user journey end to end: discovering doctors, filtering/searching by specialty, reviewing doctor details, selecting an appointment date and time, validating required patient information, completing a dummy booking, reviewing the saved appointment, refreshing the page, cancelling the appointment, removing it, and verifying the final empty state.

**Application:** QATools Playground — MediBook Clinic  
**URL:** https://playground.qatools.dev/clinic  
**Testing Type:** Manual Testing  
**Execution Date:** 20 Nov 2026

## Test Coverage

The defined project scope contains **24 planned test cases**, and all 24 were executed.

| Metric | Result |
|---|---:|
| Total Test Cases | 24 |
| Passed | 24 |
| Failed | 0 |
| Blocked | 0 |
| Not Run | 0 |
| Pass Rate | 100% |

### Covered Areas

- Home page load and navigation
- Find a Doctor navigation
- My Appointments navigation
- All 8 specialty filters
- Doctor card content
- Doctor profile navigation
- Doctor data consistency
- Positive doctor search
- Negative/no-results search
- Booking flow start
- Date and time-slot selection
- Required-field validation
- Booking data consistency
- Successful dummy appointment booking
- Appointment confirmation
- Appointment persistence after refresh
- Appointment cancellation
- Cancelled appointment removal
- Empty appointments state
- Active navigation state
- Home statistics
- Top-rated doctors section

## Key End-to-End Scenario

A full dummy booking flow was completed using fictional test data:

1. Opened **Dr. Vikram Shah** profile.
2. Started the appointment booking flow.
3. Selected **Fri, Nov 20 — 15:00**.
4. Verified required patient-detail validation.
5. Used fictional patient data only.
6. Completed the appointment successfully.
7. Verified the booking in **My appointments**.
8. Refreshed and confirmed the appointment persisted.
9. Cancelled the appointment.
10. Removed the cancelled appointment.
11. Verified the final **No appointments yet** empty state.

No real patient, medical, or payment information was used.

## Test Artifacts

- `MediBook_Clinic_Manual_QA_Test_Cases.xlsx` — master test-case tracker and execution results
- `TEST_PLAN.md` — scope, approach, entry/exit criteria
- `TEST_EXECUTION_REPORT.md` — final execution summary
- `BUG_REPORTS.md` — defect summary
- `screenshots/` — selected execution evidence

## Defect Summary

No confirmed defects were identified within the executed scope.

This does **not** mean the application is defect-free; it means no reproducible defect was confirmed during these 24 planned manual test cases.

## Tools

- Browser-based manual testing
- Microsoft Excel / spreadsheet tracking
- GitHub for portfolio documentation

## QA Skills Demonstrated

- Test scenario design
- Positive and negative testing
- UI and navigation testing
- Search and filter testing
- Data consistency validation
- Required-field validation
- End-to-end workflow testing
- State persistence testing
- Cancellation workflow testing
- Test evidence collection
- Test execution reporting

## Repository Structure

```text
MediBook-Clinic-Manual-Testing/
├── README.md
├── TEST_PLAN.md
├── TEST_EXECUTION_REPORT.md
├── BUG_REPORTS.md
├── MediBook_Clinic_Manual_QA_Test_Cases.xlsx
└── screenshots/
```

## Notes

This project was executed against a demo/practice application. All appointment and patient data used during testing was fictional and created only for QA purposes.
