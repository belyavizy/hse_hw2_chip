# hse_hw2_chip

Ссылка на мой [google colab](https://colab.research.google.com/drive/1-AMyNXg4k3qpsMsx9rYbn9EvEKimgpdh?usp=sharing)
 
 ### Вводные данные для исследования
 > Клеточная линия: H7
 > 
 > Гистоновая метка: H3K27me3
 
 ### Анализ FastQC
 Все html-файлы, полученные в ходе выполнения исследования из домашнего задания, находятся в папке reports.
 
 ### Реплика №1 - ENCFF792HPJ
![image](https://user-images.githubusercontent.com/95979982/222257909-54df9a85-03f9-4939-9508-31248bb9694f.png)
![image](https://user-images.githubusercontent.com/95979982/222257959-eccdf77f-3ad7-45d0-b70c-17a6032c400d.png)
![image](https://user-images.githubusercontent.com/95979982/222258009-deeab3e3-29ab-4dd9-ac1e-6da6fa0470ae.png)
![image](https://user-images.githubusercontent.com/95979982/222258044-8ea16db5-f065-4c82-b5f0-fca7141c8836.png)
![image](https://user-images.githubusercontent.com/95979982/222258107-350d5b15-4f06-40e7-b2ef-2f7bf374ce7a.png)
![image](https://user-images.githubusercontent.com/95979982/222258088-604d7da5-23eb-4be0-a5e0-ceab49ec8976.png)
 ### Реплика №2 - ENCFF920HHA
![image](https://user-images.githubusercontent.com/95979982/222258197-f5ad7488-84c4-49a2-ba13-b1bedfe26c95.png)
![image](https://user-images.githubusercontent.com/95979982/222258232-02857136-74c4-47d2-998e-52a1df44e741.png)
![image](https://user-images.githubusercontent.com/95979982/222258276-13d8ebae-991e-413c-b69b-6994e79434c0.png)
![image](https://user-images.githubusercontent.com/95979982/222258311-41073839-1b45-4e35-bb7b-719d187f44a9.png)
![image](https://user-images.githubusercontent.com/95979982/222258339-36fbbf5b-b20a-46ea-95dc-71eaf740e714.png)
> Вывод: качество приемлимое для дальнейшей работы

 ### Контроль - ENCFF486LTO
 ![image](https://user-images.githubusercontent.com/95979982/222259650-296e21ad-2747-417b-95b3-94d47dc54581.png)
![image](https://user-images.githubusercontent.com/95979982/222259701-f775a049-995d-4e0c-aa90-4e5569644f66.png)
![image](https://user-images.githubusercontent.com/95979982/222259721-7bc49ba8-8db2-4428-8d3e-8a276939e6cc.png)
![image](https://user-images.githubusercontent.com/95979982/222259772-81d0d0fe-2b64-495c-b8ec-7860ec9aae5b.png)
![image](https://user-images.githubusercontent.com/95979982/222259817-e6c33ce7-1ce4-4e91-9a88-f1bd622e69ab.png)
![image](https://user-images.githubusercontent.com/95979982/222259853-b0398444-0a2d-4d38-b837-1e872fbfd9d1.png)
> Вывод: качество прочтений хорошее, всё находится в зеленой зоне.

Подрезание чтений не проводилось

### Полученная статистика по выравниванию на 18-ю хромосому

![image](https://user-images.githubusercontent.com/95979982/222260215-f29a1a8b-3ffe-4e08-9ff0-62f27719618b.png)


Процент выравниваний получился таким из-за того, что была взята одна хромосома незначительного размера.
 
 ### Диаграммы Эйлера-Венна
![image](https://user-images.githubusercontent.com/95979982/222260300-cebf0a52-3902-45a6-bf82-68c51b51f5a2.png)
![image](https://user-images.githubusercontent.com/95979982/222260338-37d1d2f2-3003-48b3-a347-a3a4cc1c80ff.png)
![image](https://user-images.githubusercontent.com/95979982/222260378-f5fa291a-c479-4bc2-8b0c-97ec2d8eb6ce.png)
![image](https://user-images.githubusercontent.com/95979982/222260459-7d4cba6f-91ae-4508-9fae-33e3b2601469.png)


> Вывод: пересечений мало (возможно, из-за того, что выравнивание было произведено на одну хромосому). Сами диаграммы показывают нам количество пересечений среди выявленных нами пиков и пиков из ENCODE (и наоборот). Значение пересечений в первом случае совпадает, а во втором минимально отличается (т.к. позиции пиков неуникальны, то значения могут не совпасть).
