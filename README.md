### Опис ДЗ
Для виконання цього ДЗ вам необхідно переглянути урок по npm

- Створюємо репозиторій на github
- Через консоль клонируем его себе на ПК
- Через консоль створюємо файл index.js у корньому проекті
- В цьому файлі реалізовуються функції: суммування, вичитання та умноження
- Ініціалізуємо npm (npm init) і заповнюємо всі поля
- Встановлюємо в проект пакет lodash
- Створюємо файл .gitignore і додаємо в нього все, що не повинно бути на github, це точна папка node_modules та інші системні папки, які у вас є, наприклад .vscode , .idea
- Добавьте красивіше в проект
- Запустіть його через npx, подивіться, які файли були змінені
- Встановіть eslint в проекті
- Виконайте ініціалізацію з правилами airbnb
- Запустіть лінтер на файлах проекту, виправте зауваження
- Через командну строку заливаємо все, що накодили на github
### ↓↓↓ Опис виконання ↓↓↓
- клонування через консоль -->
git clone https://github.com/s-i-fedorov/hw_19_npm.git

- створення файлу через термінал ubuntu -->  
serhii@serhii-PC: /WebstormProjects/npm/hw_19_npm$ mkdir js  
serhii@serhii-PC: /WebstormProjects/npm/hw_19_npm$ cd js/  
serhii@serhii-PC: /WebstormProjects/npm/hw_19_npm/js$ touch index.js

- ініціалізація гіт у репозиторії -->  
serhii@serhii-PC:~/WebstormProjects/npm$ git init

- запуск prettier через npx -->  
serhii@serhii-PC:~/WebstormProjects/npm/hw_19_npm/js$ npx prettier --write index.js
index.js 60ms

- commit and push через термінал -->  
  serhii@serhii-PC:~/WebstormProjects/npm/hw_19_npm$ git commit -am "hw_19 completed"  
  [main 550076c] hw_19 completed
  1 file changed, 1 insertion(+)  
- serhii@serhii-PC:~/WebstormProjects/npm/hw_19_npm$ git push  
    Перечисление объектов: 14, готово.  
    Подсчет объектов: 100% (14/14), готово.  
    При сжатии изменений используется до 4 потоков  
    Сжатие объектов: 100% (10/10), готово.  
    Запись объектов: 100% (13/13), 1.35 КиБ | 1.35 МиБ/с, готово.  
    Всего 13 (изменений 2), повторно использовано 0 (изменений 0), повторно использовано пакетов 0  
    remote: Resolving deltas: 100% (2/2), done.  
    To github.com:s-i-fedorov/hw_19_npm.git
    fa848ec..550076c  main -> main
