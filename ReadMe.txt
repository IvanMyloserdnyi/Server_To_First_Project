Бекенд частина



1 Реалізувати на стороні бекенду обробку запиту GET(/photos) який буде повертати массив з 25 обьектів ( структура така ж я у моковіх даних)



1.1 При ініалізації серверу( npm run start) маємо гененрувати вказані масив та записувати їх у файли photos.txt / відповідно



1.2 При GET запиті на /photos маємо читати видповідний файл та віддавати корістувачу всі данні у форматі json (JSON.stringify())





2 Реалізувати на стороні бекенду обробку запиту GET(/comments) який буде повертати массив з 100 обьектів ( структура така ж я у моковіх даних)



1.1 При ініалізації серверу( npm run start) маємо гененрувати масив та записувати у файл comments.txt відповідно



2.1 При GET запиті на /photos маємо читати видповідний файл та віддавати корістувачу всі данні у форматі json (JSON.stringify())



Фронтенд частина



Замінюємо вікористання момкових данних на данні, які ми отримуємо з серверу



Допрацюйте модуль для відтворення фотографій так, щоб як дані використовувалися не випадково згенеровані об'єкти, а ті дані, які ви завантажите з віддаленого сервера. (4 ТЗ)



Додайте обробку можливих помилок при завантаженні. (4.2 ТЗ)