# lazy-load

Adds a function *_lazy_load* that loads a zsh completion when pressing tab instead of at zsh shell startup time.

## Usage

```
_lazy_load $CMD $COMPLETION_CMD
```

## Examples

```
_lazy_load pipenv "_PIPENV_COMPLETE=zsh_source pipenv"
_lazy_load rustup "rustup completions zsh"
_lazy_load hcloud "hcloud completion zsh"
_lazy_load kubectl "kubectl completion zsh"
_lazy_load helm "helm completion zsh"
```

## Installation

### Antidote
```
anidote install goarano/zsh-lazy-load
```

### Zgen
```
zgen load goarano/zsh-lazy-load
```

### Antigen
```
antigen bundle goarano/zsh-lazy-load
```
