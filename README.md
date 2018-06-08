# Git OwO

A plugin to make git more readable and fun!

Based on the [OWO Chrome extension](https://chrome.google.com/webstore/detail/owo/jolaggjkdhhgcdhcjjhfkkbllefoggob?hl=en) by leafysweetsgarden.

## Example workflow

```bash
git add -A
git commit -m "Corrected bug!"
```

That is _such a boring commit message!_ Using this plugin that commit message can become more readable:

```bash
git add -A
git owo commit -m "Corrected bug!"
# Translates to "Cowwected bug ^w^" 
``` 

So much better! :zap:

## Setup

```bash
git clone https://github.com/mattstruble/git-owo.git
```

Then add the following to your `~/.bash_profile` (or `~/.zshrc`, or whatever profile you use): 

```bash
export PATH=path/to/git-owo:$PATH
```