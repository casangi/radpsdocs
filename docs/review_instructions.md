# Internal and External Reviews

## Internal Review Guidelines

The goal of an internal review is to provide initial feedback to the scrum team soon after the development work for an issue has been completed. It is not intended to provide exhaustive testing for all possible use cases.

Assignees to internal reviews should be part of the scrum team.

Internal reviews would be completed within the sprint where it is assigned. Any new issues found during the review should be created ideally before the start of the sprint review and at the latest before the start of sprint planning.


## External Review Guidelines

The goal of external reviews is to provide outside feedback on the work being produced by the scrum team particularly with respect to specific use cases. The feedback from the external reviewer will be used to guide the future work done by the scrum team.

Assignees for external reviews do not need to be part of the scrum team, but should at least attend the sprint reviews so that they know what is being worked on.

External reviews should be completed within 1 sprint of when they are assigned.


## Process 

- Product owner assigns notebooks to either themselves or other scrum team members for internal review during sprint planning.

- Product owner solicits external reviews outside the sprint planning processes if the external reviewers are not already part of the scrum team.

- In either case, the assigned reviewer does the following checks :

    - Does the notebook run as expected (either in collab or locally)? (_Internal reviews should check the notebook runs in collab and locally._)
    - Does the notebook show the appropriate documentation of the function?
    - Are the explanations and contents of the notebook clear?
    - Do additional simple interactive tests trigger any errors?
    - Are there any obvious gaps in the unit test suite? [this seems outside the scope of a reviewer and more something that Sandra should check..]
    - Any additional review needed by external reviewers or for additional use cases?

- The assigned reviewer should report their feedback to the above questions on the issue that they have been assigned to reviewer. The product owner may request that the reviewers create new issues to address the feedback.

