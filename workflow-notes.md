# Workflow Notes

## Concepts
- Issue: a work item that describes what to do, with goals and a task checklist.
- Branch: a separate line of work so changes don't affect the stable code.
- Commit: a saved, described change in the branch history.
- Pull request: a request to merge a branch into another, with review.
- Default branch: the main stable branch (here, main) that receives merged work.

## Links
- Repository: https://github.com/anuneza-code/swe325_525-github-ai-practice
- Default branch: main
- Issue: https://github.com/anuneza-code/swe325_525-github-ai-practice/issues/1
- Feature branch: feature/github-ai-workflow
- Pull request: https://github.com/anuneza-code/swe325_525-github-ai-practice/pull/2

## How it fits together
The issue defined the work. A feature branch (feature/github-ai-workflow) held the
changes as separate commits. A pull request proposed merging the branch into main,
where a self-review identified an improvement that was fixed with another commit.
After review, the PR was merged into main, which closed the issue automatically.