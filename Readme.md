Часть 1

Ссылка на Google-Colab (1 часть): https://colab.research.google.com/drive/1Su05odi3OTGy1TjwniUUJcA0V7kIJ6hs?usp=sharing

Проверка качества чтений из fastQC: сравнительная статистика из multiQC

![image](https://user-images.githubusercontent.com/93254228/143721942-0d4f9c74-1222-421b-9281-5b2d83a14667.png)
![fastqc_sequence_counts_plot](https://user-images.githubusercontent.com/93254228/143722062-756f847a-e5a5-407f-b66b-d774901ea828.png)
![fastqc_per_base_sequence_quality_plot](https://user-images.githubusercontent.com/93254228/143722076-c031d1d4-e5bb-491e-8c8f-e975abbba039.png)
![fastqc_per_sequence_quality_scores_plot](https://user-images.githubusercontent.com/93254228/143722081-88ffb686-bea0-4da1-83d7-8544ac8c7b2c.png)
![fastqc_per_sequence_gc_content_plot](https://user-images.githubusercontent.com/93254228/143722086-566ebd81-6102-4a4d-8190-0e0d1d3e2442.png)
![fastqc_per_base_n_content_plot](https://user-images.githubusercontent.com/93254228/143722090-8bb57ff3-4d0a-469b-b356-38b3316c2f03.png)
![fastqc_sequence_duplication_levels_plot](https://user-images.githubusercontent.com/93254228/143722102-2c780be9-424b-49df-8cf7-fe4a653e1480.png)

Суммарная статистика:

![fastqc-status-check-heatmap](https://user-images.githubusercontent.com/93254228/143722105-4f45e57b-950a-46e6-ac0c-ff717dd99466.png)

Количество уникально картированных чтений по каждому образцу:

![image](https://user-images.githubusercontent.com/93254228/143722266-f8c31506-0511-455a-8523-8e19b3f3dd57.png)

Смотрим статистику HTSeq и узнаем, количество чтений соответствует участкам генома, где не аннотировано ни одного экзона, и количество чтений, которые могут принадлежать разным генам:

![image](https://user-images.githubusercontent.com/93254228/143722252-b12812b8-6cb7-4fac-9526-b53cabd807f2.png)

Считаем количество чтений, соответствующих хотя бы одному гену:

![image](https://user-images.githubusercontent.com/93254228/143722333-fdfb1388-680a-44df-9526-e0bd2e1395ee.png)

Таблица (сделанная в Excel) со статистикой по каждому образцу:

![image](https://user-images.githubusercontent.com/93254228/143722563-4a3171c3-ab48-496d-8810-ebfb956f3cb6.png)
