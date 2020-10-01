# Составные части проекта

## Пример проекта

![](../../../.gitbook/assets/izobrazhenie%20%2826%29.png)

## build.gradle

Глобальные зависимости, внутри проставляется как собирать проекты, как они связаны и тп

## settings.gradle

```text
include ':app', ':core'
rootProject.name = "TestKotlinGame"
```

В этом файле перечисляются модули \(в gradle описывается как project\). Что бы переименовать модуль, достаточно переимееновать директорию и поменять подключение в этом файле

то есть это настройки проекта и модулей в целом

## local.properties

Путь до SDK
