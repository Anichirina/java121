# Отчёт о тестировании приложения "Money Transfer" #
**Краткое описание**
Создано приложение, которое повторяет действия пополнения счета крупной суммой. Наше приложение было запущено в Java, оно повторяло процесс сложения и вывода итога сложения.
**Описание тестов**
Проводилось функциональное тестирование, воспроизведением действия сложения и вывод итога в формате int в наших условиях. Были проверены граничные значения, уменьшив одно значение на один ноль, уменьшив оба цифра на ноль, изменить вид функции на long.  При уменьшении чисел ответ выходит положительный и при изменении вида функции выходит правильный ответ.
https://yadi.sk/i/15WEwUSGyoF3QQ

**Результаты**
успешных 3/не успешных тестов 1
Ссылки на баг-репорт #1  
Общие рекомендации
В приложении использован неправильный вид переменной, лучше int поменять на long