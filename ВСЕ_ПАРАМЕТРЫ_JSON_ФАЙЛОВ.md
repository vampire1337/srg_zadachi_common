# 📋 ВСЕ ПАРАМЕТРЫ ИЗ JSON ФАЙЛОВ

**Дата экспорта данных:** 26.06.2025  
**Отображение:** Все параметры в соответствии с JSON структурой  

---

## 🏢 АО "АЛЬФАСТРАХОВАНИЕ"

### 📄 ЖИЗНЬ (BORROWER_INSURANCE)
**Файл:** `Tarifnoye rukovodstvo MKB_AO -Al_faStrakhovaniye-_life.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:47:12
- **active:** true
- **title:** Тарифное руководство МКБ
- **insuranceType:** BORROWER_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** alfastrah_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30

**Документы:**
- $document: Паспорт заемщика/созаемщика

**Возрастные параметры:**
- **insurerAgeFrom:** 18
- **insurerAgeTo:** 65
- **endAge:** 70
- **firstYearAgeCorrection:** 1
- **otherYearAgeCorrection:** 1
- **ageResolutionMode:** DATE_DIFF

**Тарифы по возрастам:**
```
Возраст | Мужчины % | Женщины %
18      | 0.25000   | 0.20000
19      | 0.25000   | 0.20000
20      | 0.25000   | 0.20000
21      | 0.26300   | 0.20400
22      | 0.27100   | 0.20400
23      | 0.27100   | 0.20400
24      | 0.29700   | 0.21200
25      | 0.29700   | 0.21200
26      | 0.29700   | 0.21200
27      | 0.30500   | 0.22900
28      | 0.30500   | 0.23700
29      | 0.32300   | 0.23700
30      | 0.34700   | 0.23700
31      | 0.36500   | 0.24600
32      | 0.38100   | 0.26300
33      | 0.39100   | 0.27100
34      | 0.42500   | 0.27100
35      | 0.44100   | 0.29700
36      | 0.48300   | 0.32300
37      | 0.50900   | 0.34700
38      | 0.53500   | 0.35700
39      | 0.56800   | 0.38100
40      | 0.59400   | 0.39100
41      | 0.62800   | 0.41500
42      | 0.66200   | 0.44100
43      | 0.70400   | 0.46700
44      | 0.73800   | 0.50100
45      | 0.77200   | 0.52600
46      | 0.85600   | 0.56000
47      | 0.92400   | 0.60200
48      | 1.00900   | 0.64500
49      | 1.09400   | 0.68700
50      | 1.19600   | 0.73800
51      | 1.30700   | 0.79800
52      | 1.41700   | 0.85600
53      | 1.54400   | 0.91600
54      | 1.68800   | 1.00100
55      | 1.83200   | 1.07700
...до 65 лет
```

### 🏠 ИМУЩЕСТВО (PROPERTY_INSURANCE)
**Файл:** `Tarifnoye rukovodstvo MKB_AO -Al_faStrakhovaniye-_realty.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:47:22
- **active:** true
- **title:** Тарифное руководство МКБ
- **insuranceType:** PROPERTY_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** alfastrah_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30

**Документы:**
- $document: Паспорт заемщика/созаемщика

**Тарифы:**
- **tariffPerc:** 0.15400
- **tariffPercSpecial:** null

**Региональные лимиты:**
1. **regionLimit:** 20000000.00000 (общий)
2. **regionLimit:** 0.00000 (исключенные регионы)
   - ФИАС коды: de67dc49-b9ba-48a3-a4cc-c2ebfeca6c5e, b2d8cd20-cabc-4deb-afad-f3c4b4d55821, bd8e6511-e4b9-4841-90de-6bbc231a789e, 0bb7fa19-736d-49cf-ad0e-9774c4dae09b, 61b95807-388a-4cb1-9bee-889f7cf811c8, 7bac30d2-0e95-499e-a34a-7351a8f13833, de459e9c-2933-4923-83d1-9c64cfd7a817, 486c7c54-caa1-4b04-8dd3-c182313337fc, 10530e14-2627-4e68-aae4-c57373defcf4, d28a09a6-ad4e-407a-ad64-c208549befc4

**Типы недвижимости:**
- FLAT
- HOUSE
- PARKING

### 📜 ТИТУЛ (TITLE_INSURANCE)
**Файл:** `Tarifnoye rukovodstvo MKB_AO -Al_faStrakhovaniye-_title.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:47:34
- **active:** true
- **title:** Тарифное руководство МКБ
- **insuranceType:** TITLE_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** alfastrah_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30
- **periodType:** YEAR

**Документы:**
- $document: Отчет об оценке рыночной стоимости недвижимого имущества
- $document: ЕГРН / ЕГРП на дату регистрации права
- $document: Выписка из домовой книги
- $document: Документы-основания приобретения права собственности
- $document: Паспорт заемщика/созаемщика
- $document: Паспорт продавца

**Тарифы:**
- **tariffPerc:** 0.20000
- **tariffPercSpecial:** null

**Региональные лимиты:**
1. **regionLimit:** 7000000.00000 (общий)
2. **regionLimit:** 0.00000 (исключенные регионы)
   - ФИАС коды: de67dc49-b9ba-48a3-a4cc-c2ebfeca6c5e, b2d8cd20-cabc-4deb-afad-f3c4b4d55821, bd8e6511-e4b9-4841-90de-6bbc231a789e, 0bb7fa19-736d-49cf-ad0e-9774c4dae09b, 61b95807-388a-4cb1-9bee-889f7cf811c8, 7bac30d2-0e95-499e-a34a-7351a8f13833, de459e9c-2933-4923-83d1-9c64cfd7a817, 486c7c54-caa1-4b04-8dd3-c182313337fc, 10530e14-2627-4e68-aae4-c57373defcf4, d28a09a6-ad4e-407a-ad64-c208549befc4

**Типы недвижимости:**
- FLAT
- HOUSE
- PARKING

---

## 🏢 ООО "АБСОЛЮТ СТРАХОВАНИЕ"

### 🏠 ИМУЩЕСТВО (PROPERTY_INSURANCE)
**Файл:** `MKB - IMUSHCHESTVO_OOO -Absolyut Strakhovaniye-_realty.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:41:54
- **active:** true
- **title:** МКБ - ИМУЩЕСТВО
- **insuranceType:** PROPERTY_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** absolut_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30
- **insAmountThresholdPerc:** 0.00000

**Документы:**
- $document: Паспорт заемщика/созаемщика

**Тарифы:**
- **tariffPerc:** 0.15400
- **tariffPercSpecial:** null

**Региональные лимиты:**
1. **regionLimit:** 15000000.00000 (стандартный)
2. **regionLimit:** 20000000.00000 (премиум регионы)
   - ФИАС коды: 0c5b2444-70a0-4932-980c-b4dc0d3f02b5, 29251dcf-00a1-4e34-98d4-5c47484a36d4
3. **regionLimit:** 0.00000 (исключенные регионы)
   - ФИАС коды: de67dc49-b9ba-48a3-a4cc-c2ebfeca6c5e, 1781f74e-be4a-4697-9c6b-493057c94818, bd8e6511-e4b9-4841-90de-6bbc231a789e, 0bb7fa19-736d-49cf-ad0e-9774c4dae09b, 486c7c54-caa1-4b04-8dd3-c182313337fc, 10530e14-2627-4e68-aae4-c57373defcf4, 6fdecb78-893a-4e3f-a5ba-aa062459463b, d28a09a6-ad4e-407a-ad64-c208549befc4, b2d8cd20-cabc-4deb-afad-f3c4b4d55821, f5807226-8be0-4ea8-91fc-39d053aec1e2, 61b95807-388a-4cb1-9bee-889f7cf811c8, 7bac30d2-0e95-499e-a34a-7351a8f13833, ee594d5e-30a9-40dc-b9f2-0add1be44ba1, de459e9c-2933-4923-83d1-9c64cfd7a817, 639efe9d-3fc8-4438-8e70-ec4f2321f2a7

**Типы недвижимости:**
- FLAT
- HOUSE
- PARKING

### 📜 ТИТУЛ (TITLE_INSURANCE)
**Файл:** `MKB - TITUL_OOO -Absolyut Strakhovaniye-_title.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:42:03
- **active:** true
- **title:** МКБ - ТИТУЛ
- **insuranceType:** TITLE_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** absolut_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30
- **insAmountThresholdPerc:** 0.00000
- **periodType:** YEAR

**Документы:**
- $document: Отчет об оценке рыночной стоимости недвижимого имущества
- $document: ЕГРН / ЕГРП на дату регистрации права
- $document: Выписка из домовой книги
- $document: Документы-основания приобретения права собственности
- $document: Паспорт заемщика/созаемщика
- $document: Паспорт продавца

**Тарифы:**
- **tariffPerc:** 0.20000
- **tariffPercSpecial:** null

**Региональные лимиты:**
1. **regionLimit:** 2500000.00000 (стандартный)
2. **regionLimit:** 2500000.00000 (премиум регионы)
   - ФИАС коды: 0c5b2444-70a0-4932-980c-b4dc0d3f02b5, 29251dcf-00a1-4e34-98d4-5c47484a36d4

**Типы недвижимости:**
- FLAT
- HOUSE
- PARKING

---

## 🏢 ГСК "ЮГОРИЯ"

### 🏠 ИМУЩЕСТВО (PROPERTY_INSURANCE)
**Файл:** `Gotovoye zhil_ye_GSK -Yugoriya-_realty.json`

**Основные параметры:**
- **exportedAt:** 2025-06-26 15:43:33
- **active:** true
- **title:** Готовое жилье
- **insuranceType:** PROPERTY_INSURANCE
- **profileOwnerCode:** mkb
- **insuranceCompanyCode:** ugsk_sk
- **includedFeePerc:** 0.00000
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30
- **insAmountThresholdPerc:** 0.00000

**Документы:**
- $document: Паспорт заемщика/созаемщика

**Тарифы:**
- **tariffPerc:** 0.15400
- **tariffPercSpecial:** null

**Региональные лимиты:**
- **regionLimit:** 30000000.00000 (общий)

**Типы недвижимости:**
- FLAT

---

## 📊 СТРУКТУРА ОБЩИХ ПАРАМЕТРОВ

### 🔧 Технические параметры (общие для всех):
- **phoneLimitEnabled:** false
- **policiesPerPhoneLimit:** 2
- **phoneLimitPolicyMinDays:** 30
- **includedFeePerc:** 0.00000
- **active:** true
- **profileOwnerCode:** mkb

### 📋 Коды страховых компаний:
- **alfastrah_sk** - АО "АльфаСтрахование"
- **absolut_sk** - ООО "Абсолют Страхование"
- **ugsk_sk** - ГСК "Югория"

### 🎯 Типы страхования:
- **BORROWER_INSURANCE** - Страхование жизни заемщика
- **PROPERTY_INSURANCE** - Страхование имущества
- **TITLE_INSURANCE** - Страхование титула

### 🏘️ Типы недвижимости:
- **FLAT** - Квартиры
- **HOUSE** - Дома
- **PARKING** - Парковочные места

### 📅 Период страхования:
- **YEAR** - Годовой период (для титула)

### 📄 Документы ($document):
**Для жизни:**
- Паспорт заемщика/созаемщика

**Для имущества:**
- Паспорт заемщика/созаемщика

**Для титула:**
- Отчет об оценке рыночной стоимости недвижимого имущества
- ЕГРН / ЕГРП на дату регистрации права
- Выписка из домовой книги
- Документы-основания приобретения права собственности
- Паспорт заемщика/созаемщика
- Паспорт продавца

---

**Отчёт создан:** 16.01.2025  
**Источник:** Прямое отображение JSON данных без интерпретации 