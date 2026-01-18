## Key Design Principles

- Security-first: No direct enrollment by a single actor

- Auditability: Every action logged and traceable

- Operational simplicity: Minimal steps for branch staff

- Same-day enablement: Eliminate dependency on delayed sync cycles

## End-to-End Flow

### 1. Customer Submits Documents

- Account Opening Form (AOF)

- USSD request letter

### 2. CSO Initiates Request (Maker)

- CSO logs into USSDPortal

- Uploads customer documents

- Enters required enrollment metadata

- Submits enrollment request

### 3. Authorization Stage (Checker)

- Request is automatically routed to the Service Manager

- Service Manager reviews submitted details and documents

- Approves or rejects the request

### 4. Backend Enrollment

Upon approval, the system triggers automated USSD enrollment

Customer becomes eligible for USSD usage the same day

### 5. Audit & Logging

- All actions are timestamped

- Maker and checker identities are recorded

- Documents and decisions are retained for compliance

## Security & Compliance Controls

- Role-based access (CSO vs Service Manager)

- Maker–checker enforcement

- Immutable audit logs

- Document retention for regulatory review

- No direct database access from branch users







