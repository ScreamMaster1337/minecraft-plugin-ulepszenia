# Minecraft Item Upgrade Plugin

Minecraft Item Upgrade to plugin, który umożliwia graczom ulepszanie przedmiotów na serwerze. Dzięki prostym komendom można ulepszać przedmioty za pomocą tokenów lub określonych materiałów. Plugin pozwala również na przeładowanie konfiguracji.

## Funkcje
- **Ulepszanie przedmiotów za pomocą tokenów**: Gracze mogą ulepszać swoje przedmioty za pomocą tokenów.
- **Ulepszanie przedmiotów za pomocą materiałów**: Gracze mogą ulepszać swoje przedmioty za pomocą określonych materiałów.
- **Zarządzanie komendami**: Kontrola nad tym, jakie komendy mogą być używane przez graczy do ulepszania przedmiotów.
- **Konfiguracja ulepszeń**: Możliwość ustawienia, jakie przedmioty i enchanty można ulepszać oraz ile tokenów lub materiałów jest potrzebnych do ulepszenia.

## Użycie Komend

- `/ulepsz-kille`  
  **Opis:** Otwiera GUI do ulepszania przedmiotów za pomocą tokenów.

- `/ulepsz-kille reload`  
  **Opis:** Przeładowuje konfigurację pluginu dla ulepszania za pomocą tokenów.

- `/ulepsz-rudy`  
  **Opis:** Otwiera GUI do ulepszania przedmiotów za pomocą materiałów.

- `/ulepsz-rudy reload`  
  **Opis:** Przeładowuje konfigurację pluginu dla ulepszania za pomocą materiałów.

## Specjalne Permisje
- `m4code.reload`: Umożliwia użycie podkomend `/ulepsz-kille reload` oraz `/ulepsz-rudy reload`.

## Podgląd

Poniżej znajduje się zrzut ekranu prezentujący gui z komendy `/ulepsz-kille`:

![footer](https://cdn.discordapp.com/attachments/1102682877235310734/1293746981616877599/Zrzut_ekranu_2024-10-10_032817.png?ex=67087f45&is=67072dc5&hm=9fcaeaece99e0e8f711adfac6d653ebca5bf2a4c0ef83640ac64b3e41e0dce43&)

Poniżej znajduje się zrzut ekranu prezentujący gui z komendy `/ulepsz-rudy`:

![footer](https://cdn.discordapp.com/attachments/1102682877235310734/1293746981864210529/Zrzut_ekranu_2024-10-10_032832.png?ex=67087f45&is=67072dc5&hm=1affbf7936388162b696e9a80139bad82fdacd51e7d5a986e1a4f91984a25d28&)

## Konfiguracja

Plugin automatycznie tworzy plik konfiguracyjny:

### Przykład konfiguracji (`config.yml`):

```yaml
whitelist:
  - "DIAMOND_SWORD:14"
  - "DIAMOND_PICKAXE:15"
  - "DIAMOND_HELMET:10"
  - "DIAMOND_CHESTPLATE:11"
  - "DIAMOND_LEGGINGS:12"
  - "DIAMOND_BOOTS:13"

cost:
  DIAMOND_SWORD:
    "UNBREAKING 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "UNBREAKING 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "UNBREAKING 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
  DIAMOND_PICKAXE:
    "UNBREAKING 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "UNBREAKING 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "UNBREAKING 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
  DIAMOND_HELMET:
    "PROTECTION 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
  DIAMOND_CHESTPLATE:
    "PROTECTION 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
  DIAMOND_LEGGINGS:
    "PROTECTION 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
  DIAMOND_BOOTS:
    "PROTECTION 1":
      token: 5
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 2":
      token: 10
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"
    "PROTECTION 3":
      token: 15
      material:
        - "DIAMOND 9"
        - "GOLD_INGOT 15"
        - "IRON_INGOT 30"
        - "EMERALD 45"

upgrade:
  lore: "&a✔ Upgrade"
  line: 5

token:
  name: '&6Token zabójstw &4🗡4'
  lore:
    - '&8- &7Ten token możesz zdobyć'
    - '&8- &7poprzez wymianę &4zabójstw'
    - '&8- &7pod komendą &a/sklep-kille'
    - ''
    - '&8- &bSłuży on do kupowania lub ulepszenia'
    - '&8- &btwojej zbroji oraz broni u kowala'
  material: 'RED_DYE'
  enchantments:
    - 'DURABILITY 3'
  custom-model-data: 1
  flags:
    - 'HIDE_ENCHANTS'
    - 'HIDE_ATTRIBUTES'

```
**Wymagania:**
- Serwer Minecraft (wersja 1.16+)
- Java 8+

**Autor:** [ScreamMaster1337](https://github.com/ScreamMaster1337)  
**Licencja:** MIT
