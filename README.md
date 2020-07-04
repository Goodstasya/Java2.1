Задание.

Авиаперевозчики предлагают различные бонусные программы, начисляющие бесплатные мили за перелёты.

За каждые 20 рублей, потраченные на билет, начисляется 1 миля.

Стоимость билета назначим переменную _int_ cost = 3600
 
А переменную _int_ bonus - 20

Для расчета бонусных миль пишем java-код.

```public class Main {
     public static void main(String[] args) {
 
         int cost = 3600;
         int bonus = 20;
 
         int total = cost / bonus;
         System.out.println(total);
     }
 }`