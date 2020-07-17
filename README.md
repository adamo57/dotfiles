# DOTFILES

## Install
Clone the repo
`git clone git@github.com:adamo57/dotfiles.git`

Install the CronJob

`crontab -e`

Paste `0 19 * * 1,3,5 $HOME/dotfiles/backup.sh` and save the file.

This adds a CronJob that runs the backup script every Monday
