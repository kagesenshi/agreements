---
title: Opportunity Registration Form
version: 0.1.0
prime_name: "[PRIME]"
prime_registration_no: "[PRIME_REGISTRATION_NO]"
prime_address: "[PRIME_ADDRESS]"
provider_name: "[PROVIDER]"
provider_registration_no: "[PROVIDER_REGISTRATION_NO]"
provider_address: "[PROVIDER_ADDRESS]"
effective_date: DD MMMM YYYY
end_client: "[END_CLIENT]"
opportunity_name: "[OPPORTUNITY_NAME]"
exclusivity: false
alternative_delivery_commission_rate: 10%
provider_proposed_workshare: |
    1. [WORKSHARE]
specific_modifications_and_overrides: |
    1. None
master_teaming_date: 
---

**PARTIES INFORMATION**

|   |   |
| - | - |
| **Prime** | ${PRIME_NAME} (Registration No. ${PRIME_REGISTRATION_NO}) at ${PRIME_ADDRESS} |
| **Provider** | ${PROVIDER_NAME} (Registration No. ${PROVIDER_REGISTRATION_NO}) at ${PROVIDER_ADDRESS} |
| **Date** | ${EFFECTIVE_DATE} |

<br/>

**INCORPORATED TERMS**

This Opportunity Registration Form ("Opportunity Registration") is issued pursuant to, and is governed by, the following documents (collectively, the "Agreement"). If the documents conflict, the following order of precedence applies:

1. This Opportunity Registration including the Specific Modifications And Overrides
{% if MASTER_TEAMING_DATE %}
2. Master Teaming Agreement (if any) entered between Prime and Provider on ${MASTER_TEAMING_DATE}{% endif %}

3. General Teaming Terms and Conditions at ${AGREEMENTS_URL}

By executing this Opportunity Registration, the Parties acknowledges that they have read, understood, and agree to be bound by the Agreement in its entirety. This Opportunity Registration and the Agreement shall be governed by the laws of Malaysia.

<br/>

**OPPORTUNITY DETAILS**

|   |   |
| - | - |
| **End Client** | ${END_CLIENT} |
| **Opportunity Name** | ${OPPORTUNITY_NAME} |
| **Exclusivity** | {% if EXCLUSIVITY %} Exclusive {% else %} Non-Exclusive {% endif %} |
| **Alternative Delivery Commission Rate**\*  | ${ALTERNATIVE_DELIVERY_COMMISSION_RATE} |

<br/>

*Alternative Delivery Commission Rate is only applicable if the Opportunity is designated as Non-Exclusive and Prime elects to utilize an alternative party for the delivery and execution of the resulting contract.

<br/>

**PROVIDER PROPOSED WORKSHARE**

${PROVIDER_PROPOSED_WORKSHARE}

<br/>

**SPECIFIC MODIFICATIONS AND OVERRIDES**

${SPECIFIC_MODIFICATIONS_AND_OVERRIDES}

\newpage

**IN WITNESS WHEREOF,** the parties have executed this Opportunity Registration by their duly authorized representatives.

| **For and on behalf of Prime**    | **For and on behalf of Provider** |
| - | - |
| Signature: | Signature: |
| Name: | Name: |
| Position: | Position: |
| Date: | Date: |


