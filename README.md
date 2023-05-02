# The Swift n

The `Swift n` is a nice little tool to open files or directory in your favourite editor in a blazingly fast way. <br> 
It basically allows you to find fuzzily the file and zoxide into the relevant directory if provided giving you workflow
the ultimate smoothness.


## Usage
There are multiple ways to open your file or folder to ensure that you get your setup in minimum steps:

`n                               ` <br> opens fzf interface and opens selection from fzf in nvim. <br> <br>
`n [search-pattern]              ` <br> opens fzf with search-pattern and opens selection in nvim. <br> <br>
`n [folder-name] [search-pattern]` <br> zoxides into folder-name and opens fzf result in nvim. <br> <br>
`n [folder-name] .               ` <br> zoxides into folder-name and opens nvim in that directory. 

## Install
There are a few easy steps to install the tool which are as follows: <br>
1. Clone the repository in your preffered directory: 
```
git clone https://github.com/smabbasht/swift-n
```
2. Rename variable editor in the script `n`. The editor is by default set to `nvim`, you could be rename it to your editor for e.g: `vim`, `code`, `clion` etc.
3. Add script `n` to your path:
You will have to add the script to your path in order to use directly use it from anywhere:
- If you use `Fish`, you have to add this in your `~/.config/fish/config.fish`:
```fish
fish_add_path /path/to/swift-n
```
- In Bash, you have to add this in your `~/.bashrc`
```bash
export PATH="/path/to/swift-n:$PATH"
```
- In Zsh, you could add this in your `~/.zshrc` 
```zsh
export PATH=$PATH:/path/to/swift-n
```

## Support
You could support the project by giving this repo a *star* and by sharing it
with other users. PRs are highly encouraged. 


