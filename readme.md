# Информация о проекте
Необходимо организовать систему учета для питомника, в котором живут
домашние и вьючные животные.

# Задание

## 1. Используя команду cat в терминале операционной системы Linux, создать два файла Домашние животные (заполнив файл собаками, кошками,хомяками и Вьючные животными заполнив файл Лошадьми, верблюдами и ослы), а затем объединить их. Просмотреть содержимое созданного файла.Переименовать файл, дав ему новое имя (Друзья человека).

 
 
![](./img/Task1.jpg)

```
cat > Домашние_животные

cat >  Вьючные_животными

ls

cat Домашние_животные

cat Вьючные_животными

cat Домашние_животные Вьючные_животными > Животные 

cat Животные

mv Животные "Друзья человека"

ls

ls -ali

```

## 2. Создать директорию, переместить файл туда.
![test](./img/Task2.png)
```
sudo mkdir Ферма

ls

sudo mv Друзья_человека Ферма/

ls

ls Ферма/*
```

# 3. Подключить дополнительный репозиторий MySQL. Установить любой пакет из этого репозитория

![](./img/Task3-1.png)
![](./img/Task3-2.png)
![](./img/Task3-3.png)
```
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

sudo apt-get update

sudo apt-get install mysql-server
```
# 4. Установить и удалить deb-пакет с помощью dpkg.

![](./img/Task4-2.png)

# 5. Выложить историю команд в терминале ubuntu
```
sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb
sudo apt-get update
sudo apt-get install mysql-server

sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb
sudo dpkg -i docker-ce-cli_20.10.133-0ubuntu-jammy_amd64.deb


sudo dpkg -r docker-ce-cli

history

```