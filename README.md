# flash_cards_example
Утилита-пример программы по генерации flash-карт
## Инструкция:
1. Скачайте репозиторий
2. Откройте папку репозитория и в ней терминал
3. В терминале выполните команду
   ```cmd
   ./flash_cards.exe --input ./params.json --output ./output.json
   START
   Data written to ./output.json
   ```
   Где params.json - файл с параметрами генерации а output.json - путь до файла куда нужно записать сгенерированные карты

   ### Пример params.json:
   ```json
   [
	    {
	        "NativeLang":"RU",
		    "LearningLang":"EN",
		    "Words": 1,
		    "Topic": "Food & Cuisine",
		    "CEFRLevel":"A1"
	    },
	    {
	        "NativeLang":"RU",
		    "LearningLang":"EN",
		    "Words": 5,
		    "Topic": "Travel & Sightseeing",
		    "CEFRLevel":"B1"
	    }
	]
   ```
 ### Пример output.json:
   ```json
   [
	{
		"Topic": "Food \u0026 Cuisine",
		"Level": "A1",
		"Word": "apple",
		"Pronunciation": "ˈæpəl",
		"Definition": "плод яблони, обычно употребляемый в пищу",
		"Translation": "яблоко",
		"Example": "I ate an apple for breakfast.",
		"ExampleTranslation": "Я съел яблоко на завтрак."
	},
	{
		"Topic": "Travel \u0026 Sightseeing",
		"Level": "B1",
		"Word": "Airport",
		"Pronunciation": "/ˈeə.pɔːt/",
		"Definition": "приложение",
		"Translation": "Аэропорт",
		"Example": "I will meet you at the airport.",
		"ExampleTranslation": "Я встречу тебя в аэропорту."
	},
	{
		"Topic": "Travel \u0026 Sightseeing",
		"Level": "B1",
		"Word": "Hotel",
		"Pronunciation": "/hoʊˈtel/",
		"Definition": "отель",
		"Translation": "Гостиница",
		"Example": "We booked a hotel near the beach.",
		"ExampleTranslation": "Мы забронировали отель рядом с пляжем."
	},
	{
		"Topic": "Travel \u0026 Sightseeing",
		"Level": "B1",
		"Word": "Tourist",
		"Pronunciation": "ˈtʊr.ɪst/",
		"Definition": "турист",
		"Translation": "Турист",
		"Example": "The city attracts thousands of tourists every year.",
		"ExampleTranslation": "Город привлекает тысячи туристов каждый год."
	},
	{
		"Topic": "Travel \u0026 Sightseeing",
		"Level": "B1",
		"Word": "Museum",
		"Pronunciation": "/mjuːˈziː.əm/",
		"Definition": "музей",
		"Translation": "Музей",
		"Example": "Have you been to the museum yet?",
		"ExampleTranslation": "Ты уже был в музее?"
	},
	{
		"Topic": "Travel \u0026 Sightseeing",
		"Level": "B1",
		"Word": "Ticket",
		"Pronunciation": "/ˈtɪk.ɪt/",
		"Definition": "билет",
		"Translation": "Билет",
		"Example": "Don't forget to buy a ticket for the concert.",
		"ExampleTranslation": "Не забудь купить билет на концерт."
	}
   ]
   ```
