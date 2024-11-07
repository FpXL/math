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

Чтобы добавить изменения:
1. выберите команду `CMD/Ctrl + P` > `Git: Create New Branch`
2. сделайте изменения
3. создайте pull request `CMD/Ctrl + P` > `Git: Pull` чтобы отправить запрос на включения ваших изменений

Вы великолепны! 
