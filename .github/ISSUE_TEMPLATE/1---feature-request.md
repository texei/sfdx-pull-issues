---
name: 1 - Feature request
about: Describe a use case where force:source:pull doesn't work
title: ''
labels: enhancement
assignees: ''

---

**What is the use case that doesn't work? Please describe.**
A clear and concise description of what the problem is and how to reproduce it. Ex. When I delete a field, the related record types are not pulled.

**Full steps to reproduce**
Steps to reproduce the behavior:
1. Create a Scratch Org (specify needed settings if any)
2. Create a field
3. Create a Permission Set and add the FLS for the previous field
4. Pull everything
5. Delete the field
6. Pull again

**Expected result**
The field and the Permission Set are pulled

**Actual result**
Only the field is pulled. Local repo still has a reference to the field that doesn't exists anymore, because of the Permission Set not being pulled

**Additional context**
Add any other context or screenshots about the feature request here.
