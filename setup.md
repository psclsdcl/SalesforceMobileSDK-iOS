# Setup

remote repo
==
After you git clone, you need to add the upstream repo (pointing to the public repo):

`git remote add upstream git@github.com:forcedotcom/SalesforceMobileSDK-iOS.git`

submodules
==
After you git clone, you need to initialize the (external) submodules:

`git submodule init`
`git submodule update`

merging
==
To pull changes from our public repo:

`git fetch upstream`

`git merge upstream/master`