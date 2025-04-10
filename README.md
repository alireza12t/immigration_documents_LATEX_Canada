# Immigration Documents LaTeX Repository

This repository contains LaTeX templates and scripts designed to assist in generating essential documents required for immigration applications, specifically tailored for study permit renewals and Post-Graduation Work Permit (PGWP) applications in Canada.

## How to Use

### General Instructions:

1. **Clone the repository:**
```bash
git clone <repository-url>
```

2. **Navigate to the specific document folder and modify parameters:**
- For proof of means documents, edit `proof_means_financial_renew_study_permit.tex`.
- For PGWP client information, edit `PGWP_Client_Information.tex`.

3. **Compile the LaTeX documents:**
```bash
pdflatex <document_name>.tex
```

4. **Ensure required PDF files (bank statements, pay stubs, etc.) are placed in the same folder or the paths are adjusted accordingly.**

## Parameter Explanations

### Proof of Means of Financial Support

| Parameter | Description |
|-----------|-------------|
| `\fullName` | Applicant's full name. |
| `\hasTA` | Boolean flag indicating if the applicant has a Teaching Assistant position. |
| `\hasRA` | Boolean flag indicating if the applicant has a Research Assistant position. |
| `\hasExternalJob` | Boolean indicating external employment status. |
| `\rentExpense` | Monthly rent expense in CAD. |
| `\groceryExpense` | Monthly grocery expenses. |
| `\transportExpense` | Monthly transportation expenses. |
| `\remainingTuition` | Outstanding tuition fees, if applicable. |
| `\oneTimeTravelExpense` | One-time travel expense for return ticket to home country. |
| `\grossSalary` | Gross monthly salary from external job. |
| `\netSalary` | Net monthly salary after deductions. |
| `\taMonthlyIncome` | Monthly income from Teaching Assistant position. |
| `\raMonthlyIncome` | Monthly income from Research Assistant position. |
| `\savingsBalance` | Current balance of savings account. |

### PGWP Client Information

| Parameter | Description |
|-----------|-------------|
| `\fullName` | Applicant's full name. |
| `\emailAddress` | Applicant's contact email. |
| `\phoneNumber` | Applicant's contact phone number. |
| `\universityName` | Name of the university attended. |
| `\programName` | Program and degree pursued. |
| `\graduationDate` | Official graduation date. |
| `\employmentStartDate` | Date of current employment start; leave blank if unemployed. |
| `\employerName` | Name of current employer; leave blank if unemployed. |
| `\caqRenewed` | Boolean flag indicating renewal status of CAQ. |
| `\studyPermitRenewed` | Boolean flag indicating renewal status of study permit. |

## File Organization

Ensure your PDFs (such as pay stubs, CAQs, permits, and bank statements) are named exactly as referenced in the LaTeX files or adjust the filenames in the LaTeX documents accordingly.

## Requirements
- **LaTeX distribution** (such as TeX Live or MiKTeX)
- **pdfLaTeX** (included with most LaTeX distributions)

## Troubleshooting
- If documents fail to compile, ensure all referenced PDFs exist and are correctly named.
- Check for any missing LaTeX packages by reviewing compilation errors.

## License
This project is provided under the MIT License. Feel free to adapt and modify it as needed for personal use.

