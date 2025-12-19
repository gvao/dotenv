ZSH_SCRIPTS="$HOME/dotenv/zsh"

source_if () {
  [ -r $1 ] && source $1
}

source_if "~/dotenv/.zshrc_original"
# source_if "$ZSH_SCRIPTS/env.sh"
# source_if "$ZSH_SCRIPTS/path.sh"
# source_if "$ZSH_SCRIPTS/aliases.sh"
# source_if "$ZSH_SCRIPTS/plugins.sh"
# source_if "$ZSH_SCRIPTS/prompt.sh"

# Syntax highlight
source_if "/usr/share/zsh-syntax-highlighting/zsh-syntax-highlighting.zsh"

setopt autocd           # cd só digitando o nome da pasta
setopt correct          # corrige comandos
setopt histignoredups   # histórico sem duplicar linhas
setopt interactivecomments

HISTFILE=~/.zsh_history
HISTSIZE=4000
SAVEHIST=4000
