# Задание 1: Оживляем персонажа!

## Описание

Наш персонаж в шутере в данный момент замер широко раскинув руки (T-pose), даже когда мы его двигает по игровому полю. Давайте попробуем оживить его. Для этого мы добавим в проект анимации и будем управлять ими из скрипта игрока.

## Требования

Зайди на сайт [Миксамо](https://www.mixamo.com/) и загрузи своего персонажа на вкладке Characters.

Скачай для своего персонажа анимации idle(ожидание), бега и прыжка.

Добавь анимации в проект и настрой им параметры, как мы делали [в прошлом модуле](https://github.com/copetonrob/YP_Unity_M2_W9/blob/main/Task1.md).

Создай аниматор контроллер и закинь в него анимации.

Создай в аниматор контроллере параметры bool isRun, bool isGrounded

https://github.com/copetonrob/YP_Unity_M3_W3/assets/58771904/e4029074-b9ad-4eae-b32b-e38fa191042c

<video src='https://github.com/copetonrob/YP_Unity_M3_W3/blob/main/video/video1.mp4' width=600/>

Создай переходы между анимациями как на картинке.

<video src='https://github.com/copetonrob/YP_Unity_M3_W3/blob/main/video/video2.mp4' width=600/>

Настрой параметры переходов. Не забудь убрать галочки Has Exit Time.

<video src='https://github.com/copetonrob/YP_Unity_M3_W3/blob/main/video/video3.mp4' width=600/>

В скрипте добавь ссылку на аниматор и укажи условия, при которых переключаются параметры аниматора. Нужно всего лишь уставновить bool переменные аниматора в нужное значение и смена анимаций по переходам произойдет автоматически.

<video src='https://github.com/copetonrob/YP_Unity_M3_W3/blob/main/video/video4.mp4' width=600/>

Не забудь указать ссылку на аниматор в модельке персонажа.

<img src="https://github.com/copetonrob/YP_Unity_M3_W2/blob/main/img/img1.png" width="300"/>
