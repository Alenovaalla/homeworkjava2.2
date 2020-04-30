# Отчёт о тестировании приложения "Precision"

## Краткое описание

Проводилось тестирование модуля приложения "Precision", позволяющего внедрять бонус новым клиентам. Для этого в  IntelliJ IDEA был написан и проверен код модуля.

## Описание тестов

Проведено модульное тестирование нового блока приложения. В IntelliJ IDEA был написан следующий код:

public class Main {
    public static void main(String[] args) {
        double regularBonus = 0.3;
        double specialBonus = 0.6;
        double totalBonus = regularBonus + specialBonus;
        System.out.println(totalBonus);
    }
}
## Результаты

1. 100% неуспешных тестов
2. https://github.com/Alenovaalla/homeworkjava2.2/issues/1

## Общие рекомендации

Необходимо провести дополнительное тестирование для выявления причины бага (в задании указано НЕ менять данные)