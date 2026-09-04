#  Стажировка по Data Science в компании strikt

[Задача 1](https://github.com/pomellonn/strikt/tree/main/Article%20coverage): Coverage тезисов относительно статьи

Оценить, насколько выбранный поднабор тезисов покрывает содержание статьи. 
Реализовано два метода оценки:  
1. ROUGE + Jaccard + Character n-grams -  интерпретируемый lexical baseline: сравнение лемм, n-грамм и последовательностей между частями статьи и выбранными тезисами
2. Entities + RuWordNet	- извлечение сущностей, чисел, дат, ключевых понятий и отрицания; расширение понятия синонимами через RuWordNet и  расчет conceptual/factual coverage с штрафами за противоречия по числам, сущностям и отрицанию.


[Задача 2](https://github.com/pomellonn/strikt/tree/main/Contrastive%20learning):
Contrastive learning для переобучения эмбеддера для генерации кандидатов перед дедубликацией
