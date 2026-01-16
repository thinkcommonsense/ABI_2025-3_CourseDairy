
Notes about Git
We have local and remote repositories.
A repository consists of working direcotry, staging directory and the repository.
I did a test change

git status
shwos changes to the working directory and the state of the staging area

git add
add changes to a file to the staging area


sdf

Network Graph

                Head
                I
                Master
                I
98ca9           34ac2



                Head
                I
                Master
                I
89as7           98ca9           34ac2

## Concepts
## Commits
A commit is a bundled up set of changes.
It is a uniquely identified by a [hash](https://wikipedia.org/wiki/Hash_function)
- Author -- **who** did the change?
- Date -- **when did the change occur?
- Message -- **why** did the change occur?
- Patch -- **what** was changed?

## Commands

- `git status` -- shows changes to the working directory and the state of the s
- `git add` -- add changes to a file to the staging area
- `git commit` -- bundle the staged changes and commit them to the repository
- `git push` -- synchronize changes[^changes] **to** the remote
- `git pull` -- synchronize change[^changes] **from** the remote
- `git restore` -- restore the work directory or staging area

