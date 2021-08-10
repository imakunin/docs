---

__system: {"dislikeVariants":["Нет ответа на мой вопрос","Рекомендации не помогли","Содержание не соответствует заголовку","Другое"]}
---
# Установить уведомления о потреблении

Для контроля расходов в {{ yandex-cloud }} вы можете настраивать уведомления о потреблении с помощью бюджетов. Бюджет — это способ контролировать расходы на потребление ресурсов в {{ yandex-cloud }} за определенный период. 

В бюджете вы устанавливаете сумму расходов за период расчета для определенных ресурсов и настраиваете, при достижении какого порога потребления и кому будут отправлены уведомления. Вы можете задать несколько порогов и определить разных получателей уведомлений для каждого из них. Достижение установленного порога не влияет на дальнейшее потребление ресурсов. 

В качестве периода расчета можно выбрать месяц, квартал или год. С началом каждого следующего периода бюджет будет автоматически перезапускаться. Также вы можете самостоятельно настроить период расчета, указав даты его начала и окончания. Такой бюджет после завершения не перезапустится.

Бюджеты суммируют данные о потреблении в течение всего периода расчета. Например, созданный в середине месяца бюджет все равно будет учитывать все месячные затраты на указанные ресурсы. 

## Создать бюджет {#create-budget}

Для создания бюджета необходима роль `editor`. Для получения оповещений достаточно роли `viewer`. Подробнее об управлении доступом можно узнать в разделе [{#T}](../../iam/concepts/access-control/roles.md).

Чтобы создать бюджет:

1. В [консоли управления]({{ link-console-billing }}) нажмите значок ![image](../../_assets/ugly-sandwich.svg) и перейдите в раздел **Биллинг**.
1. Выберите аккаунт на странице **Список аккаунтов**.
1. Перейдите на страницу **Бюджеты** и нажмите **Создать бюджет**.
    1. Введите имя бюджета.
    1. Выберите период расчета бюджета. Укажите:

		* дату начала действия бюджета, если выбрали **Настраиваемый** период. Дата начала — первое число месяца.
		* дату окончания действия бюджета. Дата окончания устанавливает, когда бюджет перестанет считать потребление и отправлять уведомления. Дата окончания — последнее число месяца. Не может быть позже пяти лет от текущей даты.

    1. Выберите пользователей, которые получат уведомление при превышении бюджета.
    1. Определите область действия бюджета. Вы можете выбрать отдельные облака, каталоги и сервисы, которые будут входить в установленный бюджет. По умолчанию данные собираются со всех облаков, каталогов и сервисов, доступных выбранному платежному аккаунту. 
    1. Задайте сумму и тип бюджета. Тип **Стоимость потребления** собирает данные о стоимости ресурсов без учета различных скидок, тип **К оплате** учитывает скидки и активные промокоды.
    1. Установите хотя бы один порог потребления, при котором будут отправлены уведомления. Вы можете указать пороговое значение в процентах или валюте и выбрать пользователей, которые получат уведомления. Бюджет может иметь несколько пороговых значений.
   
   {% note info %}
   
   Пользователи, указанные в блоке **Общая информация**, будут получать уведомления при превышении каждого заданного порога. Пользователи, указанные при задании порога, получат уведомление только при превышении этого порога.
   
   Если при подсчете бюджета было превышено одновременно несколько порогов, пользователи получат только одно уведомление.
   
   {% endnote %}

1. После заполнения всех полей нажмите кнопку **Создать**. Бюджет будет создан.