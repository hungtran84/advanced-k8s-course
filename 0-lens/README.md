# Managing k8s clusters with Lens

## Installing Lens using package manager

- MacOS Brew

```shell
brew install --cask lens
```

- Windows

```cmd
choco install lens -y
```

- CentOS

```shell
sudo yum install snapd
sudo systemctl enable --now snapd.socket
sudo ln -s /var/lib/snapd/snap /snap
sudo snap install kontena-lens --classic
```

> kontena-lens 4.2.5 from Mirantis Inc (jakolehm) installed

- Ubuntu/Debian

```shell
sudo apt install snapd
sudo snap install kontena-lens --classic
````

> kontena-lens 4.2.5 from Mirantis Inc (jakolehm) installed

## Installing Lens from source

https://k8slens.dev/

