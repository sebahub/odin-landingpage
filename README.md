# Odin Project

[Odin Project](https://www.theodinproject.com)

## Useful links

- [Learn how to learn](https://www.coursera.org/learn/learning-how-to-learn) starts 15.04.2022
- [Replit code and learn together](https://replit.com/)
- [mdn Webdocs](https://developer.mozilla.org/en-US/)


## Learning

### Pomodoro Technique
[wiki](https://en.wikipedia.org/wiki/Pomodoro_Technique)

Set timer for 25 minutes, work for 25 minutes, take 5 minute break, again 25 minutes, after 4x 25 Minutes, take longer 15-30 minute break

[Tomato Timer](http://tomato-timer.com/#)

## Asking for help

### Markdown

For a single line of Code

`one backtick before and after`

For multiple lines of Code

```javascript
Three backticks before and after
```

## The Linux command line

### Useful commands

open Terminal `CTR + ALT + T`  
show username `whoami`  
current directory `pwd`


## Git and Github

### Setting up git and github

update System

```
sudo apt update
sudo apt upgrade
```
install git

```
sudo add-apt-repository ppa:git-core/ppa
sudo apt update
sudo apt install git
```

configure git and github

```
git config --global user.name "Your Name"
git config --global user.email "yourname@example.com"
```
change default branch to main
```
git config --global init.defaultBranch main
```
colorful output
```
git config --global color.ui auto
```
check config
```
git config --get user.name
git config --get user.email
```
### create SSH Key
check if ssh key is installed
```
ls ~/.ssh/id_ed25519.pub
```
create ssh key
```bash
ssh-keygen -t ed25519 -C <youremail>
```
link ssh key with github
- click profile
- SSH and GPG keys
- New SSH key
```bash
cat ~/.ssh/id_ed25519.pub
```
- copy output
- paste output to github
- verify ssh connection
```bash
ssh -T git@github.com
```
[Test your SSH Key](https://docs.github.com/en/authentication/connecting-to-github-with-ssh/testing-your-ssh-connection)  
clone github project with SSH
```
git clone git@github.com:username/git_test.git
```
create file(s) and watch
```bash
git status
```
```bash
git add filename
```
see commits
```bash
git log
```

## CSS

### Box Model

```css
html {
  box-sizing: border-box;
}
*, *::before, *::after {
  box-sizing: inherit;
}
```



