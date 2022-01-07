Программа предназначена для предотвращения обновлений Viber на Windows. Полезно когда вайбер после своих обновлений больше не работает или когда вайбер после установки даже не загружается. Причина этому - старые драйвера для видеокарты. **Обновление на новые версии драйверов должно решить проблему в большинстве случаев.** Если же проблема остается, то можно воспользоваться этой программой. Тестировалось на Win7(x64) и Viber 6.0.1

**Требования:**
должна быть установлена [Java SE Runtime Environment 8](http://www.oracle.com/technetwork/java/javase/downloads/jre8-downloads-2133155.html) (JRE 8) или выше.

## Инструкция по установке

1) Если вайбер уже устанавливался, то нужно сначала деинсталировать Viber, а затем почистить все остатки по следующим путям:

    *с:\Users\%username%\AppData\Local\Viber*

    *с:\Users\%username%\AppData\Roaming\ViberPC*

2) Устанавливаем [Viber for Windows ver 6.0.1](https://download.cdn.viber.com/desktop/windowsxp/ViberSetup.exe)

3) После первого запуска Viber в меню "Инструменты > Параметры > Основное" отключаем "Запускать Viber при загрузке системы".

4) Распаковать [архив](https://github.com/asavchuk/ViberFix/raw/master/viberfix.zip) на диск "С" в папку *viberfix*, т.е. программа должна быть расположена в 

*с:\viberfix*

5) Поместить из архива файл "*run viberfix*" в автозагрузки. Т.о. вайбер будет (и должен) запускаться из автозагрузки. 

## Внимание

- если вайбер покажет, что обновление готово к установке (будет восклицательный знак в правом верхнем углу программы), - НЕ устанавливать его 

- если нужно запустить вайбер вручную, то запускайте только по ярлыку "*run viberfix*"
