## Screenshots

### Undo Commit
![Undo Commit](screenshots/Drop-commit.png)


### Squash Commit
![Squash Commit](screenshots/squash-commit-1.png)

![Squash Commit](screenshots/squash-commit-2.png)

### Amend Commit
![Amend Commit](screenshots/amend.png)

### Graph
![Graph](screenshots/graph.png)

## Note

During the rebase operations, Git sometimes reported an error while deleting the `.git/rebase-merge` directory. This was caused by the repository being located inside OneDrive, which was temporarily locking the files. The `drop`/`squash` operations themselves were completed successfully; only the cleanup of the rebase directory failed.I forced-deleted the leftover directory as in the screenshots above.
