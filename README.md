- 👋 Hi, I’m @seekstudy-end
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
seekstudy-end/seekstudy-end is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
welcome to my homepage,we can talk abount it together. 
name: 💪 Suggest a Project
description: Have a project that we should be listing? Let us know!
title: "[New Project]: <title>"
labels: ["💪 New Project"]
body:
  - type: markdown
    attributes:
      value: |
        # Thank you for taking the time to help us improve the app!
  - type: checkboxes
    attributes:
      label: Is this project already existing in the app?
      description: Please search the happycommits.json file in the root directory.
      options:
        - label: I have searched the existing projects
          required: true
  - type: textarea
    attributes:
      label: Tell us about the project
      description: Please provide a link to the github repo and tell us why the
        project would be a good fit!
    validations:
      required: yes
  - type: checkboxes
    id: DPG
    attributes:
      label: Is the Project a DPG (Digital Public Good)
      description: You can check the DPG Registry
        [here](https://digitalpublicgoods.net/registry/),
      options:
        - label: "Yes"
        - label: "No"
          required: true
  - type: checkboxes
    id: SDGs
    attributes:
      label: Does the project list which Sustainable Development Goals it addresses in
        its labels?
      description: View the SDGs [here](https://sdgs.un.org/goals) and view how a
        project lists them in their labels
        [here](https://github.com/rubyforgood/human-essentials)!
      options:
        - label: "Yes"
        - label: "No"
  - type: checkboxes
    id: terms
    attributes:
      label: Code of Conduct
      description: By submitting this issue, you agree to follow our [Code of
        Conduct](https://github.com/github/.github/blob/main/CODE_OF_CONDUCT.md)
      options:
        - label: I've read the Code of Conduct and understand my responsibilities as a
            member of the GitHub community
          required: true
  - type: textarea
    attributes:
      label: Anything else?
      description: >
        Links? References? Anything that will give us more context about
        the issue you are encountering!
        Tip: You can attach images or log files by clicking this area to highlight it and then dragging files in.
