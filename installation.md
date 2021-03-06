***  
 ***<center><big>ИНСТРУКЦИЯ ПО УСТАНОВКЕ СИСТЕМЫ КОНТРОЛЯ ВЕРСИЙ (СКВ) GIT   
 НА ПЭВМ С ОПЕРАЦИОННОЙ СИСТЕМОЙ WINDOWS.</big></center>***   
***  
   
1. Необходимо узнать тип операционной системы (ОС):     
откройте _"Проводник"_ (нажмите на клавиатуре сочетание клавиш _"Win+E"_),   
далее кликните правой кнопкой мыши (ПКМ) по иконке _"Мой компьютер"_ (1)   
--> далее нажмите левой кнопкой мыши (ЛКМ) _"Свойства"_ (2):   

![Рис.1](./img/1.png "Мой компьютер -->Свойства")  

2. В октрывшемся окне найдите строку:
_"Тип системы: 64-разрядная операционная система"_(3):   

![Рис.2](./img/2.png "64 разрядная ОС")   

3. Откройте браузер Интернета (например _"Google Chrome"_),   
зайдите на поисковый сайт, например: https://www.google.com,     
в строке поиска введите _"GIT"_ (1), откройте ссылку: https://git-scm.com (2):   

![Рис.3](./img/3.png "google.com")   

4. На сайте https://git-scm.com (4) перейдите в раздел _"Downloads"_ (5):   

![Рис.4](./img/4.png "Раздел Загрузки")   

5. Для скачивания нажмите на ссылку на слове _"Windows"_ (6),   
или сразу на ссылку _"Download 2.32.0 for Windows"_:   

![Рис.5](./img/5.png "Выбор дистрибутива")   

6. Нажмите на ссылку _"64-Bit Git for Window Setup"_ (7):   

![Рис.6](./img/6.png "дистрибутив для 64 битной ОС")   
 
и сохраните на локальный диск (8):

![Рис.6.1](./img/6_1.png "дистрибутив для 64 битной ОС")   

7. Перейдите в _"Проводник"_, далее в папку _"Downloads"_ или (Загрузки),   
найдите скачанный файл _"Git-2.32.0.-64-bit.exe"_ и запустите его:   

![Рис.7](./img/7.png "Запуск инсталлятора")   

8. Нажмите _"Запустить"_:   

![Рис.8](./img/8.png "Запустить")   

9. Далее следуйте инструкции _"Next"_:   

![Рис.9](./img/9.png "Next")   

10. Выберете папку для установки, и нажмите _"Next"_:   

![Рис.10](./img/10.png "Папка для установки")   

11. Выберете название папки для ярлыка, и нажмите _"Next"_:   

![Рис.11](./img/11.png "Папка для ярлыка")   

12. Выберете текстовый редактор который будет установлен по-умолчанию, и нажмите _"Next"_:   

![Рис.12](./img/12.png "Текстовый редактор")   

13. Выберете компоненты для установки, и нажмите _"Next"_:   

![Рис.13](./img/13.png "Компоненты для установки")   

14. Выберите среду способ использования из командной строки:   
(_"Use Git from Git Bash only"_ - использование только из командной строки Bash;   
_"Use Git from the Windows Command Prompt"_ - использование командной строки Bash,   
а также минимальный набор команд Git из консоли Windows;    
_"Use Git and optional Unix tools from the Windows Command Prompt"_   
- использование Git и утилит Unix из командной строки Windows,   
в этом случае будут перезаписаны некоторые утилиты Windows, например _"find"_ и _"sort"_),   
и нажмите _"Next"_:   

![Рис.14](./img/14.png "Способ использования командной строки")   

15. Выберете какую библиотеку SSL / TLS вы будете использовать для HTTPS:   
(_"OpenSSL"_ - сертификаты сервера будут проверяться с использованием Unix-файла _"ca-bundle.crt"_.   
_"Windows Secure Channel"_ - сертификаты сервера будут проверяться с использованием стандартной библиотеки Windows),   
и нажмите _"Next"_:   

![Рис.15](./img/15.png "Библиотека SSL / TLS")   

16. Выберете способ обработки окончания строк:   
(_"«Checkout Windows-style, commit Unix-style line endings»"_   
- это значение гарантирует, что Git преобразует LF в CRLF при проверке текстовых файлов.   
При выполнении текстовых файлов CRLF также преобразуется в LF.   
Это мера совместимости для защиты новых строк в текстовых файлах,   
что позволяет легко работать с текстовыми файлами в Windows и на платформах Unix),   
и нажмите _"Next"_:   

![Рис.16](./img/16.png "Конвертация конца строки")   

17. Выберете эмулятор терминала:   
(_"MinTTY"_ - терминал Unix; _"Windows"_ - стандартный терминал Windows),   
и нажмите _"Next"_:   

![Рис.17](./img/17.png "Эмулятор терминала")   

18. Выберете способ внесения изменения по-умолчанию:   
простое смещение вперёд — иначе создание коммита слияния,   
преобразование или перебазирование и получение изменений,    
нажмите _"Next"_:   

![Рис.18](./img/18.png "Дополнительные параметры")   

19. Включите или отключте менеджер учетных данных
(_"Git Credential Manager"_), и нажмите _"Next"_:      

![Рис.19](./img/19.png "Дополнительные опции")   

20. Включите дополнительные опции и функции:
(_"File system caching"_ - кэширование файловой системы,   
_"Symbolic links"_ - разрешить символьные ссылки),   
и нажмите _"Next"_:   

![Рис.20](./img/20.png "Дополнительные функции")  

21. Выберете эксперементальные опции, и нажмите _"Install"_:   

![Рис.21](./img/21.png "Эксперементальные опции")   

22. Установить галочку запустить Git Bash ("_Launch Git Bash"_)   
и запустите процесс установки, нажав кнопку _"Finish"_:   

![Рис.22](./img/22.png "Launch Git Bash")   

*Инсталляция программы СКВ GIT успешно завершена!* 

23. Проверить версию GIT можно выполнив команду:   
git --version   

![Рис.23](./img/23.png "Git Verion")   

***
