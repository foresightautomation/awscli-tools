# awscli-tools

Handy tools for using the AWS cli.

To use this on a production system, you can run the following commands
as root:

```bash
cd /root
git clone --no-checkout https://github.com/foresightautomation/awscli-tools.git
cd awscli-tools
git config core.worktree /
git reset --hard origin/master
git pull
/usr/local/sbin/awscli-tools-initialize
/usr/local/sbin/awscli-tools-run-deploy
```
