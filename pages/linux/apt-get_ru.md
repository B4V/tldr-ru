# apt-get

> Менеджер пакетов в Debian и Ubuntu.

- Обновляет список доступных пакетов и версий. Рекомендуется выполнять перед запуском дополнительных команд apt-get:

`apt-get update`

- Устанавливает новый пакет:

`apt-get install {{package}}`

- Удаляет пакет:

`apt-get remove {{package}}`

- Обновляет установленные пакеты до последней доступной в репозиториях версии:

`apt-get upgrade`

- Удаляет "ненужные" пакеты (пакеты зависимости ранее удаленных пакетов):

`apt-get autoremove`

- Обновляет установленные пакеты (аналогично "upgrade"), а также доставляет новые пакеты зависимости и удаляет пакеты, которые устанавливались в систему и уже не используются:

`apt-get dist-upgrade`
