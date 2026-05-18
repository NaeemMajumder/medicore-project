Manage Doctors [Admin panel]
### Screen Definition
- display-doctors-table [Mandatory]
- input-search-by-name-or-specialization [Mandatory]
- button-add-new-doctor [Mandatory]
- input-name [Mandatory]
- input-email [Mandatory]
- input-phone [Mandatory]
- input-specialization [Mandatory]
- button-add-doctor [Mandatory]
- button-edit [Mandatory]
- button-delete [Mandatory]
- button-save-changes [Mandatory]
- button-cancel [Mandatory]
- modal-confirm-deletion [Mandatory]
### User Story
As an admin, I want to add, update or remove doctors so that the system has accurate and updated doctor information.
### Acceptance Criteria
- Table shows doctor name, email, phone, specialization and date added
- Admin can search by name or specialization
- All fields must be filled before adding a new doctor
- Email must be in valid format
- Phone must be valid
- Success toast notification shown after add, update or delete
- Confirm deletion modal prevents accidental deletions
- Doctor Added toast shown in green after successful add
- Doctor Deleted toast shown in red after successful delete
- Doctor Data Updated toast shown in green after successful update
**Status: Implemented**