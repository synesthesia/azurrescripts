# Python example of using MS Graph with app-only authentication

## Introduction

This folder contains the Microsoft example code for interacting with the MS Graph from Python using application authentication.

With this form of authentication the script can access tenant-wide data subject to permissions granted in the application registration

## Configuration

Follow all steps in the [top-level README](../../README.md) and the [Python README](../README.md).

Ensure that you have an Azure AD application registration for application access to the MS Graph API as documented in the top-level [README](../../README.md).

In this directory copy the file `config.sample.cfg` to `config.cfg` and populate with the Client ID and Tenant Id for the application registration.

To run the code:
- in your shell with active conda environment, change into this directory
- open VS Code (`code .`)
- in VS code open `main.py`
- run the code in the file using the run button (see [VS Code documentation for Python](https://code.visualstudio.com/docs/languages/python))
- OR at the conda prompt in this directory just run `python main.py`

## Understanding the code

If you follow the [Microsoft tutorial steps](https://learn.microsoft.com/en-us/graph/tutorials/python-app-only?tabs=aad&tutorial-step=2) you will see how the code has been built up.