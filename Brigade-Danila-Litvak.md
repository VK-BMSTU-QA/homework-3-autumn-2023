# Домашнее задание №3 по курсу "Обеспечение качества"

# Проект ["VK Реклама"](https://ads.vk.com)

## Авторизационные данные

Почта: tp_autumn_selenium@mail.ru

Пароль: _

## Создание кампании - https://ads.vk.com/hq/new_create/ad_plan (с авторизацией)

### Позитивные кейсы

![campaign_creating_page](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/campaign_creating_page.jpg)
- Кампании. Создание кампании. При успешном создании кампании через "Сайт" она появляется в списке на странице https://ads.vk.com/hq/dashboard/ad_plans
- Кампании. Создание кампании. При успешном создании кампании через "Сообщество и профиль" она появляется в списке на странице https://ads.vk.com/hq/dashboard/ad_plans
- Кампании. Создание кампании. При успешном создании кампании через "Одноклассники" она появляется в списке на странице https://ads.vk.com/hq/dashboard/ad_plans
- Кампании. Создание кампании. При успешном создании кампании через "Каталог товаров" она появляется в списке на странице https://ads.vk.com/hq/dashboard/ad_plans
- Кампании. Создание кампании. При успешном создании кампании через "VK Mini Apps & VK Games" она появляется в списке на странице https://ads.vk.com/hq/dashboard/ad_plans
- Кампании. Удалении кампании. При наличии кампании в списке и её удалении, кампания исчезает из списка
![campaigns_list](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/campaigns_list.jpg)
- Кампании. Удалении черновика. При наличии черновика в списке и его удалении, черновик исчезает из списка
![drafts_list](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/drafts_list.jpg)

### Негативные кейсы

- Кампании. Создание кампании. Настройка кампании. Целевые действия. Сайт. При нажатии на кнопку "Продолжить" с пустым полем "Рекламируемый сайт" появляется уведомление "Обязательное поле".

  ![required_url_site](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/required_url_site.jpg)
- Кампании. Создание кампании. Настройка кампании. Целевые действия. Сайт. При нажатии на кнопку "Продолжить" с невалидной ссылкой(неимеющую структуру url-адреса) "Рекламируемый сайт" появляется уведомление "Неверный формат URL".

  ![incorrect_url_site](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/incorrect_url_site.jpg)
- Кампании. Создание кампании. Настройка кампании. Целевые действия. Сайт. Бюджет кампании. Минимальная цена. При вводе числа < 100 в поле "Бюджет" появляется сообщение "Бюджет кампании должен быть не меньше 100₽"

  ![incorrect_budget](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/incorrect_budget.jpg)
- Кампании. Создание кампании. Группы объявлений. Сайт. Нажатие на "Продолжить" у "Регионы показа" появляется уведомление "Не выбраны регионы показа"

  ![incorrect_region](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/incorrect_region.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при незаполненном поле "Заголовок" под этим полем появляется сообщение "Обязательное поле"

  ![empty_title_site](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_title_site.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при длинном поле "Заголовок"(40 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_title_site](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_title_site.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при незаполненном поле "Короткое описание" под этим полем появляется сообщение "Обязательное поле"

  ![empty_short_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_short_description.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при длинном поле "Короткое описание"(90 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_short_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_short_description.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при длинном поле "Длинное описание"(2000 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_long_description_site](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_long_description_site.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при длинном поле "Текст рядом с кнопкой"(30 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_button_text](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_button_text.jpg)
- Кампании. Создание кампании. Объявления. Сайт. При нажатии на кнопку "Опубликовать" при длинном поле "Данные рекламодателя"(115 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_advertiser](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_advertiser.jpg)
- Кампании. Создание кампании. Настройка кампании. Целевые действия. Каталог. При нажатии на кнопку "Продолжить" с пустым полем "Рекламируемый сайт" появляется уведомление "Обязательное поле".

  ![empty_url_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_url_catalog.jpg)
- Кампании. Создание кампании. Настройка кампании. Целевые действия. Каталог. При нажатии на кнопку "Продолжить" с невалидной ссылкой(неимеющую структуру url-адреса) "Рекламируемый сайт" появляется уведомление "Неверный формат URL".

  ![incorrect_url_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/incorrect_url_catalog.jpg)
- Кампании. Создание кампании. Настройка кампании. Целевые действия. Каталог. При нажатии на кнопку "Продолжить" с пустым полем "Каталог товаров" появляется уведомление "Обязательное поле".

  ![empty_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_catalog.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при незаполненном поле "Заголовок" под этим полем появляется сообщение "Обязательное поле"

  ![empty_title_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_title_catalog.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при длинном поле "Заголовок"(25 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_title_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_title_catalog.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при незаполненном поле "Описание для карусели" под этим полем появляется сообщение "Обязательное поле"

  ![empty_carousel_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_carousel_description.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при длинном поле "Описание для карусели"(50 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_carousel_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_carousel_description.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при незаполненном поле "Описание для баннера" под этим полем появляется сообщение "Обязательное поле"

  ![empty_banner_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/empty_banner_description.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при длинном поле "Описание для баннера"(125 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_banner_description](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_banner_description.jpg)
- Кампании. Создание кампании. Объявления. Каталог. При нажатии на кнопку "Опубликовать" при длинном поле "Длинное описание"(220 символов) под этим полем появляется сообщение "Превышена максимальная длина поля"

  ![long_long_description_catalog](https://github.com/marcussss1/homework-3-autumn-2023/blob/main/images/long_long_description_catalog.jpg)
