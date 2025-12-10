1. Goal: Achieve a "Right-First-Time" (RFT) submission rate for SME loan applications.
2. Result: Applications must be complete and compliant upon initial submission, minimizing rework.
3. Problem (Current State)                                          and                                    Solution (RFT Engine)
i. High application bounce rate due to missing/incomplete documents (KYC, Income, Business Proof)-- Digital, Rule-Based Pre-Screening Engine.
ii. Operational staff waste time manually checking eligibility and chasing paperwork-- Real-Time Validation: Checks documents and eligibility criteria instantly.
iii. Slow Time-to-Disbursement and poor customer experience (CX)-- Instant Feedback Loop: Tells applicants exactly what is missing/wrong before submission.

3. RFT Engine Core Logic
Checks: Validates KYC, Income Proof, and Business Proof integrity and completeness.
Eligibility: Screens against clear parameters (e.g., SME Classification, Industry Risk).
Outcome: Categorizes applications as Ready for Appraisal (RFT), Action Required, or Soft-Reject.

4. Repository Contents
data/: Raw dataset (Loan Application DataSet.csv) used to analyze current application bounce patterns.
docs/: Project brief (SME Loan Pre-Screen...docx) and context (Capstone Deck_HDFC.pdf).
solution/: Placeholder for the Rule Engine implementation code and logic diagrams.
presentation/: Final project presentation slides (PPT).

5. Technologies Used
Rule-Based Decision Engines (e.g., Python if-else or specialized B.R.M.S.).
Data Analysis (Pandas/Excel) for pattern identification.
OCR / Data Extraction (Future integration for document automation).
