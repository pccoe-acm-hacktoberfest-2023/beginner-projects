# Contribution Rules📚:

1. Do NOT remove other content.
1. Styling/code can be pretty
1. Try to keep pull requests small to minimize merge conflicts

## Getting Started 🤩🤗:

1. Fork this repo (button on top)
1. Clone on your local machine
   ```sh
       git clone https://github.com/your-username/animated-components.git
   ```
1. Navigate to project directory.
1. ```sh
   cd animated-components
   ```
1. Create a new branch with a sensible name like your-name-add-hover-icons
   ```sh
   git checkout -b my-new-branch
   ```
1. Stage the changes
   ```sh
    git add .
   ```
1. Commit your changes
   ```sh
   git commit -m "Relevant message"
   ```
1. Then push
   ```sh
   git push origin my-new-branch
   ```
1. Create a new pull request from your forked repository
1. Avoid Conflicts {Syncing your fork}
1. An easy way to avoid conflicts is to add an 'upstream' for your git repo, as other PR's may be merged while you're working on your branch/fork.
   ```sh
   git remote add upstream https://github.com/pccoe-acm-hacktoberfest-2023/animated-components.git
   ```
1. You can verify that the new remote has been added by typing.
   ```sh
   git remote -v
   ```
1. To pull any new changes from your parent repo simply run
   ```sh
   git merge upstream/main
   ```
1. This will give you any eventual conflicts and allow you to easily solve them in your repo. It's a good idea to use it frequently in between your own commits to make sure that your repo is up to date with its parent.
