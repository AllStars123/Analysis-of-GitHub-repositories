# Analysis-of-GitHub-repositories

1. Скачайте образ и соберите его, находясь в той же директории, где расположен Dockerfile:
docker build -t img-hdp-zeppelin .
Поднимаем новый контейнер из образа:
docker run -it --name zeppelin -p 50090:50090 -p 50075:50075 -p 50070:50070 -p 8042:8042 -p 8088:8088 -p 4040:4040 -p 4044:4044 -p 8888:8888 --hostname localhost img-hdp-zeppelin
Если не первый раз запускать, то:
 docker start -i zeppelin
2. Переходим на  http://localhost:8888:

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/1.png)
3. Настраиваем интерпретатора Spark

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/2.png)

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/3.png)

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/4.png)

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/5.png)

![Image alt](https://github.com/AllStars123/Analysis-of-GitHub-repositories/blob/main/7.png)


<h3>Авторы</h3>
* Луценко Дмитрий
* Пурнов Никита
