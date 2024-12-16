**Enable wsl on Wiindows 11**

Go to `Turn windows features on or off`, check:

    - Virtual Machine Platform
    - Windows Subsytem for Linux

`Restrat your computer.`

>WSL status

```
wsl --status
```

>wsl set default version

```
wsl --set-default-version 2
```

>wsl update

```
wsl --update
```

>wsl list posible linux installations

```
wsl --list --online
```

>Install Linux distro

```
wsl --install -d distro_name (from first column)
```

>Example

```
wsl --install -d kali-linux
```
