
# How to install neofetch apply it first to see in command prompt in linux

-  first you need to update the system to any change happening

``` php
sudo apt update
```
- then input this to install the neofetch

```php
sudo apt install neofetch
```

- then to edit the bashrc

```php
nano ~/.bashrc
```

- then input the neofetch then **type ^O to save** and **^Q for quit**
## Install the docker

- update first the system

```php
sudo apt update
```

- for certificate

```php
sudo apt install apt-transport-https ca-certificates curl software-properties-common
```

- adding the key

```php
curl -fsSL https://download.docker.com/linux/ubuntu/gpg | sudo gpg --dearmor -o /usr/share/keyrings/docker-archive-keyring.gpg
```

- add the docker repository

```php
echo "deb [arch=amd64 signed-by=/usr/share/keyrings/docker-archive-keyring.gpg] https://download.docker.com/linux/ubuntu $(lsb_release -cs) stable" | sudo tee /etc/apt/sources.list.d/docker.list > /dev/null

```

- update again

```php
sudo apt update
```

- downloads docker ce

```php
sudo apt install docker-ce

```

- verify the docker

```php
sudo systemctl status docker
```

- for checking
```php
docker --version
```

- **optional to do it **
```php
sudo usermod -aG docker $USER
```

