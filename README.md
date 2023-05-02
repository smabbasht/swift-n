# The Swift n

The `Swift n` is a nice little tool to open files or directory in your favourite editor in a blazingly fast way. <br>
It basically allows you to find fuzzily the file and zoxide into the relevant directory if provided giving you workflow
the ultimate smoothness.

## Usage

There are multiple ways to open your file or folder to ensure that you get your setup in minimum steps:

`n                               ` <br> opens fzf interface and opens selected file from fzf in your editor. <br> <br>
`n [search-pattern]              ` <br> opens fzf with search-pattern and opens selected file in your editor. <br> <br>
`n [folder-name] [search-pattern]` <br> zoxides into folder-name and opens fzf result in your editor. <br> <br>
`n [folder-name] .               ` <br> zoxides into folder-name and opens that directory in your editor.

## Install

There are a few easy steps to install the tool which are as follows: <br>

1.  Clone the repository in your preffered directory:

<!---->

    git clone https://github.com/smabbasht/swift-n

2.  Rename variable editor in the script `n`. The editor is by default set to
    `nvim`, you could rename it as you like for e.g: `vim`, `code`, `clion` etc.
3.  Add script `n` to your path:
    You will have to add the script `n` to your path in order to use directly use
    it from anywhere:
    *   If you use `Fish`, add this in your `~/.config/fish/config.fish`:
    ```fish
    fish_add_path /path/to/swift-n
    ```
    *   If you use `Bash`, add this in your `~/.bashrc`
    ```bash
    export PATH="/path/to/swift-n:$PATH"
    ```
    *   If you use `Zsh`, add this in your `~/.zshrc`
    ```zsh
    export PATH=$PATH:/path/to/swift-n
    ```

## Plan

The plan is to extend this helper tool to make it a `tmux-session` helper
too. This option will be invoked using flags. I want suggestions on as to do it
or not since those who don't use `TMUX` might find this an overkill.

## Support

You can support this project by giving this repo a :star2: and by sharing it
with peers :two_men_holding_hands: <br> PRs are highly encouraged.
