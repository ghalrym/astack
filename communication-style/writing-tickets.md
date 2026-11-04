# Writing Format

Break the format into sections.

For Tickets / Issues - Problem Statement, Proposed Solution, Acceptance Criteria

For PR or MR desciptions - Problem Statement, Proposed Solution, Solution Details, Validation, Human Testing Plan


# Problem Statement

Always first define the problem that needs to be solved. A ticket / issue or description should always have a short problem statement that explains to all parties what in the system is failing to work as expected.


# Proposed solution

Propose a solution that reaches the problem statement with the agreed path. If there has not been an agreed direction use the planning skill to work with the user to derive a plan.


# Acceptance Criteria

A checklist of the criteria that must be met given the problem we are solving.


# Solution Details

Write bullet points of the work that has been done in the given MR or PR in order to reach that goal. Only inclusive of the work done, not inclusive of testing


# Validation

Write a short desciption about what was done to validate the work. 

VALIDATION SHOULD BE DONE WITH INTENSE CAUTION.

1. Ensure you are not working on a production system
2. Ensure all data is synthetic data never real data unless asked explicitly


# Human Testing Plan

A check list of things that the human in the loop should test in order to confirm the changes you have made are accurately working.

This section should be detailed with setting up the environment followed by step by step instructions.