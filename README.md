# Отчёт о тестировании Precision

## Тестирование сложения regularBonus и specialBonus

<04/04/2021> - <04/04/2021> было проведено <unit тестирование> приложения <Precision>.

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* <[issues](https://github.com/dimawer37/-2.2/issues/1>)

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:

* тест план, задание №2

1. Создать базовое приложение и разместить в нём переданный вам код
2. Проверить его работоспособность

* кусок кода:

public class Main {
public static void main(String[] args) {
double regularBonus = 0.3;
double specialBonus = 0.6;
double totalBonus = regularBonus + specialBonus;
System.out.println(totalBonus);
}
}

В качестве тестовых данных использовались данные <предоставленные приложением Precision>:

* <regularBonus = 0,3>
* <specialBonus = 0,6>

OP - 0,9

Тестирование производилось в следующем окружении:
* <Win 10, 64 разрядная>
* <версия Java 11>
* <Среда разработки Intellij IDEA>