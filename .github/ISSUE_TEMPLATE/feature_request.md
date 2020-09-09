---
name: Feature request
about: Describe a use case where force:source:pull doesn't work
title: ''
labels: enhancement
assignees: ''

---

**What is the use case that doesn't work? Please describe.**
A clear and concise description of what the problem is and how to reproduce it. Ex. When I delete a field, the related record types are not pulled.

**Full steps to reproduce**
* Create a Scratch Org (specify needed settings if any)
* Create a field
* Create a Permission Set and add the FLS for the previous field
* Pull everything
* Delete the field
* Pull again

**Expected result**
The field and the Permission Set are pulled

**Actual result**
Only the field is pulled. Local repo still has a reference to the field that doesn't exists anymore, because of the Permission Set not being pulled

**Additional context**
Add any other context or screenshots about the feature request here.
