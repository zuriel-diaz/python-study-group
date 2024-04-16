# Python Study Group

## Goal

## Requirements/Dependencies
- Git
- Curl
- Pyenv
- Poetry

## Setup

1. Clone the repository

2. Install dependencies
```
poetry install --no-root
```
Poetry generates a virtual environment for you.

3. Execute the tests
```
pytest
```

Note.-Make sure you have enable the virtual environment. Execute the following command to identify where is located the virtual environment created by Poetry:

```
poetry env info --path
```

## Approach/Methodology

1. Co-define the topics agenda and expectations with the team.
2. Learn core concepts about *X* subject.
3. Learn by doing by co-creating/co-participating in a laboratory.
4. Share the recap points via team meeting.
5. Interview to identify missing gaps/opportunities.
    **We'll need to conduct a new round depending on interview results.**
6. Share the knowledge via Weekly sessions (Feynman technique).

## Contribution

1. Talk with the team to pick a subject from the current agenda.
    * Clarify the scope and expectations.

    **Note.-**Feel free to follow this contribution/guideline for code quality enhancement. E.g., coding standards, etc.
2. Create a new feature branch from the **main** branch.
3. Follow the template document to research/consolidate the chosen topic.
3.1 We must determine at least a couple of items: tests and coding conventions. This needs to be discussed and created by the team.
4. Commit and push the in-progress branch remotely and [create the Pull-Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/getting-started/best-practices-for-pull-requests). It should be from the current branch into the main branch.
    The expectation is to have at least two approvals from the teammates to gain experience and grow from specific feedback.