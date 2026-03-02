---
title: Order Form
version: 0.1.0
effective_date: DD MMMM YYYY
order_id: ""
client_name: "[CLIENT]"
client_registration_no: "[CLIENT_REGISTRATION_NO]"
client_address: "[CLIENT_ADDRESS]"
provider_name: "[PROVIDER]"
provider_registration_no: "[PROVIDER_REGISTRATION_NO]"
provider_address: "[PROVIDER_ADDRESS]"
subcontractor_agreement_date: ""
enterprise_agreement_date: ""
specific_modifications_and_overrides: |
   1. None
---
**PARTIES INFORMATION**

| **Order Reference** | ${ORDER_ID} |
| - | - |
| **Client** | ${CLIENT_NAME} (Registration No. ${CLIENT_REGISTRATION_NO}) ${CLIENT_ADDRESS} |
| **Provider** | ${PROVIDER_NAME} (Registration No. ${PROVIDER_REGISTRATION_NO}) ${PROVIDER_ADDRESS} |
| **Date** | ${EFFECTIVE_DATE} |


**INCORPORATED TERMS**

This Order Form is issued pursuant to, and is governed by, the following documents (collectively, the "Agreement"). If the documents conflict, the following order of precedence applies:

1. This Order Form including the:

   a. Specific Modifications And Overrides

   b. Appendices

{% if SUBCONTRACTOR_AGREEMENT_DATE %}2. Subcontractor Agreement  (if any) entered between Prime and Provider on ${SUBCONTRACTOR_AGREEMENT_DATE}{% endif %}

{% if ENTERPRISE_AGREEMENT_DATE %}3. Enterprise Agreement  (if any) entered between Prime and Provider on ${ENTERPRISE_AGREEMENT_DATE}{% endif %}

4. Standard Terms of Service at ${AGREEMENTS_URL}

   a. Training Terms of Service

   b. Professional Services Terms of Service

   c. General Terms of Engagement

By executing this Order Form, the Parties acknowledges that they have read, understood, and agree to be bound by the Agreement in its entirety. This Order Form and the Agreement shall be governed by the laws of Malaysia.

**SPECIFIC MODIFICATIONS AND OVERRIDES**

${SPECIFIC_MODIFICATIONS_AND_OVERRIDES}

\newpage

**IN WITNESS WHEREOF**, the parties have executed this Agreement by their duly authorized representatives.

| **For and on behalf of Client**    | **For and on behalf of Provider** |
| - | - |
| **Name:** **Position:** **Date:** | **Name:** **Position:** **Date:** |

\newpage

**ORDER DETAILS**

| Item | Unit Of Measure | Quantity |
| - | - | - |
|  |  |  |

\newpage

**SCOPE OF WORK**

1) **\[Scope of work (if any)\]**
