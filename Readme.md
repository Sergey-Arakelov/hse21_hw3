Часть 1

Ссылка на Google-Colab (1 часть): https://colab.research.google.com/drive/1B8_4ntL7yWqhKpF5SE0j5uN7AkNpY4AQ?usp=sharing 

Проверка качества чтений из FastQC: сравнительная статистика из MultiQC

![image](https://user-images.githubusercontent.com/93254228/143735315-81953ada-b85f-44c6-8b3a-b73e44f18ca0.png)

![fastqc_sequence_counts_plot](https://user-images.githubusercontent.com/93254228/143735336-d03a21fe-dc4b-4a1b-b55b-7c265e14cb42.png)

![fastqc_per_base_sequence_quality_plot](https://user-images.githubusercontent.com/93254228/143735353-e8a498ec-d81f-4613-9430-86da4dff5d2a.png)

![fastqc_per_sequence_quality_scores_plot](https://user-images.githubusercontent.com/93254228/143735374-ea6c93c2-953d-4406-84ff-3185dabe697d.png)

![fastqc_per_sequence_gc_content_plot](https://user-images.githubusercontent.com/93254228/143735386-a091a948-d915-4b96-9fbf-02179f931d80.png)

![fastqc_per_base_n_content_plot](https://user-images.githubusercontent.com/93254228/143735399-4cc74556-51b1-4eb1-b78e-21930bb5ece6.png)

![fastqc_sequence_duplication_levels_plot](https://user-images.githubusercontent.com/93254228/143735417-f8a9679f-5ceb-48ba-a2bf-aa5cf31cd6de.png)


Суммарная статистика:

![fastqc-status-check-heatmap](https://user-images.githubusercontent.com/93254228/143735445-4281022e-e9e8-4086-a3d5-fc435d0d50b8.png)

Количество уникально-картированных чтений по каждому образцу

![image](https://user-images.githubusercontent.com/93254228/143763500-a3b21a81-1052-46e7-b4a9-88d68e6abf80.png)

По статистике HTSeq узнаём, какое количество чтений соответствует участкам генома, где не аннотировано ни одного экзона, и количество чтений, которые могут принадлежать разным генам

![image](https://user-images.githubusercontent.com/93254228/143766757-84574012-a12a-4b2e-93ae-14af7d28eef2.png)

Количество чтений, соответствующих хотя бы одному гену:

![image](https://user-images.githubusercontent.com/93254228/143766822-3802748a-799b-4add-b4dc-1588e35432dc.png)

Таблица со статистикой по каждому образцу

![image](https://user-images.githubusercontent.com/93254228/143764707-f1be9a2d-22d0-47dc-a24a-42a5faca5c67.png)

Таблица (файлл all_counts)

![image](https://user-images.githubusercontent.com/93254228/143766890-960d608f-5d10-4151-9bb7-a6de4e58826c.png)

Часть 2. Анализ с помощью DESeq2
