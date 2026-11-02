# SWMP — Solver Want More Packages!

**SWMP (Solver Want More Packages!)** — основной встроенный репозиторий программного обеспечения для операционной системы **SolverUNIX**.

SWMP предназначен для распространения, хранения и установки готовых бинарных пакетов. Его задача — сделать установку программ в SolverUNIX простой и удобной.

---

## 🇷🇺 Русский

### О проекте

SWMP — официальный репозиторий пакетов SolverUNIX. Он является частью экосистемы SolverUNIX и предназначен для предоставления пользователям программного обеспечения в готовом бинарном виде.

Вместо обязательной сборки программ из исходного кода SWMP использует предварительно собранные пакеты, которые можно установить через пакетный менеджер `solpkg`.

### Возможности

- Распространение бинарных пакетов.
- Установка и удаление программ.
- Переустановка пакетов.
- Обновление информации о репозиториях.
- Обновление установленного программного обеспечения.
- Возможность использования сторонних репозиториев.

### Пакетный менеджер

Для управления пакетами используется `solpkg`.

Основные команды:

| Команда | Описание |
|---|---|
| `ins` | Установка пакета |
| `ins --reinst` | Переустановка пакета |
| `dlt` | Удаление пакета |
| `upd` | Обновление информации о репозиториях |
| `upg` | Обновление системы |

Примеры использования:

```bash
solas solpkg ins firefox
solas solpkg ins --reinst firefox
solas solpkg dlt firefox
solas solpkg upd --repos
solas solpkg upg
```

### Сторонние репозитории

SWMP не ограничивает пользователя только встроенным репозиторием.

SolverUNIX предусматривает возможность подключения сторонних репозиториев. Пользователи и разработчики смогут создавать собственные источники пакетов.

### Цели проекта

- Создать удобную систему распространения программного обеспечения.
- Обеспечить централизованный репозиторий для SolverUNIX.
- Поддерживать бинарное распространение пакетов.
- Предоставить возможность использования сторонних репозиториев.

---

## 🇬🇧 English

### About

SWMP is the official built-in software repository of **SolverUNIX**.

It is designed to distribute, store and install ready-to-use binary packages. Its goal is to make software installation in SolverUNIX simple and convenient.

Instead of requiring users to compile software from source code, SWMP provides prebuilt packages that can be installed using the `solpkg` package manager.

### Features

- Binary package distribution.
- Package installation and removal.
- Package reinstallation.
- Repository metadata updates.
- Installed software updates.
- Support for third-party repositories.

### Package Manager

SWMP uses `solpkg` for package management.

Main commands:

| Command | Description |
|---|---|
| `ins` | Install a package |
| `ins --reinst` | Reinstall a package |
| `dlt` | Remove a package |
| `upd` | Update repository information |
| `upg` | Upgrade the system |

Usage examples:

```bash
solas solpkg ins firefox
solas solpkg ins --reinst firefox
solas solpkg dlt firefox
solas solpkg upd --repos
solas solpkg upg
```

### Third-party Repositories

SWMP does not restrict users to the built-in repository.

SolverUNIX is designed to support third-party repositories. Users and developers will be able to create and maintain their own package sources.

### Project Goals

- Build a convenient software distribution system.
- Provide a centralized repository for SolverUNIX.
- Support binary package distribution.
- Allow users to connect third-party repositories.

---

## Project Status

SWMP is part of the SolverUNIX ecosystem and is under development.

**SWMP — Solver Want More Packages!**

*Part of the SolverUNIX project.*
