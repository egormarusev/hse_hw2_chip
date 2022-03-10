# hse_hw2_chip

Ссылка на мой [google colab](https://colab.research.google.com/drive/1M6Kuz5MR5jVZQmARgHb-gNaJ72Hc71Fv?usp=sharing)

## Вводные данные для исследования

Клеточная линия: GM23248

Гистоновая метка: H3K79me2

## Анализ FastQC

Все html-файлы в папке reports.

### Реплика №1 - ENCFF772USM

![image](https://user-images.githubusercontent.com/75699392/157736430-26f874ec-7daf-4c3f-a8de-514b4535e08e.png)

![image](https://user-images.githubusercontent.com/75699392/157736925-715a7a8e-cd72-4405-b218-e53cacece9a4.png)

> Качество прочтений очень хорошее, все в зеленой зоне.

![image](https://user-images.githubusercontent.com/75699392/157736961-73e2b7d6-60fe-42d9-88a3-f0495a775792.png)

![image](https://user-images.githubusercontent.com/75699392/157737027-02174184-b284-4c93-af87-b18eee248dee.png)

![image](https://user-images.githubusercontent.com/75699392/157737065-7fde7031-c6c5-4292-8963-94922c8bd6ef.png)

![image](https://user-images.githubusercontent.com/75699392/157737237-9b5049fe-15f3-4b6e-87ab-22b9756ff17b.png)

> Лишних адаптеров нет

### Реплика №2 - ENCFF247ZUN

![image](https://user-images.githubusercontent.com/75699392/157737849-a1b41478-8a26-42b8-8b57-759ea701df77.png)

![image](https://user-images.githubusercontent.com/75699392/157737887-07c3d372-bdba-47a9-a673-0e28534f8597.png)

> Качество прочтений очень хорошее, все в зеленой зоне.

![image](https://user-images.githubusercontent.com/75699392/157737913-bfd11f11-890a-4e73-8bc7-9a4ffa76740d.png)

![image](https://user-images.githubusercontent.com/75699392/157738962-9b7d0b17-492a-4889-972c-0155c26c9f12.png)

![image](https://user-images.githubusercontent.com/75699392/157738996-8818668b-9281-4c2b-9913-00fdbd55c881.png)

![image](https://user-images.githubusercontent.com/75699392/157739025-604c6b4b-ce6c-4619-84d3-4f3daeec8471.png)

> Лишних адаптеров нет


### Контроль - ENCFF203UWC

![image](https://user-images.githubusercontent.com/75699392/157743759-c0c8bdf3-9e88-4832-b89d-fa2a68f78792.png)

![image](https://user-images.githubusercontent.com/75699392/157743798-8da04b1e-701b-471f-a596-89ea8f397922.png)

> Качество прочтений очень хорошее, все в зеленой зоне.

![image](https://user-images.githubusercontent.com/75699392/157743823-e2bd9f2e-192a-48ab-b0bf-7c26283ffa32.png)

> В некоторых участках наблюдаются отклонения

![image](https://user-images.githubusercontent.com/75699392/157743851-15da1b95-2b83-4544-b915-21aea34f46d2.png)

![image](https://user-images.githubusercontent.com/75699392/157743871-30875ac9-47d3-4ecd-8be4-17cf10053b2a.png)

![image](https://user-images.githubusercontent.com/75699392/157743907-27158777-5fb5-43fb-9bc4-fec983861056.png)

> Лишних адаптеров нет

### Контроль - ENCFF203UWC с подоезанием чтений

![image](https://user-images.githubusercontent.com/75699392/157744121-a984be6c-e51d-485b-b467-b0785cb785de.png)

![image](https://user-images.githubusercontent.com/75699392/157744174-3ad32e83-90e0-44e8-b8b9-bac6f3b4630b.png)

> Качество прочтений очень хорошее, все в зеленой зоне.

![image](https://user-images.githubusercontent.com/75699392/157744192-2a061d18-d214-4bd7-b8d8-f9112450754d.png)

![image](https://user-images.githubusercontent.com/75699392/157744215-609cbfd0-8629-4792-a0ad-0edc43eb22d5.png)

![image](https://user-images.githubusercontent.com/75699392/157744239-40e1d7c9-1ddf-440c-91bc-11f67599074d.png)

![image](https://user-images.githubusercontent.com/75699392/157744271-669ae80c-3d05-4782-9b11-c960b731bfd6.png)

> Лишних адаптеров нет



## Полученная статистика по выравниванию на 14-ю хромосому

Процент выравниваний получился таким из-за того, что была взята одна хромосома незначительного размера.

| ID            | Всего ридов  | Уникально выровнилось | Неуникально выравнилось | Не выравнилось    |
| ------------- |:------------:| ---------------------:|------------------------:| --------------:   |
| ENCFF772USM   |   30706597   |   1306737 (4.26%)     |     2908153 (9.47%)     | 26491707 (86.27%) |
| ENCFF247ZUN   |   40707391   |   1745001 (4.29%)     |     3883564 (9.54%)     | 35078826 (86.17%) |
| ENCFF203UWC   |   21232897   |    916540 (4.32%)     |     1867193 (8.79%)     | 18449164 (86.89%) |

> Почему процент выравниваний получился именно таким?

Потому что мы использовали только одну хромосому.

## Диаграммы Эйлера-Венна

![image](https://user-images.githubusercontent.com/75699392/157740576-c6031f60-8d9a-41e4-9562-6d666448f648.png)

![image](https://user-images.githubusercontent.com/75699392/157740630-27777967-969a-4bf3-a5d1-17c23db29047.png)

![image](https://user-images.githubusercontent.com/75699392/157740658-cfec2c79-4367-4c15-81d6-a3a6296356a7.png)

![image](https://user-images.githubusercontent.com/75699392/157740761-8e79476f-ed21-4ffc-9ba6-5e138f0f642f.png)

> Перечесений мало, потому выравнивание было произведено только на одну хромосому.

> Диаграмма Венна показывает нам количество пересечений среди выявленных нами пиков и пиков из ENCODE и наоборот. Значения получились разными из-за того, что позиции пиков могут быть неуникальны.


