# Руководство по использованию приложения DJI Fly для трансляций в реальном режиме времени

Это руководство поможет вам разобраться: 

    - какие платформы потоковой трансляции поддерживает приложение DJI Fly, 
    - как вести потоковую трансляцию, 
    - какие продукты поддерживают потоковую трансляцию, 
    - какие дополнительные разрешения и скорости передачи видео можно использовать.

**Соответствующие продукты:** дроны с камерой

Потоковую трансляцию поддерживает приложение DJI Fly версии V1.4.12 и выше. Чтобы использовать эту возможность и делиться изображением с экрана, вам нужно включить потоковую трансляцию в **Настройках передачи изображения** / **Image Transmission Settings**.

> 1. For DJI Fly V1.16.0 and later, when using DJI RC 2/DJI RC Pro/DJI Smart Controller for 
livestreaming via DJI Fly, you need to plug in the microphone to start the livestreaming.
> 
> 2. Пульт дистанционного управления DJI RC не поддерживает трансляцию в реальном режиме времени.
> 
> 3. Прямая трансляция по протоколу RTMP поддерживается, если вы используете дроны DJI Mavic 4 Pro, DJI Flip, DJI Air 3S, DJI Air 3 или DJI Mini 4 Pro вместе с пультом DJI RC 2.
> 
> 4. When other aircraft are used with DJI RC-N3/DJI RC-N2/DJI RC-N1, they support RTMP livestreaming.

## Дополнительные разрешения и скорости передачи видео

**Дополнительное разрешение:** 1080P или 720P

> Из-за аппаратных ограничений пульт DJI RC 2 поддерживает трансляцию в реальном режиме времени только в формате 720P.

**Дополнительные скорости передачи видео:** 
    
    - устройства на iOS: 2 Мбит/сек или 1 Мбит/сек; 
    - устройства на Android: 5 Мбит/сек или 3 Мбит/сек.

**Поддерживаемые платформы:**

    RTMP

**RTMP Livestream Operation Guides**

**Перед началом работы:**

1. Загрузите и установите приложение DJI Fly.

2. Убедитесь, что приложение подключено к интернету через 4G/5G или Wi-Fi.

3. Подтвердите, что у аккаунта есть разрешение на прямую трансляцию на соответствующей платформе. Если этого разрешения нет, то получить коды для трансляции нельзя и провести ее по протоколу RTMP невозможно.

4. Убедитесь, что текущая платформа поддерживает протоколы RTMP. Изучите руководства по прямой трансляции или свяжитесь со службой поддержки клиентов платформы.

**После подготовки выполните следующие действия:**

1. Включите питание дрона и пульта управления, подклюaчите пульт к приложению DJI Fly. Если подключение выполнено успешно, то на экране появится сообщение **GO FLY**.

Примечание: При подключении пульта управления к приложению DJI Fly используйте USB-кабель для подключения к дрону. Это не нужно делать в том случае, если вы используете пульт дистанционного управления со встроенным экраном, например, DJI RC Pro и DJI Smart Controller.

组<1@2x.png>

2. Нажмите GO FLY > Transmission > Live Streaming Platforms > RTMP.

组<2@2x.png>

组<3@2x.png>

组<4@2x.png>

3. Введите адрес прямой трансляции и коды, полученные от платформы в поле **RTMP Address**. Чтобы получить дополнительную информацию об этом, изучите руководство по прямой трансляции или свяжитесь со службой поддержки клиентов платформы.

Ниже показан скриншот с платформы Bilibili для получения протокола RTMP:

Please note that “/” needs to be added between the livestreaming address and livestreaming codes as a transition. If the livestreaming address already ends with a “/”, it is not necessary to add another slash mark. For example, In the example, the livestreaming address is:rtmp://10.39.12.189:1935, and the livestreaming code is :livxxxme. The combination is: rtmp://10.39.12.189:1935/livxxxme.

组<5@2x.png>

4. After entering “RTMP Address”, “Livestream Resolution” and “Livestream Bitrate”, tap “Start”. A countdown “3/2/1” will appear. The livestream will start automatically once the countdown ends. After the livestreaming platform is connected successfully, a red icon will appear on the camera view.

组<6@2x.png>
