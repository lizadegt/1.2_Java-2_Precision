# Отчёт о тестировании 1.2 Задача №2 - Precision

## Краткое описание

16.07.2021 было проведено функциональное тестирование программы дополнительного бонуса для новых клиентов.

На тестирование затрачено: 1 час

В результате тестирования выявлены следующие дефекты:
* []()

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:
* [Программа дополнительного бонуса для новых клиентов](https://github.com/netology-code/javaqa-homeworks/tree/master/programming)
 ``` java
public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
``` 
### В качестве тестовых данных использовались данные [тестового случая](https://github.com/netology-code/javaqa-homeworks/tree/master/programming):
 ``` java
        double regularBonus = 0.3;
        double specialBonus = 0.6;
``` 


### Тестирование производилось в следующем окружении:
* Windows 10 x64
* Версия Java - version "11.0.11" 2021-04-20