
# 👾 Портфолио Unity разработчик - Дмитрий Петров

Привет! Меня зовут Дима, ниже подборка моих учебных и личных проектов на Unity. Сначала будут представлены мои личные работы, 
затем — 3 учебные в рамках курса [Онлайн-курс по архитектуре игр в Unity - Яковлев Илья](https://yakovlevgamedev.ru/page37501206.html)
для закрепления принципов SOLID и практики применения паттернов проектирования.

---

## 🚀 Проекты

### 1. **Zombie Survivors (2D Survival Shooter)**
*Шутер на выживание, где моим основным упором была проработка эффектов, анимации и звуков.*
- Несколько типов оружия - дробовик, винтовка и пистолет со своими паттернами стрельбы и звуками
- Tilemap-карта
- Визуальные и анимационные эффекты (брызги крови, выстрел ружья, смерть зомби)

[Подробнее →](https://github.com/Dormitori/zombie-survivors-unity)

<img src="https://github.com/Dormitori/zombie-survivors-unity/blob/6e074a0d5601277a7aa1b8795ff4342c70a39654/Media/zombie_survivors.gif" width="600">

---

### 2. **Balls Runner**
*3D раннер.*
- Генерация бесконечного трека с рандомными препятствиями.
- Самописный шейдер для создания фона - расширяющиеся квадраты для создания туннельного эффекта.
- Фиксирование рекордов.
- Разрушение шарика при смерти.

[Подробнее →](https://github.com/Dormitori/balls-runner-unity)

<img src="https://github.com/Dormitori/balls-runner-unity/blob/fd5248bbb188a3b43f6372fc50862f8be60b5a54/Screens/balls.gif" width="600">

---

### 3. **Mandelbulb Fractal Visualizer**
*Интерактивный 3D-визуализатор фрактала Мандельбульба (Mandelbulb) на Unity.*
- Реализация математической визуализации 3D-фрактала с помощью маленьких кубов (вокселей).
- Использование GPU-инстансирования для отрисовки mesh'а, отрисовка батчами для большей оптимизации FPS.
- Окрашивание фрактала с помощью шейдера на Shader Graph.

[Подробнее →](https://github.com/Dormitori/mondelbulb-unity)

<img src="https://github.com/Dormitori/mondelbulb-unity/blob/e26b4f88de71262c34730237afdf55a741bc9dce/Screens/Screen1.png" width="600">


---
## 🚀 Практика применения основных паттернов проектирования

### 1. **State machine - Механика патрулирования через машину состояний на Unity**
*AI: патрулирующий враг реагирует на игрока через машину состояний.*
- Разделение поведения на состояния: патрулирование, подозрение, преследование.
- Визуализация поля зрения через Gizmos.

[Подробнее →](https://github.com/Dormitori/patroller-state-machine-unity)

<img src="https://github.com/Dormitori/patroller-state-machine-unity/blob/1f5b8a454d7034c5c781762ab248b3c64f575a46/Media/state_machine.gif" width="600">

---

### 2. Strategy - Tower Defense — Враги и башни на стратегии перемещения/атаки  
*Механики перемещения и атаки врагов/башен реализованы через паттерн “Стратегия” с возможностью динамического переключения.*
- Гибкие паттерны движения и защиты врагов: линейно, с ускорением, по сплайну, по окружности.
- Многообразие режимов стрельбы башен: прямая и баллистическая траектория с расчетом оптимального момента выстрела, все выстрелы по врагам работают на упреждение.
- Абстракции IMovePattern и ICannonShootMode для легкого расширения поведения.

[Подробнее →](https://github.com/Dormitori/turrets-strategy-assignment)

<img src="https://github.com/Dormitori/turrets-strategy-assignment/blob/3f53c56b48435c2622ec781cf65727ae25e07f55/Media/example.gif" width="600">

### 3. **Mediator - HUD инвентаря для 2D top-down игры на Unity**
*2D топ-даун-игра: универсальный HUD-инвентарь c drag-n-drop.*
- Cвязь между игровыми компонентами и UI при помощи паттерна Медиатор.
- Подбор предметов с их "притягиванием" к игроку, отображение ячеек инвентаря и взаимодействие с ним.

[Подробнее →](https://github.com/Dormitori/ui-hud-mediator)

<img src="https://github.com/Dormitori/ui-hud-mediator/blob/74b953b76898442bb93f324385e801d263a0278b/Media/mediator.gif" width="600">

---

## Прочие проекты
### Quadcopter math Simulation

Моделируется и визуализируется полёт квадрокоптера в 3D по заранее заданной траектории и ориентации.

Задача

**Цель:**  
Показать поведение квадрокоптера, для которого известны значения координат \( x, y, z \) и углы Эйлера (ориентация) на каждом шаге.  
Это имитация движения БПЛА на основе результатов численного интегрирования параметров поступательного и углового движения (например, решения системы ОДУ метода Эйлера или Рунге-Кутты).


 <img src="https://github.com/Dormitori/quadcopter-math-simulation/blob/42b96707fade1381b4bc64fd1faf1f3a141d6ac9/animation.gif" width="600">

[Подробнее →](https://github.com/Dormitori/quadcopter-math-simulation/tree/main)
---

### BVP
Программа для решения кравевых задач методом продолжения по параметру и отображения результатов работы в виде графиков

<img src="https://github.com/Dormitori/BVP/blob/0d3cb75863c20369b16f81b934d560d0ee026f14/1.jpg" width="600">
<img src="https://github.com/Dormitori/BVP/blob/0d3cb75863c20369b16f81b934d560d0ee026f14/2.jpg" width="600">

[Подробнее →](https://github.com/Dormitori/BVP)

## 📞 Связаться / найти меня

- Telegram: https://t.me/dormi_tori
