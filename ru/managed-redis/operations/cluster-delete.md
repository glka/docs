# Удаление кластера

> [!IMPORTANT]
>
> Резервные копии удаленного кластера хранятся 7 дней.

---

**[!TAB Консоль управления]**

1. Откройте страницу каталога в консоли управления.
1. Нажмите плитку **[!KEYREF mrd-name]**.
1. Нажмите значок ![image](../../_assets/options.svg) для нужного кластера и выберите пункт **Удалить**.
1. В открывшемся окне поставьте флаг **Я удаляю кластер** и нажмите кнопку **Удалить**.

**[!TAB CLI]**

[!INCLUDE [cli-install](../../_includes/cli-install.md)]

[!INCLUDE [default-catalogue](../../_includes/default-catalogue.md)]

Чтобы удалить кластер, выполните команду:

```
$ [!KEYREF yc-mdb-rd] cluster delete <имя или идентификатор кластера>
```

Идентификатор и имя кластера можно запросить со [списком кластеров в каталоге](cluster-list.md).

---

