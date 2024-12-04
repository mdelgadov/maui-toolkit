name: Feature Request
description: Provide a suggestion for a Syncfusion Toolkit for .NET MAUI open source controls.
labels: ["proposal/open", "t/enhancement"]
assignees: []
body:
  - type: markdown
    attributes:
      value: |
        Thank you for your interest in Syncfsuion Toolkit for .NET MAUI open source controls! We welcome all ideas. Please provide a detailed description, including screenshots, mockups, and pseudo-code, and consider the platform feasibility across .NET MAUI to expedite review.

        If you're unsure about a request, feel free to [start a discussion(https://github.com/syncfusion/maui-toolkit/discussions/new?category=ideas) to collaborate with the team and community before proceeding.
  - type: textarea
    id: description
    attributes:
      label: Description
      description: Please describe the feature, focusing on what it does and the end result. Feel free to include diagrams, mockups, or screenshots to support your idea.
      placeholder: Provide support for vertical orientation in SfSegmentedControl to modify the arrangement of items.
    validations:
      required: true
  - type: textarea
    id: api-changes
    attributes:
      label: Public API Changes 
      description: Include a list of all API changes, additions, subtractions as would be required by your proposal. These APIs should be considered placeholders, so the naming is not as important as getting the concepts correct. If possible you should include some example (pseudo-)code of usage of your new API. This will not only help us understand better, but also help you think about how you want to use this feature as a developer.
      placeholder: |
        ```csharp
        var SfSegmentedControl = new SfSegmentedControl();
        SfSegmentedControl.Orientation = SegmentOrientation.Vertical; // new API
        ```
    validations:
      required: true
  - type: textarea
    id: use-case
    attributes:
      label: Intended Use-Case
      description: Provide a detailed example of how and why this feature would be used, emphasizing the purpose behind implementing this feature, rather than simply describing its functionality.
      placeholder: In my app, I want to change the SfSegmentedControl from horizontal to vertical orientation to better organize items and enhance the user experience.
    validations:
      required: true
  - type: markdown
    attributes:
      value: |
   