# Contributing to the Project

## Github Setup
If you already have github setup and you're comfortable w/ push/pulling, please ignore this section.

First you will need to ensure that Github is installed on your computer. You can do this by running the command `git` if you are on Mac/Linux. If it is 
not installed, then it will be automatically downloaded (on Mac). On linux it will require more steps, but if you're using Linux you probably know how 
to do this so I'll move on. Setup a SSH key to use for pushing commits to github. To do this please follow the instructions [here](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/adding-a-new-ssh-key-to-your-github-account).

Once this has been done, you will need to clone the repository to your local environment. To do this, please go to a directory on your computer where you 
would like the project to be located, and then run the command `git clone` with the repo ssh URL at the end. On the main page of this repository there is 
a `Code` button which you can click to get that URL.

Once you have the repository cloned, open it in your favorite code editor. To make sure that you have everything set up, please run the following commands:

**NOTE** when you see `<yourname>` it is an indicator that you should replace that entire block with your name. Ex: test_mariam, test_fatma, etc
```
git checkout -b test_<yourname>
echo "hello world" >> can_you_hear_me.txt
git add -A
git commit -m'testing hello world'
git push --set-upstream origin test_<yourname>
```
This should happen without any errors. Once you've confirmed this, please return to the main branch by typing the following command `git checkout main`
