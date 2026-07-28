# 💀 The Man From The Fog — Jumpscare Crash Fix (Forge 1.20.1)

![Minecraft Version](https://shields.io)
![Loader](https://shields.io)
![Status](https://shields.io)

## 🇷🇺 Описание проекта
Неофициальное исправление критической ошибки для хоррор-мода **The Man From The Fog (версия 1.4)**. 

**Что исправлено:**
* Устранён вылет игры с ошибкой `java.lang.NullPointerException` в классе `JumpscareDisplayOverlayIngameProcedure`.
* Теперь при смерти игрока от монстра игра не закрывается, анимация корректно завершается или пропускается, не ломая серверную часть одиночной игры.
* Код мода был успешно модифицирован и исправлен вручную через **Recaf**.

### 📥 Как установить:
1. Перейдите во вкладку [Releases](https://github.com/dorblysir228-source/the-man-from-the-fog-crash-fix/releases) справа.
2. Скачайте файл `patched_FIX.jar`.
3. Удалите оригинальный файл `The-Man-From-The-Fog-1.4-1.20.1.jar` из вашей папки `mods`.
4. Поместите скачанный `patched_FIX.jar` в папку `mods`.

---

## 🇺🇸 English Description
Unofficial crash fix for the horror mod **The Man From The Fog (v1.4)**.

**What's fixed:**
* Fixed critical game crash with `java.lang.NullPointerException` inside `JumpscareDisplayOverlayIngameProcedure`.
* The game no longer crashes when the player dies to the monster. The internal code ticks safely.
* Patched manually using bytecode manipulation via **Recaf**.

### 📥 How to install:
1. Go to the [Releases](https://github.com/dorblysir228-source/the-man-from-the-fog-crash-fix/releases) section on the right.
2. Download `patched_FIX.jar`.
3. Remove the original `The-Man-From-The-Fog-1.4-1.20.1.jar` from your `mods` folder.
4. Drop `patched_FIX.jar` into your `mods` folder.
