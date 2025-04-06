# Криптоанализатор. Итоговый проект по курсу fastAPI
Татарских Сергей, 21-ИСбо-4

## Стек
- FastAPI + pydantic, pydantic-settings, aiohttp
- React + axios, ant design, tailwind


### Как развернуть?
#### Backend
- `python3 -m venv venv`
- `.\venv\Scripts\activate.bat`
- `pip install -r requirements.txt`
- `uvicorn src.main:app --reload`

#### Frontend
- Переходим в папку frontend
- `npm install`
- `npm run dev`

### Как пользоваться?
- В корне проекта создаем файл .env
- Регистрируемся на сайте https://coinmarketcap.com
- Выбираем бесплатный тариф и копируем в файл .env api-ключ. (Должно получиться CMC_API_KEY=ваш_ключ)
- После установки и запуска всех компонентов переходим по адресу  http://localhost:5173
- Пользуемся