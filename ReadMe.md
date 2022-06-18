# How to install code styles tools

# Instructions
* [RU](#ru)
* [EN](#en)

# RU
* [Настройка Checkstyle для IntelliJ IDEA](#настройка-checkstyle-для-intellij-idea)
* [Настройка Code Style для IntelliJ IDEA](#настройка-code-style-для-intellij-idea)

## Настройка Checkstyle для IntelliJ IDEA
Используйте конфигурационный файл: https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/checkstyle/checkstyle.xml.
Настройки для pom.xml файла можно взять из [pom.xml](pom.xml) данного репозитория.

Для IntelliJ IDEA используйте следующий плагин: https://plugins.jetbrains.com/plugin/1065-checkstyle-idea

![image](docs/images/idea_checkstyle_plugin_installation.png)

![image](docs/images/idea_checkstyle_plugin_configuration.png)

Вставьте упомянутый URL: https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/checkstyle/checkstyle.xml

![image](docs/images/add_checkstyle_configuration.png)

![image](docs/images/add_checkstyle_configuration_2.png)

Выберете импортированую конфигурацию

![image](docs/images/checkstyle_imported_configuration.png)

Запускайте проверки

![image](docs/images/checkstyle_run_check.png)

```bash
mvn clean validate
```

## Настройка Code Style для IntelliJ IDEA

Скопируйте содержимое файла https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/formatter/.editorconfig в корневую директорию вашего проекта

Файл должен называться `.editorconfig`

![image](docs/images/editorconfig_seetings.png)

В настройках IntelliJ IDEA `Preferences -> Editor -> Code Style` секции, проверьте что `Enable EditorConfig support` выбрана

![image](docs/images/idea_code_style_import.png)

# EN
## Table of content
* [Configuration Checkstyle for IntelliJ IDEA](#configuration-checkstyle-for-intellij-idea)
* [Configuration Code Style for IntelliJ IDEA](#configuration-code-style-for-intellij-idea)

## Configuration Checkstyle for IntelliJ IDEA
Use the following config: https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/checkstyle/checkstyle.xml.
Settings for pom.xml can be taken from this repo [pom.xml](pom.xml)

In IntelliJ IDEA use the following plugin: https://plugins.jetbrains.com/plugin/1065-checkstyle-idea

![image](docs/images/idea_checkstyle_plugin_installation.png)

![image](docs/images/idea_checkstyle_plugin_configuration.png)

Paste mentioned URL: https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/checkstyle/checkstyle.xml

![image](docs/images/add_checkstyle_configuration.png)

![image](docs/images/add_checkstyle_configuration_2.png)

Check imported Configuration file

![image](docs/images/checkstyle_imported_configuration.png)

Sometimes run checks

![image](docs/images/checkstyle_run_check.png)

```bash
mvn clean validate
```

## Configuration Code Style for IntelliJ IDEA

Copy content of the file https://raw.githubusercontent.com/khda91/leveup-code-checkers-configurations/main/formatter/.editorconfig root directory of your to your project.

File must have name `.editorconfig`

![image](docs/images/editorconfig_seetings.png)


In the `Preferences -> Editor -> Code Style` section check that `Enable EditorConfig support` option is checked

![image](docs/images/idea_code_style_import.png)
