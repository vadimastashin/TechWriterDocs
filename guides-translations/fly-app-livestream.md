# Руководство по использованию приложения DJI Fly для трансляций в реальном режиме времени

Это руководство поможет вам разобраться: 

    - какие платформы потоковой трансляции поддерживает приложение DJI Fly, 
    - как вести потоковую трансляцию, 
    - какие продукты поддерживают потоковую трансляцию, 
    - какие дополнительные разрешения и скорости передачи видео можно использовать.

**Соответствующие продукты:** дроны с камерой

Потоковую трансляцию поддерживает приложение DJI Fly версии V1.4.12 и выше. Чтобы использовать эту возможность и делиться изображением с экрана, вам нужно включить потоковую трансляцию в **Настройках передачи изображения** / **Image Transmission Settings**.

1. For DJI Fly V1.16.0 and later, when using DJI RC 2/DJI RC Pro/DJI Smart Controller for 
livestreaming via DJI Fly, you need to plug in the microphone to start the livestreaming.

2. Пульт дистанционного управления DJI RC не поддерживает трансляцию в реальном режиме времени.

3. Only RTMP livestreaming is supported when using the DJI Mavic 4 Pro, DJI Flip, DJI Air 3S, DJI Air 3, or DJI Mini 4 Pro with the DJI RC 2.

4. When other aircraft are used with DJI RC-N3/DJI RC-N2/DJI RC-N1, they support RTMP livestreaming.

## Дополнительные разрешения и скорости передачи видео

Дополнительное разрешение: 1080P или 720P

Из-за аппаратных ограничений пульт DJI RC 2 поддерживает трансляцию в реальном режиме времени только в формате 720P.

Дополнительные скорости передачи видео: 
    
    - устройства на iOS: 2 Мбит/сек или 1 Мбит/сек; 
    - устройства на Android: 5 Мбит/сек или 3 Мбит/сек.

**Поддерживаемые платформы:**

    RTMP

**RTMP Livestream Operation Guides**

Before starting

1. Загрузите и установите приложение DJI Fly.

2. Make sure that the App has been connected to Internet, such as 4G/5G signals or Wi-Fi.

3. Confirm that the account has livestream permission for the corresponding platform. If not, the live-streaming codes cannot be obtained, and the RTMP live stream will be unable to work.

4. Make sure that the current platform supports RTMP protocols. Please check the livestream guidelines or contact the customer service of the corresponding platform.

After preparation, please follow the steps below:

1. Power the aircraft and remote controller on, and connect the remote controller to the DJI Fly app. After the connection is successful, “GO FLY” will be displayed on the page.

Note: When connecting the remote controller to the DJI Fly app, it is necessary to use a USB cable to connect to the aircraft. This step can be omitted for remote controllers with a built-in screen (such as DJI RC Pro and DJI Smart Controller).

组<1@2x.png>

2. Tap GO FLY > Transmission > Live Streaming Platforms > RTMP.

组<2@2x.png>

组<3@2x.png>

组<4@2x.png>

3. Enter the livestreaming address and codes obtained from the livestreaming platform in “RTMP Address”. For detailed operation steps, refer to the livestream guide or contact the corresponding platform’s customer service.

Below is the reference screenshot from the Bilibili platform for obtaining RTMP:

Please note that “/” needs to be added between the livestreaming address and livestreaming codes as a transition. If the livestreaming address already ends with a “/”, it is not necessary to add another slash mark. For example, In the example, the livestreaming address is:rtmp://10.39.12.189:1935, and the livestreaming code is :livxxxme. The combination is: rtmp://10.39.12.189:1935/livxxxme.

组<5@2x.png>

4. After entering “RTMP Address”, “Livestream Resolution” and “Livestream Bitrate”, tap “Start”. A countdown “3/2/1” will appear. The livestream will start automatically once the countdown ends. After the livestreaming platform is connected successfully, a red icon will appear on the camera view.

组<6@2x.png>
