---
x-trestle-comp-def-rules:
  software-comp:
    - name: rule-pcidss_4_2-2.2
      description: Rule for pcidss_4_2-2.2
x-trestle-global:
  profile:
    title: rhel9-pcidss_4-base
    href: trestle://profiles/rhel9-pcidss_4-base/profile.json
  sort-id: pcidss_4_2-02.02
---

# pcidss_4_2-2.2 - PAN is secured with strong cryptography whenever it is sent via end-user messaging technologies.

## Control Statement

Vendor default accounts are managed as follows:
- If the vendor default account(s) will be used, the default password is changed per
Requirement 8.3.6.
- If the vendor default account(s) will not be used, the account is removed or disabled.

______________________________________________________________________

## What is the solution and how is it implemented?

<!-- For implementation status enter one of: implemented, partial, planned, alternative, not-applicable -->

<!-- Note that the list of rules under ### Rules: is read-only and changes will not be captured after assembly to JSON -->

<!-- Add control implementation description here for control: pcidss_4_2-2.2 -->

4.2.2.a Examine documented policies and procedures to verify that processes are defined to secure PAN with strong cryptography whenever sent over end-user messaging technologies.
4.2.2.b Examine system configurations and vendor documentation to verify that PAN is secured with strong cryptography whenever it is sent via end-user messaging technologies.

### Rules:

  - rule-pcidss_4_2-2.2

### Implementation Status: planned

______________________________________________________________________
