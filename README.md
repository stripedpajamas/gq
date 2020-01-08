# gq -- git quick
Fork of quickCommit by @joelwass (https://github.com/joelwass/quickCommit) personalized for my own workflow.

```bash
git add .
git commit -m "<message>"
git push origin head
```

### Installation

```bash
git clone https://github.com/stripedpajamas/gq.git
echo "source $(pwd)/gq/gq.sh" >> ~/.zshrc # or bash_profile, etc
```

### Use

```bash
~
$ cd project
~/project
$ echo "hello world" >> README.md
$ gq "Add hello world to readme"
```


