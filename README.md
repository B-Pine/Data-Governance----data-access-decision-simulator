# Data Access Decision Simulator

**Name:** Innocent BUGINGO  
**Module:** Data Governance & Integrity  
**Company:** EduConnect · Applied under Rwanda's Law No 058/2021 relating to the protection of personal data and privacy  

---

## Request 1: Marketing Campaign

| Field | Details |
|-------|---------|
| **Request** | Sarah Owusu (Marketing Manager) wants the full student database (names, emails, phone numbers, enrollments) for a referral campaign. |
| **Decision** | **Conditional Approval** |
| **Lifecycle Stage** | **Use** |
| **Justification** | Sarah has INTERNAL access, but emails and phone numbers are CONFIDENTIAL, so a full export breaks least privilege. Data may only be used for the purpose it was collected for (Art. 42), and students can object to direct marketing (Art. 19). |
| **Action Steps** | 1. Do not export the full database.<br>2. Send the campaign through the email tool, only to students who opted in to marketing, with an unsubscribe link.<br>3. Share no phone numbers; give Sarah only INTERNAL data (names, enrollment counts).<br>4. Make access time-limited and logged.<br>5. Get sign-off from the Data Protection Officer and the data owner before launch. |

## Request 2: Analytics Partnership

| Field | Details |
|-------|---------|
| **Request** | David Mensah (Head of Product) wants US-based DataInsights Inc. to access the AWS database directly. Login credentials are attached to the ticket. |
| **Decision** | **Deny** (as requested) |
| **Lifecycle Stage** | **Share** |
| **Justification** | Student profiles are CONFIDENTIAL. Sending them to a US company is a transfer outside Rwanda, allowed only with NCSA authorisation, student consent or another Art. 48 ground, plus a written contract (Art. 49). Sharing credentials in a ticket breaks least privilege and security duties (Art. 47). Unlawful transfer is an offence, with fines up to 5% of annual turnover (Art. 62). |
| **Action Steps** | 1. Rotate the shared credentials now and log it as a security incident.<br>2. Tell David access is denied until compliance is in place.<br>3. Have the DPO and Legal run a data protection impact assessment (Art. 38).<br>4. Sign a data transfer contract and obtain NCSA authorisation.<br>5. If approved, share only anonymised, aggregated activity logs through a controlled export. No profiles, no database access. |

## Request 3: Archive & Deletion

| Field | Details |
|-------|---------|
| **Request** | Comfort Asante (Support Lead) asks how to handle James Boateng's request to delete his account and all his data. His account is inactive with no pending payments. |
| **Decision** | **Approve** (fulfil the request) |
| **Lifecycle Stage** | **Destroy** |
| **Justification** | Law 058/2021 gives students the right to erasure. James has no open obligations, so there is no longer a purpose for keeping his data (Art. 42). Only records the law requires, such as payment records for tax, may be kept under the legal-obligation basis (Art. 46). |
| **Action Steps** | 1. Verify James's identity and log the request.<br>2. Delete his profile, contact details, grades and activity from all systems, backups and third-party tools.<br>3. Keep only legally required payment records, with restricted access, and delete them when the retention period ends.<br>4. Confirm the deletion to James in writing, saying what was kept and why.<br>5. Copy the DPO on the case for the record. |
