# Отчет по курсовой работе
### Подготовка и установка
Поскольку я работаю на Windows, пришлось побороться с использованием корректного python.exe после установки.    
```
python --version
py --verion
```
не возвращали никакого результата.    
Долгий ресерч привел к узнаванию о том, что Windows может подменять python.exe на установочный из магазина приложений C:\Users\user\AppData\Local\Microsoft\WindowsApps\python.exe.  
Отключила связку, что помогло добраться таки к нужному .exe и установить Mkdocs:
<img width="535" height="212" alt="Capture" src="https://github.com/user-attachments/assets/83c467ae-b9e2-46ff-8e45-594bdfb80a5f" />  
Создание папки проекта и инициализация:    
<img width="383" height="180" alt="Capture1" src="https://github.com/user-attachments/assets/efa8e4cf-71b2-4212-a17e-edf33084ab0c" />  
<img width="281" height="49" alt="Capture2" src="https://github.com/user-attachments/assets/5fe12e59-411f-4a21-8545-f98c00c073ff" />    
В проекте создались:
* файл YAML-конфигурации, который будет отвечать за название, навигацию и тему сайта
* шаблон главной страницы
Чуть не забыла скачать mkdocs-material, исправила.
### Настройка конфигурации
#### Настройка mkdocs.yml
Прописала базовые параметры, тему и навигациу в блокноте, вставила в mkdocs.yml:  
<img width="655" height="325" alt="Capture" src="https://github.com/user-attachments/assets/e841a1e4-4bd3-4182-a8c7-ef8025801114" />  
Запустила, чтобы взглянуть, что получается:  
<img width="574" height="253" alt="Capture1" src="https://github.com/user-attachments/assets/6ac97866-0a3f-4597-a09c-1268363e4748" />  
В браузере вот так выглядит:  
<img width="925" height="445" alt="Capture2" src="https://github.com/user-attachments/assets/e5810079-3c7a-4fb8-b54f-b345cb0dcaba" />



