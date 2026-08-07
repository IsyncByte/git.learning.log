# My Learning Log

## About This Project
I'm learning Git and version control to track my work.

## Goals
- Understand how commits work
- Learn branching and merging
- Push my work to GitHub
## What I Learned Today
- Git is like a time machine for your files
- Every commit is a snapshot you can go back to
- Branches let you experiment without affecting the main project
- You can merge branches back together when ready.

## Tags

- git tag -a v1.0 -m "message": create an annotated tag (stores tagger, date, message)
- git tag v1.0: create a lightweight tag (just a pointer, no metadata)
- git push origin v1.0: push a specific tag to remote
- git push --tags: push all tags
- Annotated tags are for releases; lightweight tags are for private/temporary labels
- CI/CD pipelines often trigger on new tags