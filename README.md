terragrunt-zsh-plugin
#####################

Plugin for Terragrunt adds
- autocomplete for commands
- autocomplete for global options
- alias

# Requirements

* [Terraform](https://www.terraform.io/downloads.html)
* [Terragrunt](https://terragrunt.gruntwork.io/docs/getting-started/install/) 

# Install

* [Oh My Zsh](#oh-my-zsh)

## Oh My Zsh

1. Clone repository into `${ZSH_CUSTOM}/plugins` (by default `$ZSH_CUSTOM` points to `~/.oh-my-zsh/custom`)

```sh
git clone https://github.com/jsporna/terragrunt-zsh-plugin \
    ${ZSH_CUSTOM:-~/.oh-my-zsh/custom}/plugins/terragrunt
```

2. Add te plugin to the list of plugins in `~/.zshrc` for Oh My Zsh to load:

```sh
plugins=(... terragrunt)
```

3. Start new terminal session.

# Usage

* Type `terragrunt` of `tg` into your prompt and hit `TAB` to see available completion options