---
title: Zoho CRM
description: Documentation for the Zoho CRM node in n8n, a workflow automation platform. Includes details of operations and configuration, and links to examples and credentials information.
---

# Zoho CRM

The Zoho CRM node allows you to automate work in Zoho CRM, and integrate Zoho CRM with other applications. n8n has built-in support for a wide range of Zoho CRM features, including creating and deleting accounts, contacts, and deals. 

On this page, you'll find a list of operations the Zoho CRM node supports and links to more resources.

!!! note "Credentials"
    Refer to [Zoho CRM credentials](/integrations/builtin/credentials/zoho/) for guidance on setting up authentication. 

!!! note "Examples and templates"
    For usage examples and templates to help you get started, take a look at n8n's [Zoho CRM integrations](https://n8n.io/integrations/zoho-crm/){:target="_blank" .external-link} list.


## Basic Operations

* Account
    * Create an account
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete an account
    * Get an account
    * Get all accounts
    * Update an account
* Contact
    * Create a contact
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a contact
    * Get a contact
    * Get all contacts
    * Update a contact
* Deal
    * Create a deal
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a contact
    * Get a contact
    * Get all contacts
    * Update a contact
* Invoice
    * Create an invoice
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete an invoice
    * Get an invoice
    * Get all invoices
    * Update an invoice
* Lead
    * Create a lead
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a lead
    * Get a lead
    * Get all leads
    * Get lead fields
    * Update a lead
* Product
    * Create a product
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a product
    * Get a product
    * Get all products
    * Update a product
* Purchase Order
    * Create a purchase order
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a purchase order
    * Get a purchase order
    * Get all purchase orders
    * Update a purchase order
* Quote
    * Create a quote
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a quote
    * Get a quote
    * Get all quotes
    * Update a quote
* Sales Order
    * Create a sales order
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a sales order
    * Get a sales order
    * Get all sales orders
    * Update a sales order
* Vendor
    * Create a vendor
    * Create a new record, or update the current one if it already exists (upsert)
    * Delete a vendor
    * Get a vendor
    * Get all vendors
    * Update a vendor

## Example Usage

This workflow allows you to get the data of all leads from Zoho CRM. You can also find the [workflow](https://n8n.io/workflows/552) on the website. This example usage workflow would use the following two nodes.
- [Start](/integrations/builtin/core-nodes/n8n-nodes-base.start/)
- [Zoho CRM]()

The final workflow should look like the following image.

![A workflow with the Zoho CRM node](/_images/integrations/builtin/app-nodes/zohocrm/workflow.png)

### 1. Start node

The start node exists by default when you create a new workflow.

### 2. Zoho CRM node

1. First of all, you'll have to enter credentials for the Zoho CRM node. You can find out how to do that [here](/integrations/builtin/credentials/zoho/).
2. Select the 'Get All' option from the *Operation* dropdown list.
3. Click on *Execute Node* to run the workflow.

