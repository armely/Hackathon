---
name: Hackathon Submission 2025
about: Describe this issue template's purpose here.
title: Hackathon Submission 2025
labels: ''
assignees: ''

---

name: Hackathon Project Submission
description: Submit your hackathon project details here
title: "[Submission] <Project Title>"
labels: ["hackathon"]
assignees: []
 
body:
  - type: input
    id: firstname
    attributes:
      label: First and Last Name
      placeholder: e.g., Sammy Chesire
    validations:
      required: true
 
  - type: dropdown
    id: mslearn
    attributes:
      label: Did you attend the Youtube live learning plan?
      options:
        - Yes
        - No
    validations:
      required: true
 
  - type: textarea
    id: description
    attributes:
      label: Project Pitch or Description
      description: Describe your project clearly.
      placeholder: Write a detailed description...
    validations:
      required: true
 
  - type: input
    id: repo
    attributes:
      label: Project Repository URL
      placeholder: https://github.com/...
    validations:
      required: true
 
  - type: input
    id: demo
    attributes:
      label: Project Demo Video URL
      placeholder: https://youtube.com/...
    validations:
      required: false
 
  - type: textarea
    id: team
    attributes:
      label: Team Members
      description: Add all team members involved.
      placeholder: Name them here...
    validations:
      required: true
