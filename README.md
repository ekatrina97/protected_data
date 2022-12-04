# Защита персональных данных
###  **Учебный проект**

Страховой компании необходимо рассчитать количество страховых выплат клиентам на ближайшие 5 лет на основании исторических данных за прошедшие 5 лет. Но есть условие — при выполнении задачи нельзя использовать данные клиентов в исходном виде, т.к.
в них содержится персональная информация.

**Задача исследования** — построить модель машинного обучения, которая предсказывает количество страховых выплат
на основании преобразованных исходных данных. Качество модели на преобразованных исходных данных 
не должно отличаться от такой же модели, но обученной на сырых данных (без преобразований).

### **Результаты исследования**
Рассмотрено и проверено 2 алгоритма преобразования признаков:
- домножение признаков на обратимую матрицу
- стандартизация признаков по типу алгоритма из библиотеки **sklearn** StandardScaler()

Оба алгоритма прошли проверку. В качестве модели машинного обучения была использована линейная регрессия LinearRegression()


**P.S.** При анализе данных была использована библиотека **sweetviz**, отображение работы данной библиотеки на GitHub.com может быть некорректным.
При клонировании репозитория и просмотре на локальном компьютере проблем не возникнет.
