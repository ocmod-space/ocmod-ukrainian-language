# Шо-і-як

## Попередження
ПАМ'ЯТАЙТЕ! ВИ НЕСЕТЕ ПОВНУ ВІДПОВІДАЛЬНІСТЬ ЗА БУДЬ-ЯКЕ ПОШКОДЖЕННЯ ФАЙЛІВ ВАШОГО МАГАЗИНУ АБО ВТРАТУ ДАНИХ, ТОМУ РОЗПОЧИНАЙТЕ ВСІ ЗМІНИ З РЕЗЕРВНОГО КОПІЮВАННЯ БД ТА ФАЙЛОВ!

## Інсталяція/Оновлення
* Extensions → Installer → [Upload]: `ukrainian-language.ocmod.zip`
* Extensions → Modifications → [Refresh]
* Dashboard → [Developer Settings] → [Refresh]
* System → Localisation → Languages → [+]:
    - `Language Name`: `Українська`
    - `Code`: `uk-ua`
    - `Locale`: `uk-UA,uk_UA.UTF-8,uk_UA,ukrainian`
    - `Status`: `Enabled`
    - `Sort Order`: *Optional*
* System → Settings → *Your Store* → [Edit] → Local:
    - Set default language for the store frontend in `Language` and for the admin in `Administration Language`

## Деінсталяція
* System → Settings → *Your Store* → [Edit] → Local:
    - Set other default language for the store frontend in `Language` and for the admin in `Administration Language`
* System → Localisation → Languages → [+]:
    - `Status`: `Disabled`
* Extensions → Installer → Install History → `ukrainian-language.ocmod.zip` → [Uninstall]
* Extensions → Modifications → [Refresh]
* Dashboard → [Developer Settings] → [Refresh]
