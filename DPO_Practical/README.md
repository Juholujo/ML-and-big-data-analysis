﻿# DPO_Practical
# Дпоплнительные задания

# Для первого сема:
Сделать графики для датасета из дз (вместо дефолта будет другой таргет)

[DPO_Practical/graph.jpg]

# Для второго сема:
 При помощи регулярок вывести все подстрочки из столбца речь в датасете из проекта, удовлетворяющие следующему паттерну: with [a ]<слово> <job | income> [and [a ]<слово> <job | income>], где [x] означает, что x опционально, <job | income> - либо присутствует job, либо income (этот синтакс не связан с синтаксом регулярок)
 Примеры:
 with a solid income
 with a solid job
 with a solid job and medium income
 with solid job and medium income
 with medium income and solid job
