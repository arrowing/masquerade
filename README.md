Instructions on masquerading as other users in git:

```bash
export GIT_AUTHOR_NAME="Linus Torvalds"
export GIT_AUTHOR_EMAIL="torvalds@linux-foundation.org"
export GIT_AUTHOR_DATE="Tue Jan 19 03:14:07 2038 +0000"
export GIT_COMMITTER_NAME="$GIT_AUTHOR_NAME"
export GIT_COMMITTER_EMAIL="$GIT_AUTHOR_EMAIL"
export GIT_COMMITTER_DATE="$GIT_AUTHOR_DATE"

git commit -m "Enjoy!"
```
