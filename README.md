# KillTrack Unique Main Menu — Terminal Zone

Полностью переработанное главное меню для **S.T.A.L.K.E.R. Anomaly / G.A.M.M.A.**

## Почему уникально

Большинство модов (включая то, что на твоём скрине) делают одно и то же:
- кнопки **справа**
- маленький шрифт
- почти чёрный фон

**Мы делаем наоборот:**

- Кнопки **слева** (крупный `graffiti32`)
- Полноэкранный кинематографичный фон
- Левый тёмный градиент + тонкая акцентная линия
- Больше воздуха между пунктами
- Стиль "терминал в Зоне"

## Быстрый старт

1. Скопируй `gamedata` в игру / MO2.
2. Положи текстуры:
   ```
   textures/ui/ui_mm_terminal_bg.dds
   textures/ui/ui_mm_terminal_gradient.dds
   textures/ui/ui_mm_terminal_line.dds
   textures/ui/ui_mm_terminal_logo.dds
   textures/ui/ui_mm_terminal_slider.dds
   ```
3. Музыка:
   ```
   sounds/music/terminal_zone_theme.ogg
   ```

## Где взять готовые ассеты

**Анимированные фоны (рекомендую):**
- [Zaper Animated Main Menu 2.2](https://www.moddb.com/mods/stalker-anomaly/addons/zaper-animated-main-menu-21-for-169-2k) — лучший выбор
- [Atmospheric Animated Background](https://www.moddb.com/addons/atmospheric-animated-background-menu)

**Музыка (бесплатно):**
- Официальный MoozE: https://soc.stalker-game.com/?page=soundtrack  
  → `Radwind Pt.2` или `Dead Cities Pt.2` идеально подходят
- [EYEWIDEASCA](https://www.moddb.com/mods/stalker-anomaly/addons/eyewideasca-main-menu-music)

После скачивания просто переименуй файлы под наши пути.

## Совместимость

- MCM (кнопка есть во всех меню)
- G.A.M.M.A. 0.9.5 / Anomaly 1.5.x
- Last Save to Top

## Структура

```
gamedata/
├── configs/ui/ui_mm_main_16.xml
├── textures/ui/          ← сюда текстуры
└── sounds/music/         ← сюда музыку
```

---

**KillTrack Project**  
Предыдущий Kill Confirm сохранён в backup.
