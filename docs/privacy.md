# Marley Health Privacy Notice

Marley Health is a self-hosted healthcare management application for Frappe and ERPNext. This notice describes the application's default data behavior. The organization operating a deployment remains the controller of the patient and business data stored in that deployment.

## Data storage

Marley Health stores patient profiles, appointments, encounters, clinical observations, laboratory records, inpatient records, rehabilitation records, insurance records, attachments, audit metadata, and related ERPNext transactions in the Frappe site selected by the operator.

The application does not transmit site data to the publisher by default. Data is sent to an external service only when the site operator explicitly configures an integration such as email, SMS, payment, telephony, insurance, or another third-party connector.

## Access and security

Access is controlled through Frappe users, roles, DocType permissions, sharing rules, and site-level authentication. Operators should grant the minimum permissions required for each role, use HTTPS, protect administrator accounts, keep dependencies updated, and maintain encrypted backups according to their own compliance obligations.

## Retention, export, and deletion

The site operator determines retention periods and is responsible for responding to requests to access, correct, export, or delete personal information. Frappe's standard export, document lifecycle, backup, and restore tools can be used subject to the operator's legal and clinical record-retention requirements.

## Licensing and support

Marley Health is distributed under the GNU General Public License v3.0. Source code, issue reporting, and the license are available in this repository. Privacy questions for a specific deployment should be directed to the organization operating that deployment.
