# otus-hw-docker

docker run hello-world
docker images
hello-world   latest    feb5d9fea6a5   12 months ago   13.3kB
docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
docker run -it ubuntu bash
docker ps
CONTAINER ID   IMAGE     COMMAND   CREATED          STATUS          PORTS     NAMES
8380e6b34a1a   ubuntu    "bash"    27 seconds ago   Up 27 seconds             dreamy_robinson
root@8380e6b34a1a:/# ls
bin  boot  dev  etc  home  lib  lib32  lib64  libx32  media  mnt  opt  proc  root  run  sbin  srv  sys  tmp  usr  var
root@8380e6b34a1a:/# cd dev
root@8380e6b34a1a:/# cd /
root@8380e6b34a1a:/# cd home
root@8380e6b34a1a:/home# mkdir test
root@8380e6b34a1a:/home# cd test
exit
C:\Users\79994>docker run -it ubuntu bash
root@2593af09f0f9:/# cd home
root@2593af09f0f9:/home# ls
root@2593af09f0f9:/home#
Почему пропала?
Мб этот ответ : Потому что вы не должны ничего руками править в работающем контейнере, описывайте все это в сценарии сборки. Или же выносите этот файл из контейнера и монтируйте потом.

docker run --name otusDB -d -p 5431:5432 -e POSTGRES_PASSWORD=test postgres:13.1
*создали табилцу с 1 строкой* 
docker stop otusDB
docker ps
docker rm otusDB
docker run --name otusDB -d -p 5431:5432 -e POSTGRES_PASSWORD=test postgres:13.1
-Таблицы нет. 
Если мы удалям образ, все данные теряются (говорили на лекции). 

