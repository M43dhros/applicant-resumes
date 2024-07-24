
PR's and PR Reviews
General Hey Team, below is some guidelines for PR's and PR reviews. This is a starting point as we change our processes and standardize. There is more to come but this is the minimum to start with as we get the other pieces in place. We welcome feedback but going forward we should be doing the below when putting a PR together.
 
PR Housekeeping
1)      Size - Pull requests should be small and more frequent. This makes reviewing them far easier than going through hundreds of files.
2)      Description – PR Description should not be empty and should provide sufficient detail to understand the scope of the PR.
3)      Required Reviewer should be Team Lead or designate.
a.      Optional Reviewers: Other Application Team (if applicable)
b.     Peer Reviews are important, and the team should also review.
Reviews
1)      Code Review - Reviews are completed and findings are given to the developer initiating the PR to address. Code Review guidelines in the works and will be reviewable soon.
a.      Review notes and comments are on the PR itself and need to be addressed prior to completing the PR. 
2)      Build completes successfully.
3)      Readme.md - Readme is checked and updates are verified if applicable.
4)      Unit Tests – Exist, provide desired coverage, and are applicable for the PR or the PR is rejected.
a.      Unit tests execute and pass, or the build is failed. This is the responsibility of the TL's involved to ensure that a PR Is not completed without Unit Tests associated to the code changes.
5)      Rejected PR’s findings are appropriately handled, and the PR cannot proceed without these findings being addressed.
b.     Currently a PR can reset from Rejected status, and the rejection findings/comments may be lost and unaddressed.
c.      Need to investigate how a rejected PR can reset without resolution. We need to dig into the policies/rules/process to see if there is a way to configure it not to reset without resolution to findings from a rejected PR.
d.     Short term the Dev Team Lead must verify that all findings are addressed manually when a PR was rejected before the PR is approved and completed.
Next stage will be adding additional automated checks for secret scanning, build validations, and adding automation test case requirements into this mix as we migrate to Shift Left.
 heart 1
 
