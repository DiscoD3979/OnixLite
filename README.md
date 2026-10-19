<div align="center">

# ◆ Onix Lite

**Открытая версия клиента [Onix](https://github.com/DiscoD3979/Onix) для Mindustry**

[![Версия](https://img.shields.io/badge/Onix-v3.4.4--lite-8A2BE2?style=for-the-badge)](https://github.com/DiscoD3979/OnixLite/releases)
[![Mindustry](https://img.shields.io/badge/Mindustry-160.7-A03CFF?style=for-the-badge)](https://github.com/Anuken/Mindustry)
[![Java](https://img.shields.io/badge/Java-17%2B-ED8B00?style=for-the-badge)](https://adoptium.net/)
[![Лицензия](https://img.shields.io/badge/Лицензия-LICENSE-2E7D32?style=for-the-badge)](LICENSE)

</div>

---

**Onix Lite** — открытая версия клиента [Onix](https://github.com/DiscoD3979/Onix) для Mindustry.

Полная версия Onix закрыта и доступна только для друзей. Lite — это то же самое ядро
(те же функции автоматизации, тот же интерфейс), но:

- **без** закрытых фич полной версии;
- **без** чат-маячков — определение других клиентов идёт только по «мышиным» маячкам,
  так что в чате не появляется мусора;
- **без** возможности серверу управлять клиентом (в полной версии сервер может
  попросить клиент скачать и запустить другой jar — в Lite это отключено);
- определение других Onix-клиентов: у Lite в теге слева стоит буква **L**
  (`<L?>`), у полной версии — просто `<?>`.

---

## ▶ Как запустить

1. Скачай `Onix-Lite.jar` из [Releases](https://github.com/DiscoD3979/OnixLite/releases).
2. Нужна **Java 17 или новее** ([Adoptium Temurin](https://adoptium.net/)).
3. Запусти:

```
java -jar Onix-Lite.jar
```

---

## ⟳ Обновления

Клиент сам проверяет наличие новой версии при входе в лобби и предлагает обновиться
(с прогресс-баром). Ничего вручную скачивать не нужно.

---

## ⚒ Сборка из исходников

Исходники Lite лежат в приватном репозитории `OnixLite-src` (выдаётся по запросу).

```
git clone <url OnixLite-src>
cd OnixLite-src
./gradlew.bat desktop:dist -Plite=true
```

Собранный jar будет в `desktop/build/libs/Onix.jar`.

---

## ▦ Отличия от полной версии

| | Onix (полная) | Onix Lite |
|---|---|---|
| Доступ | по приглашению | открытый |
| Тег в игре | `<?>` | `<L?>` |
| Чат-маячки | есть | нет, только мышь |
| Сервер может запускать jar на клиенте | да | **нет** |
| Обновления | вручную | автоматически, из репозитория OnixLite |

---

## 📄 Лицензия

См. [LICENSE](LICENSE).

---

<div align="center">

<sub>◆ [Onix Lite](https://github.com/DiscoD3979/OnixLite) — репозиторий с релизами</sub>

</div>
