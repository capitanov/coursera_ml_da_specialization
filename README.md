# Материалы специализации Машинное обучение и анализ данных

| **Title**     | Specialization ML & DA   |
| :-- | :-- |
| **Author**    | Alexander Kapitanov      |
| **Language**  | Python                   |
| **Release**   | 21 Oct 2019              |


## О репозитории

В этот репозиторий будет выложена полезная информация, предоставленная к специализации **Машинное обучение и анализ данных** от Яндекс и МФТИ. Также в репозиторий будут выложены сертификаты, подтверждающие прохождение курсов специализации. Решения заданий и тестов **не выкладываю** по понятным причинам. В специализации для обучения и решения задач материал представлен на языке Python (в связке с Jupyter Notebook, Numpy, Scipy, Pandas, Sci-kit Learn, Keras, Tensorflow и др).

### Сертификаты:

- [**Certificates**](https://github.com/capitanov/coursera_ml_da_specialization/tree/master/Certificates "Сертификаты") - каталог с моими сертификатами об успешном прохождении курсов специализации.

Репозиторий разбит на каталоги по курсам:

- [Математика и Python для анализа данных](https://github.com/capitanov/coursera_ml_da_specialization/tree/master/C1_Math_and_Python "Математика и Python для анализа данных")
- [Обучение на размеченных данных](https://github.com/capitanov/coursera_ml_da_specialization/tree/master/C2_Supervised_Learning "Обучение на размеченных данных")
- [Поиск структуры в данных](https://github.com/capitanov/coursera_ml_da_specialization/tree/master/C3_Unsupervised_Learning)
- Построение выводов по данным
- Прикладные задачи анализа данных
- Анализ данных: финальный проект


В каждом каталоге курса представлена следующая информация:
- **Lectures** - материалы лекций в формате pdf
- **Notebooks** - полезные ноутбуки **.ipynb** для самостоятельного изучения
- **Slides** - слайды к видео-урокам в формате pdf
- **Subtitles** - субтитры к видео-урокам
- ~~**Tasks** - решения задач специализации~~

___

## Специализация

[Машинное обучение и анализ данных](https://www.coursera.org/specializations/machine-learning-data-analysis "Машинное обучение и анализ данных")

Видео курсов разработаны на Python 2. Задания и ноутбуки к ним адаптированы к Python 3.

### Курс 1
[Математика и Python для анализа данных](https://www.coursera.org/learn/mathematics-and-python?specialization=machine-learning-data-analysis "Математика и Python для анализа данных")

Анализ данных и машинное обучение существенно опираются на результаты из математического анализа, линейной алгебры, методов оптимизации, теории вероятностей. Без фундаментальных знаний по этим наукам невозможно понимать, как устроены методы анализа данных. Задача этого курса — сформировать такой фундамент. Мы обойдёмся без сложных формул и доказательств и сделаем упор на интерпретации и понимании смысла математических понятий и объектов. 

Для успешного применения методов анализа данных нужно уметь программировать. Фактическим стандартом для этого в наши дни является язык Python. В данном курсе мы предлагаем познакомиться с его синтаксисом, а также научиться работать с его основными библиотеками, полезными для анализа данных, например, NumPy, SciPy, Matplotlib и Pandas.

### Курс 2
[Обучение на размеченных данных](https://www.coursera.org/learn/supervised-learning?specialization=machine-learning-data-analysis "Обучение на размеченных данных")

Обучение на размеченных данных или обучение с учителем – это наиболее распространенный класс задач машинного обучения. К нему относятся те задачи, где нужно научиться предсказывать некоторую величину для любого объекта, имея конечное число примеров. Это может быть предсказание уровня пробок на участке дороги, определение возраста пользователя по его действиям в интернете, предсказание цены, по которой будет куплена подержанная машина.

В этом курсе вы научитесь формулировать и, конечно, решать такие задачи. В центре нашего внимания будут успешно применяемые на практике алгоритмы классификации и регрессии: линейные модели, нейронные сети, решающие деревья и так далее. Особый акцент мы сделаем на такой мощной технике как построение композиций, которая позволяет существенно повысить качество отдельных алгоритмов и широко используется при решении прикладных задач. В частности, мы узнаем про случайные леса и про метод градиентного бустинга.

Построение предсказывающих алгоритмов — это лишь часть работы при решении задачи анализа данных. Мы разберемся и с другими этапами: оценивание обобщающей способности алгоритмов, подбор параметров модели, выбор и подсчет метрик качества.

### Курс 3
[Поиск структуры в данных](https://www.coursera.org/learn/unsupervised-learning?specialization=machine-learning-data-analysis "Поиск структуры в данных")

В машинном обучении встречаются задачи, где нужно изучить структуру данных, найти в них скрытые взаимосвязи и закономерности. Например, нам может понадобиться описать каждого клиента банка с помощью меньшего количества переменных — для этого можно использовать методы понижения размерности, основанные на матричных разложениях. Такие методы пытаются сформировать новые признаки на основе старых, сохранив как можно больше информации в данных. Другим примером может служить задача тематического моделирования, в которой для набора текстов нужно построить модель, объясняющую процесс формирования этих текстов из небольшого количества тем. Такие задачи назвают обучением без учителя. В отличие от обучения с учителем, в них не предполагают восстановление зависимости между объектами и целевой переменной. Из этого курса вы узнаете об алгоритмах кластеризации данных, с помощью которых, например, можно искать группы схожих клиентов мобильного оператора. Вы научитесь строить матричные разложения и решать задачу тематического моделирования, понижать размерность данных, искать аномалии и визуализировать многомерные данные. Видео курса разработаны на Python 2. Задания и ноутбуки к ним адаптированы к Python 3.


___

### Link:
  * https://habr.com/users/capitanov/

### Author:
  * Kapitanov Alexander

### First release:
  * 2019/10/21