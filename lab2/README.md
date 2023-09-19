1. Сделал через git clone
2. more os-labs/labs-2023/lab2/labdata2.log
3. Пронумеровал через cat -n os-labs/labs-2023/lab2/labdata2.log > test.log каждую строку в тестовый файл и через /текст осуществил поиск по файлу
4. Делал так:
git add lab2/ - загружаем папку (lab2/) в git
git commit -m "Add lab2'" - добавляем коммит
git remote add OSlab https://github.com/AnotherJelly/OSLabsBespalov - создаём связь с репозиторием
git push OSlab main - загружаем в нужную ветку
5. Папки создавал через mkdir.
Вывод фильмов через ls 'Ryan Gosling'/ > '5 пункт'.txt.
Вывод информации с использованием разделителя (delimiter.txt): cat delimiter.txt 'Ryan Gosling'/'Blade Runner 2049'/info.txt delimiter.txt 'Ryan Gosling'/'Drive'/info.txt delimiter.txt 'Ryan Gosling'/'La La Land'/info.txt delimiter.txt 'Ryan Gosling'/'The Place Beyond the Pines'/info.txt >> '5 пункт'.txt
Также есть ручной ввод разделителя, но он мне показался неудобным: cat - 'Ryan Gosling'/'Blade Runner 2049'/info.txt - 'Ryan Gosling'/'Drive'/info.txt - 'Ryan Gosling'/'La La Land'/info.txt - 'Ryan Gosling'/'The Place Beyond the Pines'/info.txt >> '5 пункт'.txt

