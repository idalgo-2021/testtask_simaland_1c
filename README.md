# testtask_simaland_1c

Каркасная конфигурация товароучетной системы

Создана в рамках выполнения тестового задания в одну из крупных торговых компаний(в 2015 году). Использована технология обычных форм.

**Задание:**

Выполнив все пункты, необходимо завести пару примеров, выгрузить базу в dt файл и выслать в ответном письме.

Пункт 1.
Создать конфигурацию для учета складских остатков. Требования к конфигурации:
- Возможность ведения остатков (количественные и суммовые) в разрезе складов и номенклатуры.
- В конфигурации должны присутствовать документы прихода, расхода и перемещения номенклатуры.
- В конфигурации должны присутствовать отчеты: обороты по складам, остатки по складам.

Пункт 2.
Создать обработку загрузки остатков в конфигурацию из Excel.Структура файла(см.ФайлСОстатками.xls):
	- Номенклатура Склад Количество
	- Пружина Склад 1 10
	- Корпус Склад 2 15
	- Карандаш Склад 1 20

Пункт 3.
Дополнительные требования к конфигурации:
- Добавить возможность ведения остатков(суммовых) номенклатуры «По средней» и по «ФИФО»
- Добавить документ инвентаризации номенклатуры, который будет заполняться текущими остатками по складу, и будет корректировать остатки.
- Добавить в документы Прихода и Расхода, контрагента.
- Добавить документы оплаты контрагентам.
- Добавить отчеты: обороты и остатки по взаиморасчетам с контрагентами и обороты и остатки по денежным средствам с использованием компоновки данных. Дать пользователю возможность изменения настоек отчета.

Пункт 4.
Дополнительные требования к конфигурации:
- Создать механизм создания и редактирования состава изделия (минимум 2 уровня вложенности изделие/деталь/материал).
- Создать отчет по потребности в материалах для производства детали с учетом остатков материалов на складах.
