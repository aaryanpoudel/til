- version control system by microsoft which uses git
### Init Setup (Linux)

```bash
sudo apt install git;

#init config
git config --global user.name "aaryanpoudel"; git config --global user.email "aaryan.poudel1@gmail.com"
```

### Add ssh key to github

1. Generate id_ed25519.pub 
```bash
#Generating ssh key
ls -al ~/.ssh;
ssh-keygen -t ed25519 -C "aaryan.poudel1@gmail.com";
eval "$(ssh-agent -s)";
ssh-add ~/.ssh/id_ed25519;
cat ~/.ssh/id_ed25519.pub;
```
2. In github, add the .pub key in Settings> Add SSH Keys