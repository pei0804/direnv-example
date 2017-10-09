# direnv-example

1.install

```
$ make mac-install
or
$ make win-install
```

2.setting



```
# ~/.bashrc
eval "$(direnv hook bash)"
```


```
# ~/.zshrc
eval "$(direnv hook zshrc)"
```

```
# ~/.config/fish/config.fish
eval (direnv hook fish)
```


```
# ~/.cshrc
eval `direnv hook tcsh`
```


3.direnv run

```
$ make direnv
```

4.run

```
make run
```