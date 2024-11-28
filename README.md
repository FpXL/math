# Чтобы посмотреть конспекты через Obsidian

Создайте [Personal Access Token в Github](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic) и сохраните его  

Поставьте галочку в настройках доступов ключа Access Token scope: repo. 
![image](https://github.com/user-attachments/assets/2d44d03a-b3b5-4992-87e7-883c7c186b2f)

Установите Obsidian https://obsidian.md/

Добавьте Git Community Plugin в настройках Obsidian: Settings > Community Plugins > Browse > в поиске введите 'Git' > Install
<img width="1207" alt="Screenshot 2024-11-07 at 8 03 19 PM" src="https://github.com/user-attachments/assets/9a094bd6-8161-4805-9a37-d496f6453e62">

Создайте папку верхнего уровня в вашем Obsidina Vault (в ней будут жить все конспекты) например `math-remote`

Вызовите командную строку: `CMD/Ctrl + P`, начните вводить и выберите `Clone an existing remote repo`

Вставьте вот этот URL в открывшемся диалоге 
`https://ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX@github.com/FpXL/math.git`, замените `ghp_XXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXXX` на ваш Github Access Token 

Следующим шагом вбейте и выберите название папки, которую вы создали выше

Следующим шагом нажмите Enter чтобы пропустить вопрос

Просматривать конспекты можно в режиме редактирования и в режиме просмотра. Во втором формулы LaTeX будут отображаться в читабельном виде. Переключайся между режимами с помощью Ctrl/Cmd + E. 


# Чтобы добавить свои изменения:
1. Напиши @Endorphine13 или @pooteeweet, чтобы тебя добавили в проект в Github
2. Если добавляешь заметку по теме, по которой еще нет страницы в проекте, то проверь, что никто из участников не работает над этой темой, добавь карточку с темой в Github > Projects > Math добавь карточку с темой. Это нужно, чтобы избежать дубликатов. 
3. Выбери команду `CMD/Ctrl + P` > `Git: Create New Branch`, введите название новой ветки без пробелов, через тире > `Enter`
4. Сделай изменения в существующих страницах 
	1. Добавь новую через `Cmd/Ctrl + O` > введи заголовок новой страницы > `Enter` 
5. Просмотри свои изменения в режиме просмотра, чтобы убедиться, что все форматирование и особенно формулы правильно отображаются.
6. Запусти команду  `Git: commit all changes`
7. Создай pull request `CMD/Ctrl + P` > `Git: Push` чтобы отправить запрос на включения ваших изменений
8. Выбери `origin`
9. Следующим шагом введи название ветки в формате `origin/{название-твоей-ветки-шаг}`
10. Зайди на https://github.com/FpXL/math/ и создай pull request, добавь описание 
11. Вы великолепны! 

Чтобы стянуть обновления, внесенные другими ребятами, переключись на ветку main в правом нижнем углу и запустите команду `CMD/Ctrl + P` > `Git: Pull`

Для вводе формул с синтаксисом LaTeX, добавь **LaTeX Suite** плагин в `Settings > Community Plugins > Browse > Install`, его нужно активировать (Enable) в списке всех установленных плагинов.


# Для ревью изменений, внесенных другими участниками 

1. Переключись на ветку main в правом нижнем углу 
2. Стяни последние изменения через`CMD/Ctrl + P` > `Git: Pull`
3. Переключись на нужную ветку c изменениями через 
	1. `CMD/Ctrl + P` > `Git: Switch Branch` или 
	2. `Git: Switch to remote branch` — тут вводи название через `origin/{название-твоей-ветки-шаг}`
4. Переключайся между режимами просмотра и редактирования с помощью `Ctrl/Cmd + E`
5. В Github > `Add your review` > `Approve` ИЛИ `Comment` для одобрения или чтобы добавить комментарий с нужными поправками. Оставляй комментрий прямо на строке, к которой он относится. При просмотре кода  в Github справа есть `+` для этого. 


