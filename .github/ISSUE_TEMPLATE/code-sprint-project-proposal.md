---
name: Code Sprint Project Proposal
description: Use this template for Code Sprint project proposals.
title: "[Project Proposal]: "
labels: ["code sprint topic"]
assignees:
  - mathewbiddle
  - mwengren
body:
  - type: markdown
    attributes:
      value: Thanks for taking the time to submit a Code Sprint project proposal!
  - type: textarea
    id: proj_desc
    attributes:
      label: Project Description
      description: Brief summary of the intent of the project.
      placeholder: Revamp pyobis package to align with updated api.
    validations:
      required: false
  - type: textarea
    id: exp_outcome
    attributes:
      label: Expected Outcomes
      description: What do you expect to get out of the project.
      placeholder: Make a usable api query package.
    validations:
      required: false
  - type: textarea
    id: skills_required
    attributes:
      label: Skills required
      description: What types of skills does the prospective contributor need?
      placeholder: Experience with Python.
    validations:
      required: false
  - type: dropdown
    id: difficulty
    attributes:
      label: Difficulty
      description: Identify the difficulty of the project.
      options:
        - Easy
        - Moderate
        - Difficult
    validations:
      required: false
  - type: input
    id: lead
    attributes:
      label: Topic Lead(s)
      description: Include topic lead names and GitHub handles as a comma separated list.
      placeholder: mathewbiddle
    validations:
      required: false
  - type: textarea
    id: lead
    attributes:
      label: Relevant links
      description: Include relevant links to issues/repositories/websites here.
      placeholder: https://github.com/ioos/ioos-code-sprint/issues/1
    validations:
      required: false