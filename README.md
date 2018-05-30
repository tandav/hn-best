# HN Best Posts
- monorepo
- front - github pages (react?)
- back - mysql, spring / sqlite / jpa / raw queries
- pagination, only last 3 or 5 days on main page
- ci
- replicas/backups of db


## log
- for some reason can't set up `git config core.hooksPath ../hn-best/hooks`. now `post-receive` hook is in default location. If i want to edit it, i just use `sshfs`
    - now move it to repo and add symlink to .git/hooks
test
