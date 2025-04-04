---
layout: default
title: VPC — Віртуальна приватна хмара
parent: AWS
nav_order: 1
---

# VPC — Віртуальна приватна хмара

VPC (Virtual Private Cloud) — це ізольований логічний сегмент хмари AWS, у якому ви створюєте власну віртуальну мережу.

## Компоненти:
- CIDR блок
- Підмережі (Public / Private)
- Internet Gateway, NAT Gateway
- Route Tables
- Security Groups / Network ACLs

## Типовий сценарій:
- Створення VPC з CIDR `10.0.0.0/16`
- Підмережі `10.0.1.0/24` (публічна), `10.0.2.0/24` (приватна)
- IGW для публічної, NAT GW для приватної
