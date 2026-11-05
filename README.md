# Automated-Financial-Transaction-Audit-Engine-
Financial Transaction Ledger Auditor | Automated Data Pipeline
Key Features & Technical Implementation:

    Data Hygiene & Cleaning: Built automated routines to drop duplicate transaction records and impute missing monetary values (.fillna()).
    Datetime Engineering: Parsed raw timestamp strings into datetime objects and extracted transactional day-of-week patterns.
    Automated Risk Engine: Applied custom conditional logic to flag high-risk wire transfers exceeding $50,000 for compliance review.
    Object-Oriented Architecture: Encapsulated the complete cleaning, transformation, and audit workflow into a modular FinancialAuditor    Python class.
