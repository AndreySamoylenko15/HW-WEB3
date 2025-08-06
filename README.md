🧮 Multiprocessing Factorization Benchmark
Цей проєкт демонструє використання багатопроцесорності у Python для розкладання чисел на множники та вимірювання продуктивності різних підходів:

Синхронна обробка

multiprocessing.Pool

concurrent.futures.ProcessPoolExecutor
📦 Вміст
factorize(numbers: list) – функція, що повертає список списків дільників для кожного числа у вхідному списку.

multifacrorize(number: int) – функція для пошуку дільників одного числа.

multiprocessing – використовується для паралельної обробки.

logging – логування результатів у консоль.

assert – перевірка правильності результатів.

▶️ Запуск
1. Клонуй або завантаж репозиторій:git clone https://github.com/your-username/factorization-multiprocessing.git
cd factorization-multiprocessing
2. Запусти скрипт:python factorize.py
⚙️ Вимоги
Python 3.8+

Бібліотеки: стандартні (time, multiprocessing, concurrent.futures, logging)
🔍 Як це працює
Синхронно: усі числа обробляються по черзі.

Pool.map: розподіляє обчислення між усіма ядрами процесора.

ProcessPoolExecutor.map: альтернативний, сучасний API для паралельної обробки.

🚀 Продуктивність
Завдяки використанню багатопроцесорності, час обробки значно зменшується, особливо для великих чисел.

