# rpi-web-man
A web-based management tool for Raspberry PI / Raspbian.

YES, indeed it is powered by `Node.js v6` on `Raspberry PI 3`.

>  This project is inspired by [vaslabs's](https://github.com/vaslabs) [pi-web-agent](https://github.com/vaslabs/pi-web-agent/wiki/A-web-application-agent-for-the-Raspberry-Pi) which is unfortunately not working for my Raspberry PI (I still don't know why...)



## 1. Features

* A web-based management tool for Raspberry PI. You can treat it like the web interface to the routers.
* Modern user interface.
* You can easily use it to
  * Monitor CPU & memory usage / CPU temperature
  * Start / stop / restart services
  * Web-based terminal
  * Reboot
* It also provide RESTful APIs for the further integrations.



## 2. Reuqirements
### 2.1 Equipment
* [**Raspberry PI 3 Model B**](https://www.raspberrypi.org/products/raspberry-pi-3-model-b/) with the latest **Raspbian OS** installed
* **Node.js v6.0**
  + By default Node.js v0.x is installed in the Raspbian, you need to uninstall it first if you want to have a try of this project.

    ```shell
    $ sudo apt-get uninstall nodejs
    ```

  + Follow this [instruction](https://nodejs.org/en/download/package-manager/#debian-and-ubuntu-based-linux-distributions) to install Node.js v6.x on your Raspbian.

    ​


## 3. How to Install

### 3.1 Clone to your Raspberry PI

```shell
cd /opt
sudo git clone https://github.com/MagicCube/rpi-web-man.git
```

### 3.2 Install

```shell
$ cd rpi-web-man
$ ./install.sh
```

### 3.3 Automatically Run at Startup

It's easy to make a node program run automatically as a service at startup. Give me somtime, I'll let you know how, or you can just google it. It's on my **TODOLIST** already.

### 3.4 Uninstall

Don't like it any more? Simply remove  `rpi-web-man` by delete the project folder.

###

## 3. How to Upgrade

After a new version comes out, you can simply use the following command to upgrade your `rbi-web-man`.

```shell
$ cd rpi-web-man
$ ./upgrade.sh
```

## 4. How to Run

```
$ cd rpi-web-man
$ ./run.sh
```
