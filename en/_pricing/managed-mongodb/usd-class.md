{% list tabs %}

- Rate for 1 month

    Host class | Rate for month | With CVoS for 1 year | With CVoS for 3 years
    ----- | ----- | ----- | -----
    **Intel Broadwell** |
    {{ b1-nano }}| {{ sku|USD|mdb.cluster.mongodb.b1.nano|month|int|string }} | − | −
    {{ b1-micro }} | {{ sku|USD|mdb.cluster.mongodb.b1.micro|month|int|string }} | − | −
    {{ b1-medium }} | {{ sku|USD|mdb.cluster.mongodb.b1.medium|month|int|string }} | − | −
    {{ s1-nano }}| {{ sku|USD|mdb.cluster.mongodb.s1.nano|month|int|string }} | − | −
    {{ s1-micro }} | {{ sku|USD|mdb.cluster.mongodb.s1.micro|month|int|string }} | − | −
    {{ s1-small }} | {{ sku|USD|mdb.cluster.mongodb.s1.small|month|int|string }} | − | −
    {{ s1-medium }} | {{ sku|USD|mdb.cluster.mongodb.s1.medium|month|int|string }} | − | −
    {{ s1-large }} | {{ sku|USD|mdb.cluster.mongodb.s1.large|month|int|string }} | − | −
    {{ s1-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s1.xlarge|month|int|string }} | − | −
    **Intel Cascade Lake** |
    {{ b2-nano }}| {{ sku|USD|mdb.cluster.mongodb.b2.nano|month|int|string }} | − | −
    {{ b2-micro }} | {{ sku|USD|mdb.cluster.mongodb.b2.micro|month|int|string }} | − | −
    {{ b2-medium }} | {{ sku|USD|mdb.cluster.mongodb.b2.medium|month|int|string }} | − | −
    {{ m2-micro }} | {{ sku|USD|mdb.cluster.mongodb.m2.micro|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y3|month|discount|percent|string }})
    {{ m2-small }} | {{ sku|USD|mdb.cluster.mongodb.m2.small|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y3|month|discount|percent|string }})
    {{ m2-medium }}| {{ sku|USD|mdb.cluster.mongodb.m2.medium|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y3|month|discount|percent|string }})
    {{ m2-large }} | {{ sku|USD|mdb.cluster.mongodb.m2.large|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y3|month|discount|percent|string }})
    {{ m2-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-2xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-3xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-4xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-5xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-6xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-7xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y3|month|discount|percent|string }})
    {{ m2-8xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-micro }} |{{ sku|USD|mdb.cluster.mongodb.s2.micro|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y3|month|discount|percent|string }})
    {{ s2-small }} | {{ sku|USD|mdb.cluster.mongodb.s2.small|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y3|month|discount|percent|string }})
    {{ s2-medium }} | {{ sku|USD|mdb.cluster.mongodb.s2.medium|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y3|month|discount|percent|string }})
    {{ s2-large }} | {{ sku|USD|mdb.cluster.mongodb.s2.large|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y3|month|discount|percent|string }})
    {{ s2-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-2xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-3xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-4xlarge }}| {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-5xlarge }}| {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y3|month|discount|percent|string }})
    {{ s2-6xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|month|int|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y1|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y1|month|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y3|month|int|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y3|month|discount|percent|string }})

- Rate for 1 hour

    Host class | Rate for 1 hour | With CVoS for 1 year | With CVoS for 3 years
    ----- | ----- | ----- | -----
    **Intel Broadwell** |
    {{ b1-nano }}| {{ sku|USD|mdb.cluster.mongodb.b1.nano|string }} | − | −
    {{ b1-micro }} | {{ sku|USD|mdb.cluster.mongodb.b1.micro|string }} | − | −
    {{ b1-medium }} | {{ sku|USD|mdb.cluster.mongodb.b1.medium|string }} | − | −
    {{ s1-nano }}| {{ sku|USD|mdb.cluster.mongodb.s1.nano|string }} | − | −
    {{ s1-micro }} | {{ sku|USD|mdb.cluster.mongodb.s1.micro|string }} | − | −
    {{ s1-small }} | {{ sku|USD|mdb.cluster.mongodb.s1.small|string }} | − | −
    {{ s1-medium }} | {{ sku|USD|mdb.cluster.mongodb.s1.medium|string }} | − | −
    {{ s1-large }} | {{ sku|USD|mdb.cluster.mongodb.s1.large|string }} | − | −
    {{ s1-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s1.xlarge|string }} | − | −
    **Intel Cascade Lake** |
    {{ b2-nano }}| {{ sku|USD|mdb.cluster.mongodb.b2.nano|string }} | − | −
    {{ b2-micro }} | {{ sku|USD|mdb.cluster.mongodb.b2.micro|string }} | − | −
    {{ b2-medium }} | {{ sku|USD|mdb.cluster.mongodb.b2.medium|string }} | − | −
    {{ m2-micro }} | {{ sku|USD|mdb.cluster.mongodb.m2.micro|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.micro|cud.y3|discount|percent|string }})
    {{ m2-small }} | {{ sku|USD|mdb.cluster.mongodb.m2.small|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.small|cud.y3|discount|percent|string }})
    {{ m2-medium }}| {{ sku|USD|mdb.cluster.mongodb.m2.medium|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.medium|cud.y3|discount|percent|string }})
    {{ m2-large }} | {{ sku|USD|mdb.cluster.mongodb.m2.large|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.large|cud.y3|discount|percent|string }})
    {{ m2-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.xlarge|cud.y3|discount|percent|string }})
    {{ m2-2xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.2xlarge|cud.y3|discount|percent|string }})
    {{ m2-3xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.3xlarge|cud.y3|discount|percent|string }})
    {{ m2-4xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.4xlarge|cud.y3|discount|percent|string }})
    {{ m2-5xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.5xlarge|cud.y3|discount|percent|string }})
    {{ m2-6xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.6xlarge|cud.y3|discount|percent|string }})
    {{ m2-7xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.7xlarge|cud.y3|discount|percent|string }})
    {{ m2-8xlarge }} | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.m2.8xlarge|cud.y3|discount|percent|string }})
    {{ s2-micro }} | {{ sku|USD|mdb.cluster.mongodb.s2.micro|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.micro|cud.y3|discount|percent|string }})
    {{ s2-small }} | {{ sku|USD|mdb.cluster.mongodb.s2.small|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.small|cud.y3|discount|percent|string }})
    {{ s2-medium }} | {{ sku|USD|mdb.cluster.mongodb.s2.medium|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.medium|cud.y3|discount|percent|string }})
    {{ s2-large }} | {{ sku|USD|mdb.cluster.mongodb.s2.large|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.large|cud.y3|discount|percent|string }})
    {{ s2-xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.xlarge|cud.y3|discount|percent|string }})
    {{ s2-2xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.2xlarge|cud.y3|discount|percent|string }})
    {{ s2-3xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.3xlarge|cud.y3|discount|percent|string }})
    {{ s2-4xlarge }}| {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.4xlarge|cud.y3|discount|percent|string }})
    {{ s2-5xlarge }}| {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.5xlarge|cud.y3|discount|percent|string }})
    {{ s2-6xlarge }} | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|string }} | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y1|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y1|discount|percent|string }}) | {{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y3|string }} ({{ sku|USD|mdb.cluster.mongodb.s2.6xlarge|cud.y3|discount|percent|string }})
    
{% endlist %}