# Wms-for-ati

## Proposed Issue Tickets for ATI Waste Management System

1. **Project setup and architecture**
   - Define scope, modules, and technology stack for the ATI Waste Management System.
   - **Acceptance criteria:** architecture diagram, module list, and initial project structure approved.

2. **User authentication and role management**
   - Implement login and role-based access for Admin, Supervisor, and Operator.
   - **Acceptance criteria:** users can sign in and access only permitted screens/actions.

3. **Waste category and bin master data**
   - Create CRUD for waste categories, bin types, and disposal methods.
   - **Acceptance criteria:** admin can add/edit/delete categories and bins with validation.

4. **Waste collection entry workflow**
   - Build form/workflow to record collection events (source, category, weight, timestamp).
   - **Acceptance criteria:** entries are saved correctly and visible in history.

5. **Pickup scheduling and assignment**
   - Implement scheduler to assign pickups to staff/vehicles.
   - **Acceptance criteria:** scheduled tasks show in assignee queue with status updates.

6. **Inventory and storage tracking**
   - Track temporary storage levels, thresholds, and overflow alerts.
   - **Acceptance criteria:** system shows current storage by category and triggers alerts at limits.

7. **Compliance and disposal record management**
   - Record disposal events and compliance documents for audits.
   - **Acceptance criteria:** disposal logs are immutable and exportable for compliance review.

8. **Dashboard and reporting**
   - Build dashboard for daily/weekly/monthly waste metrics and trends.
   - **Acceptance criteria:** key KPIs and filterable reports are available and downloadable.

9. **Notification and alert system**
   - Add alerts for missed pickups, overflow risk, and compliance deadlines.
   - **Acceptance criteria:** configured alerts are delivered to target roles in-app/email.

10. **Testing, UAT, and production release**
    - Prepare test cases, perform UAT, fix defects, and release.
    - **Acceptance criteria:** critical defects closed, UAT sign-off completed, release checklist approved.
