# Git-Hook-Sender

A list of all git hooks can be found here: https://git-scm.com/book/en/v2/Customizing-Git-Git-Hooks

git supplies some sample hooks in ./git/hooks. 
Removing the '.sample' extension to these hooks will make them execute.
In this case, a sample post-merge hook does not exist. We will make one.


##Instructions (MacOS):

###Copy post-merge executable found in resources to .git/hooks:

cp resources/post-merge ./.git/hooks/post-merge

###Make post-merge executable:

chmod +x ./.git/hooks/post-merge

