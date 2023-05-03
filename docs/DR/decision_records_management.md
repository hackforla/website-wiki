# Decision Records Management

This guide provides step-by-step instructions for developers to create, update, or remove decision records.

## Creating a New Decision Record

### Adopted Solution

!!! success "Solution Adopted"
    1. In the `adopted` directory, create a new markdown file for the decision record.
    2. Name the file using the format `<short_description>.md`, replacing `<short_description>` with a brief description of the decision.
    3. Use the Decision Record Template provided below, and fill in the relevant information for your decision record:
    ``` markdown

    ---
    status: ✅ Adopted
    ---

    #### Issue
    *[Issue #<issue_number>](https://github.com/hackforla/website/issues/<issue_number>)*

    #### Problem Statement
    *Explain the problem you're trying to solve in more detail.*

    #### Potential Solution
    *Describe the potential solution that was evaluated.*

    #### Feasibility Determination
    *Explain how the feasibility of the potential solution was determined, including any factors that influenced the decision (e.g., cost, time, resources, etc.).*
    ```

### Not Implemented Solution

!!! failure "Solution Not Implemented"
    1. In the `not_implemented` directory, create a new markdown file for the decision record.
    2. Name the file using the format `<short_description>.md`, replacing `<short_description>` with a brief description of the decision.
    3. Use the Decision Record Template provided below, and fill in the relevant information for your decision record:
    ``` markdown

    ---
    status: ⛔ Not Implemented
    ---

    #### Issue
    *[Issue #<issue_number>](https://github.com/hackforla/website/issues/<issue_number>)*

    #### Problem Statement
    *Explain the problem you're trying to solve in more detail.*

    #### Potential Solution
    *Describe the potential solution that was evaluated.*

    #### Feasibility Determination
    *Explain why the potential solution was not implemented, including any factors that influenced the decision (e.g., cost, time, resources, etc.).*
    ```

## Updating an Existing Decision Record

1. Locate the markdown file for the decision record you wish to update within the appropriate directory (`adopted` or `not_implemented`).
2. Edit the file directly, updating the content as needed (e.g., status, issue, problem statement, potential solution, feasibility determination).
3. Save your changes and commit the updated file.

## Removing a Decision Record

1. Locate the markdown file for the decision record you wish to remove within the appropriate directory (`adopted` or `not_implemented`).
2. Delete the file from the repository.
3. Commit your changes.
