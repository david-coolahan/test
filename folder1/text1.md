title 	linkTitle 	weight 	type 	description
Break glass account setup
	
Break glass account setup
	
10
	
docs
	
This page describes the configuration of break glass accounts within Microsoft Entra ID associated with systems built according to the guidance provided by ASD's Blueprint for Secure Cloud.

{{% alert title="Instruction" color="dark" %}}

The below tables outline the as built configuration for ASD's Blueprint for Secure Cloud (the Blueprint) for the Microsoft Entra admin portal at the following URL:

https://entra.microsoft.com/#view/Microsoft_AAD_UsersAndTenants/CreateUser.ReactView

The settings described on these pages provide a baseline implementation for a system configured using the Blueprint. Any implementation implied by these pages should not be considered as prescriptive as to how an organisation must scope, build, document, or assess a system.

Implementation of the guidance provided by the Blueprint will differ depending on an organisation’s operating context and organisational culture. Organisations should implement the Blueprint in alignment with their existing change management, business processes and frameworks.

Placeholders such as <ORGANISATION.GOV.AU>, <BLUEPRINT.GOV.AU> and <TENANT-NAME> should be replaced with the relevant details as required.

{{% /alert %}}
Break glass first account
Item 	Value
Display name 	Break Glass 1
User type 	Member
Account enabled 	Checked
Usage location 	Australia
Assigned roles 	Global Administrator
Groups 	<CA exclude groups>
Break glass second account
Item 	Value
Display name 	Break Glass 2
User type 	Member
Account enabled 	Checked
Usage location 	Australia
Assigned roles 	Global Administrator
Groups 	<CA exclude groups>
Related information
Security & Governance

    [Authentication Hardening]({{<ref "system-hardening-authentication">}})
    [Multi-factor Authentication]({{<ref "multi-factor-authentication">}})
    [Essential Eight - Restrict Administrative Privileges]({{<ref "security-and-governance/essential-eight/restrict-administrative-privileges.md">}})

Design

    [Emergency access admin accounts]({{<ref "design/platform/identity/users">}})

Configuration

    [Break Glass]({{<ref "configuration/entra-id/users/break-glass-accounts.md">}})

References

    Create or delete users
    Emergency access accounts
    Securing privileged access
    Manage emergency access accounts
