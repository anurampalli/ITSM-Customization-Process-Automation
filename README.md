# ITSM Customization & Process Automation

## Overview

This project demonstrates how I configured SLAs, ACLs, and REST APIs in ServiceNow
to automate ITSM workflows.

## Features

- SLA definition for Incident & Request
- Access Control Lists (ACLs) for role-based security
- GlideRecord scripts for automated priority updates
- Catalog Item Script and Catalog Item UI Policy
- Scripted REST API for fetching P1 incidents

## Screenshots

![SLA Definition](screenshots/sla)
![Scripted REST API](screenshots/scripted_rest_api)
![Catalog Script and UI Policy](screenshots/scripted_rest_api)
![Scripts - Background](screenshots/background_script)
![ACL](screenshots/acl)

## How to Import

1. Download the update set from `/updateset/sys_remote_update_set_293d610483672a107ffb1630ceaad377.xml`
2. Navigate to **System Update Sets > Retrieved Update Sets** in ServiceNow.
3. Import and Preview before committing.
