name: '🐛 Bug Report'
description: Create a new bug report.
body:
  - type: textarea
    attributes:
      label: Describe the Bug
      description: A clear and concise description of what the bug is.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Steps to reproduce
      description: Expand the steps on reproducing the bug.
    validations:
      required: true
  - type: textarea
    attributes:
      label: Relevant log output
      description: Please copy and paste any relevant log output. This will be automatically formatted into code, so no need for backticks.
      render: shell
  - type: input
    attributes:
      label: Which browser are you using? (if relevant)
      description: 'For example: Chrome, Edge, Firefox, etc'

