<p align="center">
  <img src="https://raw.githubusercontent.com/filebrowser/logo/master/banner.png" width="550"/>
</p>

![Preview](https://user-images.githubusercontent.com/5447088/50716739-ebd26700-107a-11e9-9817-14230c53efd2.gif)

## Файловый браузер для Kindle
Русскоязычный форк проекта https://github.com/guo-yong-zhi/kindle-filebrowser 
Все вопросы и предложения просьба отправлять автору на ГитХабе, это всего лишь перевод.

1. Убедитесь что на вашем Kindle получен джейлбрейк!
2. Скачайте zip-файл плагина, распакуйте папку в каталог extensions в корне Kindle.

3. После распаковки откройте KUAL и в меню вы найдете кнопку [Файловый браузер], которая содержит несколько опций.
    * 【Запуск】чтобы запустить WEB-сервис без авторизации и оставить WEB-сервис работать в фоне(использовать с осторожностью - в публичных Wi-Fi сетях любой сможет получить доступ к файлам на вашем устройстве)
    * 【Запуск (Авторизация)】чтобы запустить WEB-сервис с аутентификацией входа и оставить WEB-сервис работать в фоне(имя пользователя и пароль по умолчанию: admin)  
    * 【Start (root)】позволяет WEB-сервису получить доступ к корневому каталогу и оставить WEB-сервис работать в фоне(необходимо до запуска в терминале выполнить mntroot rw и mntroot ro) ИСПОЛЬЗОВАТЬ ТОЛЬКО С ПОЛНЫМ ПОНИМАНИЕМ СВОИХ ДЕЙСТВИЙ!НЕОСТОРОЖНЫЕ ДЕЙСТВИЯ МОГУТ ПРИВЕСТИ К ОКИРПИЧИВАНИЮ УСТРОЙСТВА!
    * 【Состояние】показывает состояние WEB-сервиса(Запущен или не запущен)
    * 【Остановить】останавливает  WEB-сервис
    * 【Обновить】Обновляет WEB-сервис до актуальной версии
    * 【Сброс】Удаляет filebrowser.db что ведет к сбросу конфигурации
    
4. Если WiFi на устройстве был отключен до запуска WEB-сервиса - WiFi будет автоматически включен и отключен после остановки WEB-сервиса.

5. Когда WEB-сервис включен, вы увидите IP-адрес в верхней части интерфейса Kindle и сможете получить доступ к файлам устройства через браузер в той же Wi-Fi сети.
Экран Kindle будет оставаться включенным и устройство не перейдет в спящий режим при запуске WEB-сервиса.
Если вы вручную отключите WiFi во время использования (например, войдете в авиарежим или будет потеряно соединение с WiFI сетью) WEB-сервис автоматически завершит работу.

6. Нажмите кнопку включения, чтобы остановить сервис, когда вы закончите пользоваться файловым браузером и Kindle вернется в свое нормальное состояние, а если вы снова нажмете кнопку включения то экран заблокируется и устройство будет нормально спать. На некоторых устройстваъ это может не сработать поэтому, пожалуйста, остановите WEB-сервис вручную, войдя в режим самолета или используя опцию [Остановить].

7. Если отображается IP - это означает что WEB-сервис не был должным образом остановлен, и пользователю напоминают что WEB-сервис все еще запущен.
При нормальных обстоятельствах IP исчезнет при нажатии кнопки включения, в противном случае попробуйте нажать [Остановить] или перезагрузить устройство. И наоборот, исчезновение IP означает что WEB-сервис был полностью остановлен что гарантирует что никакие фоновые задачи не потребляют энергию.

8. Если положение  IP и других подсказок не центрировано, вы можете изменить цифры в файле COL.txt вручную. Например, если изменить значение с 10 на 20, подсказки будут больше смещены вправо.
## Заметки
* Бинарный файл находится в extensions/filebrowser/filebrowser`и взят отсюда https://github.com/filebrowser/filebrowser ，использована версия linux-armv7  
* На сайте Book Companion есть подробные инструкции：https://bookfere.com/post/823.html
## Больше плагинов автора для Kindle
* [**kindle-filebrowser**](https://github.com/guo-yong-zhi/kindle-filebrowser) 网页文件管理器 
* [**MailPush**](https://github.com/guo-yong-zhi/MailPush) 使用第三方邮箱推送文件
* [**BlockKindleOTA**](https://github.com/guo-yong-zhi/BlockKindleOTA) 阻止Kindle升级
* [**KOSSH**](https://github.com/guo-yong-zhi/KOSSH) WiFi连接的轻量ssh服务器
* [**ShuffleSS**](https://github.com/guo-yong-zhi/ShuffleSS) 打乱锁屏图片顺序
