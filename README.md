### 📌 **Шахедо-ракетна аналітика**  

Цей проєкт виконує збір, обробку та аналіз даних про атаки БПЛА та ракет на території України, використовуючи відкриті джерела, зокрема Вікіпедію.  

---

## ⚙️ **Функціонал**  
- **Парсинг даних** із сторінок Вікіпедії, що містять списки атак.  
- **Об’єднання таблиць** у єдиний набір даних, стандартизація дат та форматування.  
- **Попередня обробка** (видалення дубльованих записів, додавання відсутніх даних).  
- **Аналіз трендів** атак за періоди часу.  
- **Візуалізація** отриманих результатів.  

---

## 🛠 **Використані технології**  
- **Python**  
- **Pandas** – для роботи з таблицями.  
- **BeautifulSoup** – для парсингу HTML-даних.  
- **Matplotlib / Plotly** – для графічного аналізу.  
- **Statsmodels** – для аналізу часових рядів (ARIMA, Holt-Winters).  
- **Requests** – для роботи з HTTP-запитами.  

---

## 🚀 **Як запустити**  
1. **Встановлення залежностей:**  
```sh
pip install pandas beautifulsoup4 requests statsmodels matplotlib plotly
```
2. **Запуск Jupyter Notebook:**  
```sh
jupyter notebook
```
3. **Відкрити та виконати комірки в `Шахедо-ракетна аналітика.ipynb`.**  

---

## 📊 **Візуалізація та Аналіз**  
- Побудова графіків атак за місяцями та роками.  
- Оцінка динаміки влучань та перехоплень.  
- Прогнозування можливих атак на основі часових рядів.  

---
