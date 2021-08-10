---

__system: {"dislikeVariants":["Нет ответа на мой вопрос","Рекомендации не помогли","Содержание не соответствует заголовку","Другое"]}
---
# Релизы {{   ml-platform-full-name }}

{% note tip %}

Чтобы всегда быть в курсе последних изменений и обновлений, подпишитесь на наш Telegram-канал новостей [{{ ml-platform-full-name }} Community](https://t.me/yandex_datasphere).

{% endnote %}

## Релиз 16.02.2021 { #160221 }

* Добавлен новый режим сохранения состояния **Autosave Commit Mode**.

## Релиз 10.02.2021 { #100221 }

* Изменился подход к сериализации состояния. Старый режим изменился и стал чуть удобнее, плюс появилась возможность включить режим **autosave**.
* Добавлена индикация загрузки GPU.
* Добавлена возможность обратиться в поддержку из сервиса.

## Релиз 24.12.2020 { #241220 }

* Представлен новый режим работы в {{  ml-platform-name }} — Early Access Version.

   **Early Access Version** — это pre-release версия системы, где будут анонсироваться все важные новые функциональные возможности.

   {% note info %}

   **Как воспользоваться?**

   Режим работы **Early Access Version** выбирается целиком для проекта. Для активации этого режима выберите в меню проекта **File** пункт **Enable Early Access Version**. 
   Вы всегда можете вернуться к обычному режиму работы, перейдя в проекте в пункт меню **File** и выбрав пункт **Disable Early Access Version**.

   **Где посмотреть:**

   Все детали того, что нового появилось в релизе и как воспользоваться, описаны в нашем новом ноутбуке: **Что нового в Early Access?**.

   {% endnote %}

* Добавлена индикация загрузки памяти и CPU в {{  ml-platform-name }} — объемы использования ядер процессора и памяти показываются прямо в интерфейсе ноутбука.
* Добавлена поддержка TensorBoard.
* Реализована возможность фонового асинхронного выполнения операций в специально обозначенных ячейках.

## Релиз 08.12.2020 { #081220 }

* Появился ознакомительный ноутбук **Добро пожаловать** (на русском языке). Он рассказывает, как устроен сервис и как быстро начать им пользоваться.

## Релиз 23.11.2020 { #231120 }

* Исправлена работа code completion.
* Добавлена поддержка `widgets`.

## Релиз 11.11.2020 { #111120 }

* Реализована поддержка TensorFlow версии 2.x.
* Реализована поддержка обновления предустановленных библиотек, в том числе TensorFlow. 
* Доработан алгоритм определения изменённых переменных, теперь в коммит попадают только действительно изменённые переменные, что сокращает время на сохранение состояния.
* Добавлен сниппет для работы с кластером SPARK.

## Релиз 01.10.2020 { #011020 }

* {{ ml-platform-full-name }} перешел в коммерческий доступ, он же GA, и стал платным. 

   Тарификация посекундная, оплата только за время вычислений, работа в самих ноутбуках не тарифицируется. 
   Единица тарификации — это один тарифицирующий юнит. Стоимость одного тарифицирующего юнита — это стоимость использования 1 ядра СPU в течение 1 секунды.

   Количество юнитов и стоимость зависит от конфигурации вычислительных ресурсов, подробное описание правил тарификации можно найти в [документации](pricing.md).

* Добавлена возможность [использования команды bash](concepts/magic.md#bash).
   
   Команда `%%bash` по-прежнему напрямую недоступна, но ее функциональностью можно воспользоваться следующим образом:
   * в заголовках ячейки необходимо указать `#!S:bash` (`S` — указание на тип ВМ, на которой нужно запустить bash).
   
   Ограничения:
   * не поддерживается запуск фоновых задач, например, `sshd`.
   * не поддерживается запуск `pip`, эта команда доступна по-прежнему только через `magic`.

* Появилась [полноценная интеграция со SPARK](concepts/data-proc.md). Можно запускать вычисления на уже существующих кластерах {{ dataproc-name }}, и даже создавать временные кластера {{ dataproc-name }}, непосредственно из сервиса {{ ml-platform-name }}. 
* Добавлено [версионирование и работа с контрольными точками](operations/projects/checkpoints.md). 
* Добавлены новые [типы конфигураций](concepts/configurations.md): `M` (8 cores, 0 gpu) и `XL` (32 cores, 4 gpu Nvidia v100).