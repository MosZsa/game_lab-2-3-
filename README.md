# Car Game

![path_to_screenshot](https://github.com/MosZsa/game_lab-2-3-/assets/162978908/2fed3215-b7d2-48e4-9a7a-24b9f0c22e03)

## Описание

Car Game — это простая игра, созданная с использованием HTML, CSS и JavaScript. 
Цель игры — избегать встречного движения как можно дольше, набирая при этом наибольшее количество очков. 
Игра имеет плавную анимацию, фоновую музыку и интуитивно понятную систему управления.

##Особенности

- Плавная анимация дороги
- Машина, управляемая игроком
- Случайно генерируемые встречные машины
- Обнаружение столкновений
- Отслеживание очков
- Фоновая музыка с возможностью воспроизведения/паузы
- Возможность паузы и перезапуска игры

## Управление

Используйте клавиши со стрелками для управления машиной игрока:
- Стрелка влево (←): Движение влево
- Стрелка вправо (→): Движение вправо
- Стрелка вверх (↑): Движение вверх
- Стрелка вниз (↓): Движение вниз

## Инструкции

Нажмите Esc для паузы/возобновления игры.

Нажмите на экран мышкой, чтобы воспроизвести/поставить на паузу фоновую музыку.

## Установка и запуск

1. Скачайте или клонируйте репозиторий:
    ```sh
    git clone https://github.com/MosZsa/Сar-game-JS
    ```
2. Перейдите в директорию проекта:
    ```sh
    cd Сar-game-JS
    ```
3. Откройте файл game.html в браузере, чтобы начать игру.

## Структура игры

```plaintext
Сar-game-JS/
│
├── images/                
│   ├── road.jpg           
│   ├── car.png            
│   └── car_reverse.png    
│
├── css/
│   └── style.css          
│
├── js/
│   └── game.js            
│
└── game.html              
