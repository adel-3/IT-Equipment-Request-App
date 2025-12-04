## 1\. Overview

The **IT Equipment Request Application** is ServicNow Mini Project designed to streamline and automate the process for employees to request new or replacement IT hardware (laptops, monitors, peripherals, etc.).

This application provides a user-friendly interface (likely a **Service Portal** page, based on the context of the other quiz questions) for users to select items, submit requests, and track their order status, replacing manual, email-based, or paper-based processes.

## 2\. Features

  * **Catalog Browsing:** Browse a categorized catalog of available IT equipment.
  * **Request Submission:** Easily fill out forms to submit requests, including justification and specific requirements.
  * **Automated Approval Workflow:** Requests are automatically routed to the appropriate manager or IT procurement team for approval.
  * **Status Tracking:** Users can view the real-time status (e.g., Pending Approval, Ordered, Ready for Pickup) of all their requests via a dedicated dashboard.
  * **Inventory Integration (Future):** Automatic update of inventory records upon fulfillment.

## 3\. Architecture and Technology

This application is built on the **ServiceNow Platform**.

| Component | Purpose |
| :--- | :--- |
| **Service Portal** | Provides the modern, mobile-responsive user interface for end-users to submit and track requests. |
| **Catalog Items** | Defines the specific equipment request forms and their variables. |
| **Flow Designer / Workflow** | Manages the multi-stage approval, fulfillment, and notification processes. |
| **Tables** | Stores submitted requests, line items, and approval histories (e.g., `sn_req_app_request` custom table). |


### **Next Step**

Which section of this README would you like to edit or elaborate on first?
