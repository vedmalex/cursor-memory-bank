# Руководство по системе VAN.RULES

> **Продвинутая функция**: Это руководство охватывает систему подрежимов VAN.RULES для продвинутых пользователей, которым необходимо управлять и модифицировать правила Cursor IDE в экосистеме Memory Bank.

## 🎯 Обзор

Система VAN.RULES является продвинутым подрежимом VAN (Верификация, Анализ, Навигация), который предоставляет комплексные возможности управления правилами. Она позволяет опытным пользователям:

- Интегрировать `.cursor/rules` с Memory Bank
- Безопасно модифицировать существующие правила
- Создавать пользовательские правила
- Валидировать целостность правил
- Мониторить статус интеграции

## 🔧 Команды VAN.RULES

### Основные команды

| Команда               | Назначение                                           | Случай использования                            |
|-----------------------|------------------------------------------------------|-------------------------------------------------|
| `VAN.RULES`           | Активация подрежима управления правилами             | Общее администрирование правил                  |
| `VAN.RULES.INTEGRATE` | Интеграция .cursor правил с Memory Bank              | Первоначальная настройка или крупные обновления |
| `VAN.RULES.MODIFY`    | Модификация существующих правил с безопасным обходом | Исправления и обновления правил                 |
| `VAN.RULES.CREATE`    | Создание новых пользовательских правил               | Добавление проектно-специфичных правил          |
| `VAN.RULES.VALIDATE`  | Валидация всех правил на корректность                | Обеспечение качества                            |
| `VAN.RULES.STATUS`    | Проверка текущего статуса интеграции                 | Мониторинг системы                              |

### Примеры использования команд

#### Базовое управление правилами
```
Пользователь: VAN.RULES
Ассистент: OK VAN.RULES

🔧 Активирую подрежим управления VAN.RULES...
📚 Загружаю возможности управления правилами...
🔍 Анализирую текущую структуру правил...
```

#### Интеграция правил
```
Пользователь: VAN.RULES.INTEGRATE
Ассистент: OK VAN.RULES

🔗 Активирую процесс интеграции правил...
📚 Читаю руководства по интеграции...
🔍 Анализирую структуру .cursor/rules...
⚡ Планирую стратегию интеграции...
```

#### Валидация правил
```
Пользователь: VAN.RULES.VALIDATE
Ассистент: OK VAN.RULES

✅ Активирую процесс валидации правил...
🔍 Сканирую все .mdc файлы...
📊 Проверяю расширения файлов, регистр, ссылки...
📋 Генерирую отчет валидации...
```

## 🏗️ Архитектура системы

Система VAN.RULES обеспечивает мост между нативной системой правил Cursor IDE и управлением рабочими процессами Memory Bank.

### Преимущества интеграции

#### Для продвинутых пользователей:
- **Полный контроль**: Полный доступ к модификации .cursor правил
- **Системная интеграция**: Бесшовный мост между .cursor и Memory Bank
- **Оптимизация производительности**: Иерархическая загрузка правил и кэширование
- **Инструменты валидации**: Автоматизированная проверка и верификация правил

#### Для системных администраторов:
- **Резервное копирование/Восстановление**: Полное управление состоянием системы
- **Мониторинг здоровья**: Диагностика системы и оптимизация
- **Управление правилами**: Централизованное администрирование правил
- **Интеграционный мост**: Единый интерфейс для всех операций с правилами

## 🔄 Процесс интеграции

### Фаза 1: Анализ и подготовка

Система VAN.RULES начинает с анализа текущего состояния как `.cursor/rules`, так и системы Memory Bank:

1. **Анализ структуры**: Сканирует иерархию директории `.cursor/rules`
2. **Проверка совместимости**: Идентифицирует правила, подходящие для интеграции
3. **Картирование зависимостей**: Составляет карту взаимозависимостей правил
4. **Оценка производительности**: Оценивает возможности оптимизации

### Фаза 2: Стратегия интеграции

На основе анализа VAN.RULES реализует гибридный подход интеграции, который поддерживает совместимость при добавлении функциональности Memory Bank.

### Фаза 3: Оптимизация и поддержка

Система непрерывно оптимизирует загрузку и выполнение правил:

- **Ленивая загрузка**: Правила загружаются только при необходимости
- **Кэширование**: Часто используемые правила кэшируются в памяти
- **Предварительная загрузка**: Критические правила загружаются при запуске
- **Сжатие**: Неиспользуемые правила сжимаются для экономии памяти

## 📁 Структура файлов

### Директория интегрированных правил

```
memory-bank/
├── rules/
│   ├── core/                    # Основные системные правила
│   │   ├── rule-loading.md      # Механизмы загрузки правил
│   │   ├── optimization.md      # Оптимизация производительности
│   │   ├── mode-transitions.md  # Логика переходов режимов
│   │   └── creative-enforcement.md # Контроль творческих фаз
│   ├── levels/                  # Правила на основе сложности
│   │   ├── level1-quick-fix.md  # Рабочие процессы быстрых исправлений
│   │   ├── level2-enhancement.md # Рабочие процессы улучшений
│   │   ├── level3-feature.md    # Разработка функций
│   │   └── level4-system.md     # Системные изменения
│   ├── phases/                  # Правила фаз рабочего процесса
│   │   ├── creative-phase.md    # Правила творческого дизайна
│   │   ├── implementation-phase.md # Правила реализации
│   │   └── reflection-phase.md  # Правила захвата обучения
│   ├── visual-maps/             # Визуализация процессов
│   │   ├── entry-process.md     # Процессы VAN режима
│   │   ├── planning-process.md  # Процессы PLAN режима
│   │   ├── creative-process.md  # Процессы CREATIVE режима
│   │   └── implementation-process.md # Процессы IMPLEMENT
│   └── integration/             # Компоненты моста
│       ├── cursor-bridge.md     # Интеграция .cursor
│       ├── rule-mappings.md     # Определения маппинга правил
│       └── optimization-config.md # Настройки производительности
```

## 🔍 Мониторинг и диагностика

### Мониторинг статуса

Команда `VAN.RULES.STATUS` предоставляет комплексный статус системы:

```
📊 Статус системы VAN.RULES
├── Статус интеграции: ✅ Активна
├── Загружено правил: 23/45 (51%)
├── Использование кэша: 15.2MB/50MB (30%)
├── Последняя валидация: 2024-12-20 14:30:00
├── Производительность: Оптимальная
└── Проблемы: Не обнаружено
```

### Проверки здоровья

Регулярные проверки здоровья обеспечивают целостность системы:

- **Целостность правил**: Валидирует синтаксис и структуру правил
- **Валидация ссылок**: Проверяет все ссылки правил
- **Метрики производительности**: Мониторит время загрузки и использование памяти
- **Верификация зависимостей**: Обеспечивает выполнение всех зависимостей

## 🚨 Устранение неполадок

### Распространенные проблемы

#### Проблема: Правила не загружаются
**Симптомы**: Правила не активируются
**Решения**:
1. Проверьте расширения файлов правил (.mdc vs .md)
2. Верифицируйте соответствие glob-паттернов структуре файлов
3. Валидируйте синтаксис правил и заголовки
4. Проверьте лимиты памяти и настройки кэша

#### Проблема: Деградация производительности
**Симптомы**: Медленная загрузка или выполнение правил
**Решения**:
1. Включите ленивую загрузку
2. Увеличьте размер кэша
3. Сожмите неиспользуемые правила
4. Пересмотрите сложность правил

#### Проблема: Конфликты интеграции
**Симптомы**: Конфликты между .cursor и Memory Bank правилами
**Решения**:
1. Используйте VAN.RULES.VALIDATE для идентификации конфликтов
2. Пересмотрите приоритеты и старшинство правил
3. Обновите маппинги правил
4. Рассмотрите консолидацию правил

### Диагностические команды

```bash
# Проверить целостность файлов правил
VAN.RULES.VALIDATE

# Мониторить производительность системы
VAN.SYSTEM.HEALTH

# Просмотреть статус интеграции
VAN.RULES.STATUS

# Оптимизировать производительность системы
VAN.SYSTEM.OPTIMIZE
```

## 🎯 Лучшие практики

### Управление правилами

1. **Регулярная валидация**: Регулярно запускайте `VAN.RULES.VALIDATE`
2. **Мониторинг производительности**: Отслеживайте использование кэша и время загрузки
3. **Инкрементальные обновления**: Вносите небольшие, инкрементальные изменения правил
4. **Документация**: Тщательно документируйте все пользовательские правила

### Стратегия интеграции

1. **Постепенная миграция**: Мигрируйте правила постепенно, не все сразу
2. **Тестирование**: Тестируйте изменения правил в изолированных средах
3. **Резервное копирование**: Всегда создавайте резервные копии правил перед крупными изменениями
4. **Контроль версий**: Используйте git для отслеживания изменений правил

### Оптимизация производительности

1. **Ленивая загрузка**: Включите ленивую загрузку для лучшей производительности
2. **Управление кэшем**: Оптимизируйте размер кэша для ваших паттернов использования
3. **Консолидация правил**: Консолидируйте похожие правила для уменьшения накладных расходов
4. **Регулярная очистка**: Удаляйте неиспользуемые или устаревшие правила

## 🔗 Связанная документация

- [Руководство по редактированию правил](rules-editing-tutorial_ru.md) - Пошаговая модификация правил
- [Руководство по интеграции правил](rules-integration_ru.md) - Детальный процесс интеграции
- [Системное администрирование](system-administration_ru.md) - Подрежим VAN.SYSTEM
- [Справочник режимов Memory Bank](../user-guide/modes-reference_ru.md) - Основные режимы системы

## 📚 Продвинутые темы

### Разработка пользовательских правил

Для продвинутых пользователей, которые хотят создавать сложные пользовательские правила, см. [Руководство по интеграции правил](rules-integration_ru.md) для детальной информации о:

- Паттернах архитектуры правил
- Продвинутых glob-паттернах
- Техниках оптимизации производительности
- Интеграции с внешними системами

### Расширение системы

Система VAN.RULES спроектирована для расширения. Продвинутые пользователи могут:

- Создавать пользовательские загрузчики правил
- Реализовывать пользовательскую логику валидации
- Добавлять новые типы правил
- Интегрироваться с внешними системами правил

---

**Следующие шаги**:
- Изучите техники модификации правил в [Руководстве по редактированию правил](rules-editing-tutorial_ru.md)
- Исследуйте системное администрирование с [Руководством по системному администрированию](system-administration_ru.md)
- Просмотрите стратегии интеграции в [Руководстве по интеграции правил](rules-integration_ru.md)