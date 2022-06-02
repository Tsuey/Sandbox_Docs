name: Bug
description: Report a game or vanilla map bug
labels: [bug]
body:
- type: markdown
  attributes:
    value: |
      Please consider opening an [issue](https://github.com/Tsuey/L4D2-Community-Update/issues) to discuss changes before you spend time here.

      We try to not accept unsolicited compiled assets of any kind. If you really need to submit one, please review [our coordination](/CONTRIBUTING.md#Coordination) policy.

      If you are submitting text or script files, please check if the repo already has them and if not, please submit un-modified files from the live game as your earliest commits.
- type: textarea
  attributes:
    label: Changes
    description: What exactly is changed and why?
  validations:
    required: true
- type: textarea
  attributes:
    label: Review
    description:  |
      Is there anything specific that needs review? Optionally, tag the appropriate [maintainer](/CONTRIBUTING.md#Responsibility).

      Note: If this PR is strictly for review, please mark it as a draft to show that merging is not expected.
  validations:
    required: false
- type: textarea
  attributes:
    label: Connected issues
    description: Which [issue](https://github.com/Tsuey/L4D2-Community-Update/issues) (if any) does this address?
    render: markdown
  validations:
    required: false
