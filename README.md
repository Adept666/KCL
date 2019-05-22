# KCL

KiCad Library

## List of symbols

| Description | Name | Designator | Pin numbers |
| --- | --- | --- | --- |
| Bipolar junction transistor: |
| N-P-N general-purpose | BJT_NPN_GENERAL | VT? | B, C, E |
| P-N-P general-purpose | BJT_PNP_GENERAL | VT? | B, C, E |
| Capacitor: |
| Ferroelectric | CAPACITOR_FERROELECTRIC | C? | 1, 2 |
| Non-polarized | CAPACITOR_NON-POLARIZED | C? | 1, 2 |
| Polarized | CAPACITOR_POLARIZED | C? | +, - |
| Preset | CAPACITOR_PRESET | C? | 1, 2 |
| Variable | CAPACITOR_VARIABLE | C? | 1, 2 |
| Connector: |
| Female, 001 pin, field width – 20 | CONNECTOR_F_001_20 | XS? | 1 |
| Female, 002 pins, field width – 20 | CONNECTOR_F_002_20 | XS? | 1, 2 |
| Male, 001 pins, field width – 20 | CONNECTOR_M_001_20 | XP? | 1 |
| Male, 002 pins, field width – 20 | CONNECTOR_M_002_20 | XP? | 1, 2 |
| Male, 004 pins, field width – 20 | CONNECTOR_M_004_20 | XP? | 1…4 |
| Male, 006 pins, field width – 20 | CONNECTOR_M_006_20 | XP? | 1…6 |
| Male, 010 pins, field width – 20 | CONNECTOR_M_010_20 | XP? | 1…10 |
| Male, 014 pins, field width – 20 | CONNECTOR_M_014_20 | XP? | 1…14 |
| Male, 020 pins, field width – 20 | CONNECTOR_M_020_20 | XP? | 1…20 |
| Male, 040 pins, field width – 20 | CONNECTOR_M_040_20 | XP? | 1…40 |
| Male coaxial power connector, field width – 20 | CONNECTOR_M_BARREL_20 | XP? | 1, 3, 2 |
| Diode: |
| Seven-segment indicator, 1 digit, common anode | DIODE_7SEG_1DIG_CA | HG? | A1, CA…CH |
| Seven-segment indicator, 1 digit, common cathode | DIODE_7SEG_1DIG_CC | HG? | C1, AA…AH |
| Seven-segment indicator, 2 digits, common anode, dynamic control | DIODE_7SEG_2DIG_CA_D | HG? | A1, A2, CA…CH |
| Seven-segment indicator, 2 digits, common anode, static control | DIODE_7SEG_2DIG_CA_S | HG?A…HG?B | A1, C1A…C1H, A2, C2A…C2H |
| Seven-segment indicator, 2 digits, common cathode, dynamic control | DIODE_7SEG_2DIG_CC_D | HG? | C1, C2, AA…AH |
| Seven-segment indicator, 2 digits, common cathode, static control | DIODE_7SEG_2DIG_CC_S | HG?A…HG?B | C1, A1A…A1H, C2, A2A…A2H |
| Seven-segment indicator, 3 digits, common anode, dynamic control | DIODE_7SEG_3DIG_CA_D | HG? | A1, A2, A3, CA…CH |
| Seven-segment indicator, 3 digits, common cathode, dynamic control | DIODE_7SEG_3DIG_CC_D | HG? | C1, C2, C3, AA…AH |
| Seven-segment indicator, 4 digits, common anode, static control | DIODE_7SEG_4DIG_CA_S | HG?A…HG?D | A1, C1A…C1H, A2, C2A…C2H, A3, C3A…C3H, A4, C4A…C4H |
| Seven-segment indicator, 4 digits, common cathode, static control | DIODE_7SEG_4DIG_CC_S | HG?A…HG?D | C1, A1A…A1H, C2, A2A…A2H, C3, A3A…A3H, C4, A4A…A4H |
| Backward | DIODE_BACKWARD | VD? | A, C |
| General-purpose | DIODE_GENERAL | VD? | A, C |
| Light-emitting (left to right arrows) | DIODE_LIGHT-EMITTING_LEFT | HL? | A, C |
| Light-emitting (right to left arrows) | DIODE_LIGHT-EMITTING_RIGHT | HL? | A, C |
| Photodiode (left to right arrows) | DIODE_PHOTO_LEFT | VD? | A, C |
| Photodiode (right to left arrows) | DIODE_PHOTO_RIGHT | VD? | A, C |
| Schottky | DIODE_SCHOTTKY | VD? | A, C |
| Tunnel | DIODE_TUNNEL | VD? | A, C |
| Zener (unidirectional) | DIODE_ZENER_DA | VD? | 1, 2 |
| Zener (bidirectional) | DIODE_ZENER_SA | VD? | A, C |
| Electrochemical current source: |
| Battery | ELECTROCHEMICAL_BATTERY | GB? | +, - |
| Cell | ELECTROCHEMICAL_CELL | G? | +, - |
| Encoder: |
| Contacting incremental | ENCODER_CONTACTING_INC | BR? | A, B, C |
| Contacting incremental with button | ENCODER_CONTACTING_INC_B | BR?A…BR?B | A, B, C, COM, NO |
| Optical incremental | ENCODER_OPTICAL_INC | BR? | A, B, VCC, GND |
| Optical incremental with button | ENCODER_OPTICAL_INC_B | BR?A…BR?B | A, B, VCC, GND, COM, NO |
| Mounting hole: |
| Mounting hole | HOLE | XS? | 0, 0, 0, 0 |
| Integrated circuit: |
| Infrared receiver | IC_IRR | D? | VCC, OUT, GND |
| Regulator, negative-voltage | IC_REGULATOR_NEG | D? | IN, GND, OUT|
| Regulator, negative-voltage, adjustable | IC_REGULATOR_NEG_ADJ | D? | IN, ADJ, OUT|
| Regulator, positive-voltage | IC_REGULATOR_POS | D? | IN, GND, OUT|
| Regulator, positive-voltage, adjustable | IC_REGULATOR_POS_ADJ | D? | IN, ADJ, OUT|
| Inductor: |
| Air core | INDUCTOR_AC | L? | 1, 2 |
| Ferromagnetic or ferrimagnetic core | INDUCTOR_FMC | L? | 1, 2 |
| Magnetodielectric core | INDUCTOR_MDC | L? | 1, 2 |
| Jumper: |
| Jumper | JUMPER | J? | J, J |
| Power: |
| Common point | POWER_COM | #PWR | COM |
| Power | POWER_V | #PWR | V |
| Power VCC | POWER_VCC | #PWR | VCC |
| Power VDD | POWER_VDD | #PWR | VDD |
| Resistor: |
| General-purpose | RESISTOR_GENERAL | R? | 1, 2 |
| Heater | RESISTOR_HEATER | EK? | 1, 2 |
| Preset | RESISTOR_PRESET | RP? | 1, 2, 3 |
| Thermistor with negative temperature coefficient (horizontal) | RESISTOR_THERMISTOR_NTC_H | RK? | 1, 2 |
| Thermistor with negative temperature coefficient (vertical) | RESISTOR_THERMISTOR_NTC_V | RK? | 1, 2 |
| Thermistor with positive temperature coefficient (horizontal) | RESISTOR_THERMISTOR_PTC_H | RK? | 1, 2 |
| Thermistor with positive temperature coefficient (vertical) | RESISTOR_THERMISTOR_PTC_V | RK? | 1, 2 |
| Variable | RESISTOR_VARIABLE | RP? | 1, 2, 3 |
| Varistor (horizontal) | RESISTOR_VARISTOR_H | RU? | 1, 2 |
| Varistor (vertical) | RESISTOR_VARISTOR_V | RU? | 1, 2 |
| Switch: |
| Switch block, 5 channels | SWITCH_BLOCK_05 | SA?A…SA?E | 1…10 |
| Button, normally open, 1 pole | SWITCH_BUTTON_NO_01 | SB? | 1COM, 1NO |
| SK-23D29-G | SWITCH_SPECIAL_SK-23D29-G | SA? | 1…8 |
| SK-42D01-G | SWITCH_SPECIAL_SK-42D01-G | SA? | 1…12 |

## Перечень символов

| Описание | Наименование | Позиционное обозначение | Номера выводов |
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
| Интегральная микросхема: |
| Инфракрасный приёмник | IC_IRR | D? | VCC, OUT, GND |
| Стабилизатор отрицательного напряжения | IC_REGULATOR_NEG | D? | IN, GND, OUT|
| Стабилизатор отрицательного напряжения регулируемый | IC_REGULATOR_NEG_ADJ | D? | IN, ADJ, OUT|
| Стабиризатор положительного напряжения | IC_REGULATOR_POS | D? | IN, GND, OUT|
| Стабиризатор положительного напряжения регулируемый | IC_REGULATOR_POS_ADJ | D? | IN, ADJ, OUT|
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
| Нагревательный элемент | RESISTOR_HEATER | EK? | 1, 2 |
| Подстроечный | RESISTOR_PRESET | RP? | 1, 2, 3 |
| Терморезистор с отрицательным температурным коэффициентом (изображён горизонтально) | RESISTOR_THERMISTOR_NTC_H | RK? | 1, 2 |
| Терморезистор с отрицательным температурным коэффициентом (изображён вертикально) | RESISTOR_THERMISTOR_NTC_V | RK? | 1, 2 |
| Терморезистор с положительным температурным коэффициентом (изображён горизонтально) | RESISTOR_THERMISTOR_PTC_H | RK? | 1, 2 |
| Терморезистор с положительным температурным коэффициентом (изображён вертикально) | RESISTOR_THERMISTOR_PTC_V | RK? | 1, 2 |
| Регулируемый | RESISTOR_VARIABLE | RP? | 1, 2, 3 |
| Варистор (изображён горизонтально) | RESISTOR_VARISTOR_H | RU? | 1, 2 |
| Варистор (изображён вертикально) | RESISTOR_VARISTOR_V | RU? | 1, 2 |
| Переключатель: |
| Блок переключателей, 5 каналов | SWITCH_BLOCK_05 | SA?A…SA?E | 1…10 |
| Кнопка замыкающая, 1 полоса | SWITCH_BUTTON_NO_01 | SB? | 1COM, 1NO |
| SK-23D29-G | SWITCH_SPECIAL_SK-23D29-G | SA? | 1…8 |
| SK-42D01-G | SWITCH_SPECIAL_SK-42D01-G | SA? | 1…12 |

## Author

Igor Vladimirovich Ivanov

## License

This project is licensed under GNU General Public License v3.0 or later
