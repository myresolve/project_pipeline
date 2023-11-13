nvm install 16.0.0
nvm use 16
npm ci
npm i -g eslint

aws configure

aws eks update-kubeconfig --name cluster --region us-east-1

login
gh auth login


#ubuntu version
lsb_release -a

chmod +x ./init.sh

export AGENT_ALLOW_RUNASROOT="1"

    #Clone Repo into workspace

Open terminal and enter the folder of the github repository/project you want to update
Type into terminal: “git add .” and then hit enter
Type into terminal “git status” and then hit enter (this step is optional)
Type into terminal “git commit -m ‘type any message here” and then hit enter
Type into terminal “git push” and then hit enter

gh repo clone myresolve/first_workflow
    #turn directory into repo
? git init
? Reinitialized existing Git repository in /workspace/first_workflow/.git/
mkdir .github
cd .github
.github root$ mkdir workflows
.github root$ cd workflows
touch my-first-workflow.yml
rm my-first-workflow.yml
touch my-first-workflow.yml

    #add all files of the current directory to track (including untracked) and then use
git add .
    #start action
git commit -m "Added First Workflow" && git push
git commit -m "parralel-job-example" && git push

git reset --soft HEAD~8 (remove 8 commits)
git reflog (after mistake)

test

sudo apt-get update; sudo apt-get install -y curl
nvm install v16.0.0
nvm use v16.0.0
npm ci
? npm install -g npm@7.21.1
? npx update-browserslist-db@latest
? npm audit fix --force


lint

prettier issue
#answer
A workaround is to remove the prettier entry in package.json of this package - no local/global prettier install necessary. Example:

{
  "devDependencies": {
    ...
    "prettier": "^1.19.1", // remove this line completely
  },
}

npm i -g eslint
eslint --fix .
npm run lint -- --fix


? npm install --save-dev prettier
