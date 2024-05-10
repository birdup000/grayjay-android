name: Bug Report
about: Create a report to help us improve
title: '[Bug] '
labels: bug
assignees: ''

body:
  - type: markdown
    attributes:
      value: |
        **Description of the issue:**
  - type: textarea
    id: description
    attributes:
      label: Describe the bug
      description: A clear and concise description of what the bug is.
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        **Steps to reproduce:**
  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
      description: Steps to reproduce the behavior:
      1. Go to '...'
      2. Click on '....'
      3. Scroll down to '....'
      4. See error
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        **Expected behavior:**
  - type: textarea
    id: expected
    attributes:
      label: Expected behavior
      description: A clear and concise description of what you expected to happen.
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        **Actual behavior:**
  - type: textarea
    id: actual
    attributes:
      label: Actual behavior
      description: A clear and concise description of what is actually happening.
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        **Device information:**
  - type: input
    id: device
    attributes:
      label: Device
      description: Samsung Galaxy A33 5G
    validations:
      required: true
  - type: input
    id: os
    attributes:
      label: Android version
      description: Enter your Android version (e.g., Android 13)
    validations:
      required: true
  - type: input
    id: grayjay
    attributes:
      label: GrayJay version
      description: 210
    validations:
      required: true
  - type: input
    id: youtube
    attributes:
      label: YouTube plugin version
      description: 157
    validations:
      required: true
  - type: input
    id: odysee
    attributes:
      label: Odysee plugin version
      description: 33
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
        **Additional context:**
  - type: textarea
    id: context
    attributes:
      label: Additional context
      description: Add any other context about the problem here.
