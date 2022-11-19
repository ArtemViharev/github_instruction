# Инструкция по использованияю GitHub

## Что такое GitHub?
*GitHub* – это веб-интерфейс, в котором можно хранить свои репозитории Git, а также эффективно отслеживать и управлять своими изменениями. С его помощью разные разработчики имеют доступ к коду одного проекта. У вас есть возможность вносить свои собственные изменения в проект одновременно с другими разработчиками.

Например, если вы вдруг допустили какую-то ошибку во время внесения изменений, вы можете легко вернуться к предыдущему этапу, где ошибки еще нет.



<table>
    <caption>
        <h2>Для чего нужно использовать GitHub?</h2>
    </caption>
    <tr>
        <td><b>Эффективное управление проектами</b></td>
        <td>GitHub – это своего рода хранилище ваших репозиториев. GitHub позволяет разработчикам работать над одним проектом, находясь в разных местах.<br>
        С помощью GitHub вы можете легко отслеживать внесенные вами изменения и управлять ими, а также проверять ход вашей работы над проектом.</td>
    </tr>
    <tr>
        <td><b>Простое сотрудничество</b></td>
        <td>С GitHub разработчики со всего мира могут работать вместе на одним проектом без каких-либо проблем.
        <br>
        Команды разработчиков могут оставаться на одной странице во время совместной работы над проектом и могут легко организовывать и эффективно управлять проектом.</td>
    </tr>
    <tr>
        <td><b>Открытый исходный код</b></td>
        <td>GitHub – это бесплатная система с открытым исходным кодом. Это означает, что разработчики могут легко получить доступ к различным типам кода/проектов, которые они могут использовать для обучения и развития своих навыков.</td>
    </tr>
    <tr>
        <td><b>Универсальность</b></td>
        <td>Это свойство GitHub очень важно. GitHub – это веб-интерфейс не только для разработчиков. Его также могут использовать дизайнеры, писатели и все, кто хочет отслеживать историю своих проектов.</td>
    </tr>
</table>


## GitHub плюсы

* Бесплатное обслуживание, хотя есть и платные.
* Очень быстрый поиск в структуре репозиториев.
* Большое сообщество и легко найти помощь.
* Он предлагает практические инструменты для сотрудничества и хорошую интеграцию с Git.
* Легко интегрируется с другими сторонними сервисами.
* Он также работает с TFS, HG и SVN.

## GitHub недостатки

* У него есть ограничения по пространству, так как вы не можете превышать 100 МБ в одном файле, в то время как репозитории ограничены 1 ГБ в бесплатной версии.
## Преимущества и недостатки GitLab

### Преимущество

* Бесплатный план без ограничений, но есть планы оплаты.
* Это лицензия с открытым исходным кодом.
* Разрешает самостоятельный хостинг на любом плане.
* Он очень хорошо интегрирован с Git.

### Недостатки

* Его интерфейс может быть несколько медленнее по сравнению с конкурентами.
* Есть несколько общих проблем с репозиториями.

![Переход](http://old.angularfirebase.com/images/thumbs/git-01.png)

## Чтобы скопировать репозиторий с GitHub:

---
1. Нужно взять ссылку в GitHub, нажав на кнопку code.
2. Зайти в терминал на своем компьютере.
3. Командой git clone ссылка на репозиторий из GitHub *"git clone ссылка на репозиторий из GitHub"* мы переносим репозиторий из GitGub.

## Чтобы перенести свой репозиторий на GitHub:  
---
1. Чтобы залить свой репозиторий, необходимо иметь свой аккаунт на GitHub.
2. Далее на сайте в правом верхнем углу нажать плюсик, выбрать "new repository", дать ему имя и нажать кнопку «создать».
3. Далее мы идем в наш терминал и вводим следующую команду: __git remote add origin *<ссылка на репозиторий>*__
4. Далее __git branch -M main__ - указываем, что основная ветка main
5. Далее __git push -u origin main__ - отправляем репозиторий (иногда просит просто git push)

  
## Чтобы поучаствовать в чьем-то проекте на GitHub:  
---
Мы можем справа вверху в GitHub в нужном репозитории нажать Fork.

И тогда дубликат исходного репозитория копируется к нам в аккаунт и с ним мы можем работать. Мы ответвлились. Мы можем работать на нем, скопируя на свой терминал командой __git clone__ (смотри инструкцию выше) и дальше работать на нем, не забывая "пушить", перенося наши коммиты в наше ответвление в репозитории на GitHub.

Работаем мы только в своей ветке, ее нужно создать как только мы залили к себе чужой репозиторий и хотим начать работать с ним!

Чтобы запросить слияние с основной веткой в проекте, нам необходим __pull request__.

### Что для этого нужно:
Как только мы сделали все необходимые изменения, закомитили их, перенесли (запушили) их в GitHub, проверили что все точно так, как нам нужно, то в GitHub сверху нажимаем кнопку "Pull request" , далее "Compare and request" пишем наш комментарий и отправляем создателю репозитория.