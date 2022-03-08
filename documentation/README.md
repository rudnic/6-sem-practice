# Документация по шорткодам

### First Shortcode
В первом шорткоде, необходимо напрямую передавать переменные, потому что, хоть карточки и одинаковые, у некоторых разные классы. Пример вызова шорткода:

```
{{< first_snippet 

    title = "Title" 
    sub_title = "Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur."
    quote = "We will make America great again!!!"

    image_quote_src = "https://yt3.ggpht.com/a/AGF-l79u61pejE_uMAoLPHi4E2Qev8JSgmiVOaxYAA=s900-c-k-c0xffffffff-no-rj-mo"
    quote_author = "Billy Harrington"
    position = "Actor"

    first_card_title = "1"
    first_card_content = "first card content"

    second_card_title = "2"
    second_card_content = "second card content"

    third_card_title = "3"
    third_card_content = "third card content"

    fourth_card_title = "4"
    fourth_card_content = "fourth card component"
>}}
```


### Second Shortcode
Для второго шорткода было принято решение использовать .json файл, где будет хранится информация о генерируемых карточках.
![Screenshot](https://i.ibb.co/Qf63ZR7/image.png)

Файл с данными выглядит так:
![Screenshot](https://i.ibb.co/CmQjmSJ/image.png)
В img_link хранится ссылка на изображение
В person_name хранится имя, которое расположено под изображением
В person_position подразумевается, что хранится занимаемая должность
Выглядит карточка так:
![Screenshot](https://i.ibb.co/Nnvnwpx/image.png)

### Third Shortcode
В третьем шорткоде, как и во втором, используется .json файл с данными:
![Screensgot](https://i.ibb.co/2ZcvCWy/image.png)
Так выглядит html:
![Screenshot](https://i.ibb.co/SrwFHrf/image.png)
