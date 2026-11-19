# Network Policy Lab

[English](#english) · [Русский](#русский)

## English

Network Policy Lab documents how applications interpret network policy rules. It focuses on three questions: how a domain name is resolved, which rule matches a connection, and which route the application selects.

### Research scope

- **Traffic classification and routing.** Examine domain matching, rule order, and the default action when no rule matches.
- **DNS and connectivity.** Trace how a DNS response affects subsequent connection attempts and distinguish name resolution failures from routing problems.
- **Configuration compatibility.** Compare how applications and versions interpret the same rule. For reproducible tests, record the software version, relevant configuration, and expected and observed behavior.

### Legal notice

The project publishes declarative rules and technical documentation for research, education, and network administration. It does not offer network access services or subscriptions. References to third-party software and rule sets identify components relevant to compatibility testing and imply no endorsement or affiliation.

Run tests only on systems you administer or have permission to test. Observe applicable law and respect third-party rights. The legal assessment of a publication or a particular use depends on the actual content and circumstances, irrespective of its stated purpose.

The materials are provided “as is.” To the extent permitted by applicable law, the authors give no warranty of accuracy, compatibility, or fitness for a particular purpose.

### Licensing

When reusing materials, consult the license applicable to the files in question. Third-party rule sets and documentation remain subject to their own terms.

## Русский

Network Policy Lab описывает, как приложения обрабатывают правила сетевой политики. В центре внимания три вопроса: как разрешается доменное имя, какое правило срабатывает для соединения и какой маршрут выбирает приложение.

### Направления исследований

- **Классификация трафика и маршрутизация.** Как приложение сопоставляет доменные имена с правилами, в каком порядке проверяет правила и какое действие выполняет, если ни одно из них не подошло.
- **DNS и диагностика соединений.** Как ответ DNS влияет на последующие попытки соединения и как отличить ошибку разрешения имени от проблемы с маршрутизацией.
- **Совместимость конфигураций.** Как разные приложения и их версии интерпретируют одно и то же правило. Чтобы проверку можно было повторить, фиксируют версию программы, существенные параметры конфигурации, ожидаемый и фактический результат.

### Правовое уведомление

Проект публикует декларативные правила и техническую документацию для исследований, обучения и администрирования сетей. Проект не предлагает услуги сетевого доступа или подписки на такие услуги. Сторонние программы и наборы правил упоминаются для проверки совместимости. Такое упоминание само по себе не означает одобрения или наличия партнёрских отношений.

Проводите испытания только на системах, которые вы администрируете или на тестирование которых у вас есть разрешение. Соблюдайте применимое законодательство и права третьих лиц. При правовой оценке публикации или конкретного способа её использования учитываются фактическое содержание и обстоятельства независимо от заявленной цели.

Материалы предоставляются «как есть». В пределах, допускаемых применимым законодательством, авторы не гарантируют их точность, совместимость или пригодность для конкретной цели.

### Лицензирование

При повторном использовании материалов руководствуйтесь условиями лицензии, применимой к конкретным файлам. Для сторонних наборов правил и документации действуют их собственные условия.
