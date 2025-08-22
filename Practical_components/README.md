## Реализация каскадной ML-системы / Cascaded ML System Implementation

[Русский](#русский) | [English](#english)

<a name="русский"></a>
### Русский
**Практическая реализация одного из этапов каскадной ML-системы для оптимизации контекстной рекламы**

Данный модуль представляет собой работающий proof-of-concept, демонстрирующий применение подхода многокритериальной оптимизации к реальным данным. Реализация включает стартовые модули для:

- Анализа и сегментации семантики
- Оптимизации ставок и бюджетов
- Вычисления метрик эффективности с учетом fairness-ограничений
- Визуализации результатов оптимизации

**Ключевые особенности:**
- Поддержка различных стратегий ставок (Manual CPC, Max Conversions)
- Интеграция метрик справедливости распределения (Nash Welfare)
- Автоматическая обработка и валидация данных из Яндекс.Директ/Google Ads
- Модульная архитектура для дальнейшего расширения

[Смотреть код реализации](practical_components/start_optimizer.ipynb)

<a name="english"></a>
### English
**Practical implementation of a cascaded ML system stage for contextual advertising optimization**

This module is a working proof-of-concept demonstrating the application of multi-criteria optimization approach to real-world data. The implementation includes starter modules for:

- Semantic analysis and segmentation
- Bid and budget optimization
- Performance metrics calculation with fairness constraints
- Optimization results visualization

**Key Features:**
- Support for various bidding strategies (Manual CPC, Max Conversions)
- Integration of fairness distribution metrics (Nash Welfare)
- Automatic processing and validation of data from Yandex.Direct/Google Ads
- Modular architecture for future expansion

[View implementation code](practical_components/start_optimizer.ipynb)
