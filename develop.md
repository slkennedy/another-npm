A test of branches

pushed to the develop branch
it triggered a build
no publish triggered b/c of branch

opened a pr on github and merged it
build was triggered
build failed - The command "git fetch origin +refs/pull/1/merge:" failed and exited with 128 during .
tried a manual restart from travis and it failed again

trying another pr and not merging it this time....
https://docs.travis-ci.com/user/pull-requests/