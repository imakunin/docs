`security_groups` — [группы безопасности](../../../../../vpc/concepts/security-groups.md) для сетевого трафика.

Правила групп безопасности применяются к трансферу. Они позволяют открыть сетевой доступ с ВМ трансфера к кластеру. Подробнее см. в разделе [{#T}](../../../../../data-transfer/concepts/network.md).

Группы безопасности и подсеть `subnet_id`, если она указана, должны принадлежать той же сети, в которой размещен кластер.

{% note info %}

В {{ TF }} сеть для групп безопасности задавать не нужно.

{% endnote %}