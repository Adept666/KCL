# KCL

KiCad Library

## Перечень символов

| Наименование | Наименование в Kicad | Позиционное обозначение | Номера выводов |
| --- | --- | --- | --- |
| Транзистор с P-N-переходами: |
| N-P-N общего назначения | BJT_NPN_GENERAL | VT? | B, C, E |
| P-N-P общего назначения | BJT_PNP_GENERAL | VT? | B, C, E |
| Конденсатор: |
| Вариконд | CAPACITOR_FERROELECTRIC | C? | 1, 2 |
| Неполяризованный | CAPACITOR_NON-POLARIZED | C? | 1, 2 |
| Поляризованный | CAPACITOR_POLARIZED | C? | +, - |
| Подстроечный | CAPACITOR_PRESET | C? | 1, 2 |
| Регулируемый | CAPACITOR_VARIABLE | C? | 1, 2 |
| Разъём: |
| Розетка, 001 конт., ширина поля – 20 | CONNECTOR_F_001_20 | XS? | 1 |
| Розетка, 002 конт., ширина поля – 20 | CONNECTOR_F_002_20 | XS? | 1, 2 |
| Вилка, 001 конт., ширина поля – 20 | CONNECTOR_M_001_20 | XP? | 1 |
| Вилка, 002 конт., ширина поля – 20 | CONNECTOR_M_002_20 | XP? | 1, 2 |
| Вилка, 004 конт., ширина поля – 20 | CONNECTOR_M_004_20 | XP? | 1…4 |
| Вилка, 006 конт., ширина поля – 20 | CONNECTOR_M_006_20 | XP? | 1…6 |
| Вилка, 010 конт., ширина поля – 20 | CONNECTOR_M_010_20 | XP? | 1…10 |
| Вилка, 014 конт., ширина поля – 20 | CONNECTOR_M_014_20 | XP? | 1…14 |
| Вилка, 020 конт., ширина поля – 20 | CONNECTOR_M_020_20 | XP? | 1…20 |
| Вилка, 040 конт., ширина поля – 20 | CONNECTOR_M_040_20 | XP? | 1…40 |
| Вилка коаксиального разъема питания, ширина поля – 20 | CONNECTOR_M_BARREL_20 | XP? | 1, 3, 2 |
| Диод: |
| Семисегментный индикатор, 1 разряд, общий анод | DIODE_7SEG_1DIG_CA | HG? | A1, CA…CH |
| Семисегментный индикатор, 1 разряд, общий катод | DIODE_7SEG_1DIG_CC | HG? | C1, AA…AH |
| Семисегментный индикатор, 2 разряда, общий анод, динамическая индикация | DIODE_7SEG_2DIG_CA_D | HG? | A1, A2, CA…CH |
| Семисегментный индикатор, 2 разряда, общий анод, статическая индикация | DIODE_7SEG_2DIG_CA_S | HG?A…HG?B | A1, C1A…C1H, A2, C2A…C2H |
| Семисегментный индикатор, 2 разряда, общий катод, динамическая индикация | DIODE_7SEG_2DIG_CC_D | HG? | C1, C2, AA…AH |
| Семисегментный индикатор, 2 разряда, общий катод, статическая индикация | DIODE_7SEG_2DIG_CC_S | HG?A…HG?B | C1, A1A…A1H, C2, A2A…A2H |
| Семисегментный индикатор, 3 разряда, общий анод, динамическая индикация | DIODE_7SEG_3DIG_CA_D | HG? | A1, A2, A3, CA…CH |
| Семисегментный индикатор, 3 разряда, общий катод, динамическая индикация | DIODE_7SEG_3DIG_CC_D | HG? | C1, C2, C3, AA…AH |
| Семисегментный индикатор, 4 разряда, общий анод, статическая индикация | DIODE_7SEG_4DIG_CA_S | HG?A…HG?D | A1, C1A…C1H, A2, C2A…C2H, A3, C3A…C3H, A4, C4A…C4H |
| Семисегментный индикатор, 4 разряда, общий катод, статическая индикация | DIODE_7SEG_4DIG_CC_S | HG?A…HG?D | C1, A1A…A1H, C2, A2A…A2H, C3, A3A…A3H, C4, A4A…A4H |
| Обращённый | DIODE_BACKWARD | VD? | A, C |
| Общего назначения | DIODE_GENERAL | VD? | A, C |
| Светоизлучающий (стрелки слева) | DIODE_LIGHT-EMITTING_LEFT | HL? | A, C |
| Светоизлучающий (стрелки справа) | DIODE_LIGHT-EMITTING_RIGHT | HL? | A, C |
| Фотодиод (стрелки слева) | DIODE_PHOTO_LEFT | VD? | A, C |
| Фотодиод (стрелки справа) | DIODE_PHOTO_RIGHT | VD? | A, C |
| Шоттки | DIODE_SCHOTTKY | VD? | A, C |
| Туннельный | DIODE_TUNNEL | VD? | A, C |
| Стабилитрон (двухсторонний) | DIODE_ZENER_DA | VD? | 1, 2 |
| Стабилитрон (односторонний) | DIODE_ZENER_SA | VD? | A, C |
| Электрохимический источник тока: |
| Батарея | ELECTROCHEMICAL_BATTERY | GB? | +, - |
| Элемент | ELECTROCHEMICAL_CELL | G? | +, - |
| Энкодер: |
| Контактный инкрементный | ENCODER_CONTACTING_INC | BR? | A, B, C |
| Контактный инкрементный с кнопкой | ENCODER_CONTACTING_INC_B | BR?A…BR?B | A, B, C, COM, NO |
| Оптический инкрементный | ENCODER_OPTICAL_INC | BR? | A, B, VCC, GND |
| Оптический инкрементный с кнопкой | ENCODER_OPTICAL_INC_B | BR?A…BR?B | A, B, VCC, GND, COM, NO |
| Монтажное отверстие: |
| Монтажное отверстие | HOLE | XS? | 0, 0, 0, 0 |
| Катушка индуктивности: |
| Без магнитопровода | INDUCTOR_AC | L? | 1, 2 |
| С ферромагнитным или ферримагнитным сердечником | INDUCTOR_FMC | L? | 1, 2 |
| С магнитодиэлектрическим сердечником | INDUCTOR_MDC | L? | 1, 2 |
| Перемычка: |
| Перемычка | JUMPER | J? | J, J |
| Земля, общая точка, питание: |
| Общая точка | POWER_COM | #PWR | COM |
| Питание | POWER_V | #PWR | V |
| Питание VCC | POWER_VCC | #PWR | VCC |
| Питание VDD | POWER_VDD | #PWR | VDD |
| Резистор: |
| Общего назначения | RESISTOR_GENERAL | R? | 1, 2 |
| Переключатель: |
| Блок переключателей, 5 каналов | SWITCH_BLOCK_05 | SA?A…SA?E | 1…10 |
| Кнопка замыкающая, 1 полоса | SWITCH_BUTTON_NO_01 | SB? | 1COM, 1NO |
| SK-23D29-G | SWITCH_SPECIAL_SK-23D29-G | SA? | 1…8 |
| SK-42D01-G | SWITCH_SPECIAL_SK-42D01-G | SA? | 1…12 |

## Author

Igor Vladimirovich Ivanov

## License

This project is licensed under GNU General Public License v3.0 or later
