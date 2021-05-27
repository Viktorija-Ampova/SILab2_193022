# SILab2_193022
Лабораториска вежба број 2
Викторија Ампова, 193022

Изглед на Control Flow Graph

![image](https://user-images.githubusercontent.com/81265230/119901351-16703380-bf46-11eb-9413-54473cb70862.png)

Цикломатскта комплексност на графот е 8. 
Го проверив со формулите E-N+2 и  P+1, каде што E е бројот на врски, N е бројот на јазли, а P е предикатни јазли.
Бројот на јазли е 20, а бројот на врски е 26, па од тоа следува 26-20+2=8.
Бројот на предикатни јазли е 7 и тоа јазлите со број 2.1, 3, 4, 7, 8, 10 и 13. Од формулата P+1 добиваме 7+1=8 

Multiple Condition

Има 4 барања кои треба да бидат опфатени и тоа 3, 8, 10, 13.

  if (hr < 0 || hr > 24)

![image](https://user-images.githubusercontent.com/81265230/119901413-2be55d80-bf46-11eb-9e0d-6b9cfcd83ed3.png)

  if (min < 0 || min > 59)

![image](https://user-images.githubusercontent.com/81265230/119901433-3273d500-bf46-11eb-9705-e5736e0174e3.png)

if (sec >= 0 && sec <= 59)

![image](https://user-images.githubusercontent.com/81265230/119901444-356ec580-bf46-11eb-8670-415cf411b316.png)

  if (hr == 24 && min == 0 && sec == 0)

![image](https://user-images.githubusercontent.com/81265230/119901451-3869b600-bf46-11eb-89b3-eea98d4f126e.png)
