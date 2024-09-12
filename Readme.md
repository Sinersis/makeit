# Установка make для Windows, macOS и Linux

## Инструкция на русском языке

### Установка make на Windows

1. **Скачать и установить MSYS2**:
    - Перейдите на [официальный сайт MSYS2](https://www.msys2.org/) и скачайте установочный файл для Windows.
    - Установите MSYS2, следуя инструкциям на экране.

2. **Открыть MSYS2 MSYS**:
    - Запустите приложение "MSYS2 MSYS" из меню "Пуск".

3. **Обновить пакеты**:
    - В терминале MSYS2 введите следующие команды для обновления системы:
      ```sh
      pacman -Syu
      pacman -Su
      ```

4. **Установить make**:
    - После обновления системы установите `make` с помощью команды:
      ```sh
      pacman -S make
      ```

5. **Проверить установку**:
    - Введите команду `make --version` в терминале MSYS2, чтобы убедиться, что `make` установлен и работает.

### Установка make на macOS

1. **Открыть терминал**:
    - Откройте "Терминал" через Launchpad или Finder.

2. **Установить Xcode Command Line Tools**:
    - Введите команду:
      ```sh
      xcode-select --install
      ```
    - Появится диалоговое окно, предлагающее установить инструменты командной строки Xcode. Нажмите "Установить".

3. **Проверить установку**:
    - После установки проверьте `make`, введя команду:
      ```sh
      make --version
      ```

### Установка make на Linux (Ubuntu, Debian, Fedora)

#### Для Ubuntu и Debian:

1. **Открыть терминал**:
    - Нажмите `Ctrl + Alt + T` для открытия терминала.

2. **Обновить список пакетов**:
    - Введите команду:
      ```sh
      sudo apt update
      ```

3. **Установить make**:
    - Введите команду:
      ```sh
      sudo apt install build-essential
      ```
    - Пакет `build-essential` включает в себя `make` и другие инструменты для компиляции.

4. **Проверить установку**:
    - Введите команду:
      ```sh
      make --version
      ```

#### Для Fedora:

1. **Открыть терминал**:
    - Нажмите `Ctrl + Alt + T` для открытия терминала.

2. **Установить make**:
    - Введите команду:
      ```sh
      sudo dnf install make
      ```

3. **Проверить установку**:
    - Введите команду:
      ```sh
      make --version
      ```

---

# Installing make for Windows, macOS, and Linux

## Instructions in English

### Installing make on Windows

1. **Download and Install MSYS2**:
    - Go to the [official MSYS2 website](https://www.msys2.org/) and download the installer for Windows.
    - Install MSYS2 by following the on-screen instructions.

2. **Open MSYS2 MSYS**:
    - Launch the "MSYS2 MSYS" application from the Start menu.

3. **Update Packages**:
    - In the MSYS2 terminal, enter the following commands to update the system:
      ```sh
      pacman -Syu
      pacman -Su
      ```

4. **Install make**:
    - After updating the system, install `make` with the command:
      ```sh
      pacman -S make
      ```

5. **Verify Installation**:
    - Enter the command `make --version` in the MSYS2 terminal to ensure `make` is installed and working.

### Installing make on macOS

1. **Open Terminal**:
    - Open the "Terminal" via Launchpad or Finder.

2. **Install Xcode Command Line Tools**:
    - Enter the command:
      ```sh
      xcode-select --install
      ```
    - A dialog will appear prompting you to install Xcode Command Line Tools. Click "Install".

3. **Verify Installation**:
    - After installation, check `make` by entering:
      ```sh
      make --version
      ```

### Installing make on Linux (Ubuntu, Debian, Fedora)

#### For Ubuntu and Debian:

1. **Open Terminal**:
    - Press `Ctrl + Alt + T` to open the terminal.

2. **Update Package List**:
    - Enter the command:
      ```sh
      sudo apt update
      ```

3. **Install make**:
    - Enter the command:
      ```sh
      sudo apt install build-essential
      ```
    - The `build-essential` package includes `make` and other necessary build tools.

4. **Verify Installation**:
    - Enter the command:
      ```sh
      make --version
      ```

#### For Fedora:

1. **Open Terminal**:
    - Press `Ctrl + Alt + T` to open the terminal.

2. **Install make**:
    - Enter the command:
      ```sh
      sudo dnf install make
      ```

3. **Verify Installation**:
    - Enter the command:
      ```sh
      make --version
      ```