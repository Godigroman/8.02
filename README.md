# Домашнее задание к занятию "`Что такое DevOps. СI/СD`" - `Клименко Олег`


### Инструкция по выполнению домашнего задания

   1. Сделайте `fork` данного репозитория к себе в Github и переименуйте его по названию или номеру занятия, например, https://github.com/имя-вашего-репозитория/git-hw или  https://github.com/имя-вашего-репозитория/7-1-ansible-hw).
   2. Выполните клонирование данного репозитория к себе на ПК с помощью команды `git clone`.
   3. Выполните домашнее задание и заполните у себя локально этот файл README.md:
      - впишите вверху название занятия и вашу фамилию и имя
      - в каждом задании добавьте решение в требуемом виде (текст/код/скриншоты/ссылка)
      - для корректного добавления скриншотов воспользуйтесь [инструкцией "Как вставить скриншот в шаблон с решением](https://github.com/netology-code/sys-pattern-homework/blob/main/screen-instruction.md)
      - при оформлении используйте возможности языка разметки md (коротко об этом можно посмотреть в [инструкции  по MarkDown](https://github.com/netology-code/sys-pattern-homework/blob/main/md-instruction.md))
   4. После завершения работы над домашним заданием сделайте коммит (`git commit -m "comment"`) и отправьте его на Github (`git push origin`);
   5. Для проверки домашнего задания преподавателем в личном кабинете прикрепите и отправьте ссылку на решение в виде md-файла в вашем Github.
   6. Любые вопросы по выполнению заданий спрашивайте в чате учебной группы и/или в разделе “Вопросы по заданию” в личном кабинете.
   
Желаем успехов в выполнении домашнего задания!
   
### Дополнительные материалы, которые могут быть полезны для выполнения задания

1. [Руководство по оформлению Markdown файлов](https://gist.github.com/Jekins/2bf2d0638163f1294637#Code)

---

### Задание 1


1. `Установите себе jenkins по инструкции из лекции или любым другим способом из официальной документации. Использовать Docker в этом задании нежелательно.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1227208562883956768/image.png?ex=662597c9&is=66244649&hm=bc9c67a1e20e1c568d6940fb2f6dbe99c41ead379666dde0912aa966d2083794&)
2. `Установите на машину с jenkins golang.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1227569387960270899/image.png?ex=66321c95&is=661fa795&hm=afa8ed1f66b83f386cb900b4e6e74768c3d80f397758316d78fda43d76381f0d&)
3. `Используя свой аккаунт на GitHub, сделайте себе форк репозитория. В этом же репозитории находится дополнительный материал для выполнения ДЗ.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1227951058056384633/image.png?ex=6633800a&is=66210b0a&hm=d5f4d2327e1e6b099a3b7a88f1e5b32f1933ec1c625f2e27db159cd5c5c22044&)
4. `Создайте в jenkins Freestyle Project, подключите получившийся репозиторий к нему и произведите запуск тестов и сборку проекта go test . и docker build ..`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229482321300947045/image.png?ex=662fd7a4&is=661d62a4&hm=a2418afd9b5ca8a82a931d6905e6427ba7dbe9313237eaab12964b8f87b0f4cc&)
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229482458161086587/image.png?ex=662fd7c4&is=661d62c4&hm=b3c40d666d3ec1b4abad87d4aa2ab5bc515e4020dc136eec8f323feb1dd79ce9&)
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229482579720147094/image.png?ex=662fd7e1&is=661d62e1&hm=afbf5f5ca6bc42080f768ee5a36d541bd11bb9e687f5a701f5d7b9f97b7651d1&)
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229482732195676210/image.png?ex=662fd806&is=661d6306&hm=7161c6381ae82c2e13e76f6c7bc6dda4db8f85708eb6863a55191d65a24d00ed&)


---

### Задание 2


1. `Создайте новый проект pipeline.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229499090203574292/image.png?ex=662fe742&is=661d7242&hm=07f1e2d3795e21f9797b25511f2b2958f25a85c4dc6c50d760ff63f5c35ee3d8&)
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229499279266025545/image.png?ex=662fe76f&is=661d726f&hm=2a4299ad610844f672fa89be24877017bdb7f30320750d5aab1d6d0abcbda952&)
2. `Перепишите сборку из задания 1 на declarative в виде кода.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229499473177219102/image.png?ex=662fe79d&is=661d729d&hm=506e07307946f4e100a0983aae582b90ac7dbbcd30926d7841d0bce470d7d8c3&)


---

### Задание 3


1. `Установите на машину Nexus.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229756714618716160/image.png?ex=6630d730&is=661e6230&hm=a963501c4ae2ce3d8485f3d5b51aa4ca26d00544f8a68c049b8a47e398d14b5b&)
2. `Создайте raw-hosted репозиторий.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1229819344679211089/image.png?ex=6625dcc4&is=66248b44&hm=faf7bdead8a958a5e2ab487023cd104cd7298842ef54ea5e3bcea57379d07e91&)
3. `Измените pipeline так, чтобы вместо Docker-образа собирался бинарный go-файл. Команду можно скопировать из Dockerfile.`
```
pipeline {
 agent any
 stages {
  stage('Git') {
   steps {git branch: 'main', url: 'https://github.com/Godigroman/sdvps-materials'}
    }
  stage('Test') {
   steps {
    sh 'go test .'
    }
   }
  stage('Build') {
   steps {
    sh 'docker run --rm -v "$PWD":$GOPATH/src/github.com/netology-code/sdvps-materials -w $GOPATH/src/github.com/netology-code/sdvps-materials -e GOOS=linux -e CGO_ENABLED=0 golang:1.16 go build -a -installsuffix nocgo -o ./app .'
    }
   }
    
  stage ('nexus deploy') {
   steps {
    nexusArtifactUploader(
      nexusVersion: 'nexus3',
      protocol: 'http',
      nexusUrl: '84.252.140.153:8081',
      groupId: '',
      version: '',
      repository: 'oleg',
      credentialsId: 'ef8cfd65-27ed-4298-aa78-bb5262afcf3f',
      artifacts: [
        [artifactId: '',
          classifier: '',
          file: 'app',
          type: '']
          ]
      )
   }
  }         
 }
}
```
4. `Загрузите файл в репозиторий с помощью jenkins.`
![](https://cdn.discordapp.com/attachments/1217104872672067615/1231557852053766164/image.png?ex=663764a1&is=6624efa1&hm=a574475e4364d15ff13b995a552000732bb4e0ba80666f68b94494c7b8e4a836&)
