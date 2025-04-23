 
 # Требования:
1. Джейлбрейк
2. KUAL
3. Подключение к интернету

# Настройка:
1. Распаковать папку KindleTeleSync в папку extensions на ваш Kindle.
2. Создать своего бота в телеграме:
## Важно: Для использования необходимо создать своего телеграм бота и получить api token
### Как получить токен в BotFather:
***
	1. Отправьте в чат с BotFather команду /newbot.
	2. Введите название бота — в этой категории особых ограничений нет.
	3. Введите юзернейм бота — его техническое имя, которое будет отображаться в адресной строке. К нему уже больше требований: юзернейм должен быть уникальным, написан на латинице и обязательно заканчиваться на bot. Так «Телеграм» защищается от злоумышленников, которые могут выдавать ботов за реальных людей.
	4. Готово!
	5. BotFather пришлет токен бота — скопируйте его и вставьте в config.json "bot_token":"ВАШ_ТОКЕН"
	Храните его в секрете и никому не передавайте!
***
3. В KUAL найти KindleTeleSync - запустить, полученный chatid (в самом верху экрана Киндла и в телеграме отобразится ваш чат айди (chat_id)) вписать в файле config.json в секцию chat_id:0 где 0 - заменить на ваш chat_id 
Настройка завершена.

Теперь боту можно пересылать сообщения с файлами/файлы , при запуске KindleTeleSync на вашем Kindle будет их скачивать в указанное место в конфиге (по умолчанию в папку books). 
Так же в конфиге можно указать форматы файлов которые будут разрешены для скачивания, по умолчанию это epub,mobi,pdf,zip,fb2
Подробные логи пишутся в файл sync.log, краткие информационные сообщения выводятся вверху экрана. 

Настройки можно вбить\поменять с внешнего устройства, запустив соответсвующий пункт меню в KOReader (см. скриншоты)

Большие файлы могут долго скачиваться, имейте это в виду!
Первая публичная версия, могут быть ошибки. 
Версия 1.2.2

Автор — [XroM](https://4pda.to/forum/index.php?showuser=237553)

За тесты и помощь спасибо [Dark_AssassinUA](https://4pda.to/forum/index.php?showuser=2610359)

ENG:
# Requirements:
1. Jailbreak
2. KUAL
3. Internet connection

# Customization:
1. Unzip the KindleTeleSync folder to the extensions folder on your Kindle.
2. Create your own bot in Telegram:
## Important: To use it, you need to create your own telegram bot and get an api token.
### How to get a token in BotFather:
***
	1. Send the /newbot team to the chat with BotFather.
	2. Enter the name of the bot — there are no special restrictions in this category.
	3. Enter the bot's username— its technical name, which will be displayed in the address bar. There are already more requirements for it: the username must be unique, written in Latin and must end with bot. This is how Telegram protects itself from intruders who can impersonate bots as real people.
	4. It's done!
	5. BotFather will send the bot token — copy it and paste it into the "api token section"
***
Keep it secret and do not share it with anyone!

3. In KUAL, find KindleTeleSync - run, enter the received chatid (at the very top of the Kindle screen and your chat ID (chat_id) will be displayed in the telegram) in the config.json file in section the chat_id:0 where 0 is replaced by your chat_id 
The setup is complete.

Now you can send messages with files/files to the bot. When you start KindleTeleSync on your Kindle, it will download them to the specified location in the config (by default, to the books folder). 
You can also specify the file formats that will be allowed for download in the config. By default, these are epub,mobi,pdf,zip,fb2
Detailed logs are written to the sync.log file, and brief information messages are displayed at the top of the screen. 
Large files can take a long time to download, keep this in mind!
The first public version, there may be errors. 
Version 1.2.2

Author — [XroM](https://4pda.to/forum/index.php?showuser=237553)


Thanks  for the tests and help to [Dark_AssassinUA](https://4pda.to/forum/index.php?showuser=2610359)

 <img src="https://github.com/user-attachments/assets/267e4466-4f9d-4bb4-8ca8-a5766d15935b" width="300">
 <img src="https://github.com/user-attachments/assets/865cfec1-f7c8-42ad-bbf5-1b4f5366ae00" width="300">
 <img src="https://github.com/user-attachments/assets/8b8baab8-bc0a-405f-ba31-75c023e66be7" width="300">
 <img src="https://github.com/user-attachments/assets/1d684896-3ff8-4098-aa39-bea1a363bf61" width="200">
 <img src="https://github.com/user-attachments/assets/76e0921d-db5f-4c4d-8b41-2a67790456d2" width="200">
