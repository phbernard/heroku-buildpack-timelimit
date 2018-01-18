# Heroku Buildpack for timelimit

Currently installs timelimit 1.8.1 on Heroku Cedar. See https://devel.ringlet.net/sysutils/timelimit/#download

## Install

    $ cd /path/to/your-app
    $ heroku buildpacks:add https://github.com/phbernard/heroku-buildpack-timelimit.git

    # Push changes to deploy
    $ git push
