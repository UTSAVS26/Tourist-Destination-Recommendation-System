# 🌏 Tourism Dataset 🏝️

**📅 Published:** 29 August 2023  
**🔢 Version:** 1  
**🔗 DOI:** [10.17632/h58s544674.1](https://doi.org/10.17632/h58s544674.1)  
**👤 Contributor:** Choirul Huda Huda  

---

## 📖 Description
This dataset contains tourist visit transactions at three popular tourist locations in Indonesia, namely Bali, Malang, and Yogyakarta. The data captures the historical tourism experiences recorded on the TripAdvisor website, collected from October 2022 to January 2023. It is designed to support researchers, especially in tourism and soft computing, and is not intended for commercialization purposes.

---

## 📂 Files Overview

| 🗂️ File Name        | 📄 Format | 📏 Size  | 📜 Description |
|--------------------|-----------|----------|-------------|
| `City.xlsx`        | XLSX      | 234 KB   | Contains data about different cities visited by tourists. |
| `Continent.xlsx`   | XLSX      | 8.67 KB  | Contains data about continents relevant to tourist visits. |
| `Country.xlsx`     | XLSX      | 12.9 KB  | Contains data about countries visited by tourists. |
| `Item.xlsx`        | XLSX      | 10.6 KB  | Contains data about tourist attractions/items. |
| `Mode.xlsx`        | XLSX      | 8.66 KB  | Contains data about the modes of travel used by tourists. |
| `Region.xlsx`      | XLSX      | 9.26 KB  | Contains data about different regions visited by tourists. |
| `Transaction.xlsx` | XLSX      | 1.94 MB  | Contains transaction data of tourist visits. |
| `Type.xlsx`        | XLSX      | 9.15 KB  | Contains data about the types of tourism activities. |
| `User.xlsx`        | XLSX      | 1.02 MB  | Contains data about the users/tourists. |

---

## 📜 File Descriptions

### 🏙️ `City.xlsx`
Contains data about different cities visited by tourists.

| Attribute    | Description                        |
|--------------|------------------------------------|
| `CityId`     | Unique identifier for the city     |
| `CityName`   | Name of the city                   |
| `CountryId`  | Identifier for the country the city belongs to |

### 🌍 `Continent.xlsx`
Contains data about continents relevant to tourist visits.

| Attribute      | Description                          |
|----------------|--------------------------------------|
| `ContenentId`  | Unique identifier for the continent  |
| `Contenent`    | Name of the continent                |

### 🌐 `Country.xlsx`
Contains data about countries visited by tourists.

| Attribute    | Description                        |
|--------------|------------------------------------|
| `CountryId`  | Unique identifier for the country  |
| `Country`    | Name of the country                |
| `RegionId`   | Identifier for the region the country belongs to |

### 🏛️ `Item.xlsx`
Contains data about tourist attractions/items.

| Attribute           | Description                                |
|---------------------|--------------------------------------------|
| `AttractionId`      | Unique identifier for the attraction       |
| `AttractionCityId`  | Identifier for the city of the attraction  |
| `AttractionTypeId`  | Identifier for the type of the attraction  |
| `Attraction`        | Name of the attraction                     |
| `AttractionAddress` | Address of the attraction                  |

### 🚆 `Mode.xlsx`
Contains data about the modes of travel used by tourists.

| Attribute      | Description                        |
|----------------|------------------------------------|
| `VisitModeId`  | Unique identifier for the visit mode |
| `VisitMode`    | Description of the visit mode      |

### 🌏 `Region.xlsx`
Contains data about different regions visited by tourists.

| Attribute    | Description                        |
|--------------|------------------------------------|
| `RegionId`   | Unique identifier for the region   |
| `Region`     | Name of the region                 |
| `ContentId`  | Identifier for the continent the region belongs to |

### 💳 `Transaction.xlsx`
Contains transaction data of tourist visits.

| Attribute      | Description                                |
|----------------|--------------------------------------------|
| `TransactionId`| Unique identifier for the transaction      |
| `UserId`       | Identifier for the user                    |
| `VisitYear`    | Year of the visit                          |
| `VisitMonth`   | Month of the visit                         |
| `VisitMode`    | Mode of the visit                          |
| `AttractionId` | Identifier for the attraction visited      |
| `Rating`       | Rating given by the user for the attraction|

### 🎡 `Type.xlsx`
Contains data about the types of tourism activities.

| Attribute           | Description                            |
|---------------------|----------------------------------------|
| `AttractionTypeId`  | Unique identifier for the attraction type |
| `AttractionType`    | Description of the attraction type     |

### 👤 `User.xlsx`
Contains data about the users/tourists.

| Attribute    | Description                        |
|--------------|------------------------------------|
| `UserId`     | Unique identifier for the user     |
| `ContenentId`| Identifier for the continent the user is from |
| `RegionId`   | Identifier for the region the user is from    |
| `CountryId`  | Identifier for the country the user is from   |
| `CityId`     | Identifier for the city the user is from      |

---

## 🛠️ Steps to Reproduce

A series of activities were carried out to gather and structure the information available on the TripAdvisor website. These activities aimed to provide a comprehensive dataset for researchers. The main steps in developing the dataset include:

1. **Crawling:** Using the WebHarvy tool, tourism information from the TripAdvisor website was collected. The raw data was unstructured and contained mixed data subjects that required normalization.
2. **Pre-processing:** This step involved eliminating empty values, irrelevant values, and duplicates.
3. **Modelling:** The data was transformed into an Excel format for further analysis. The dataset consists of nine tables: User, Item, Transaction, Continent, Region, Country, City, Mode, and Type. Data values have been encoded to maintain confidentiality. Additional data validation and enhancement were conducted through manual searches on Google Maps regarding the locations.

---

## 🏫 Institutions

- Bina Nusantara University

---

## 📚 Categories

- Tourism
- Soft Computing

---

## 📜 License

This dataset is licensed under the Creative Commons Attribution 4.0 International (CC BY 4.0). [Learn more](https://creativecommons.org/licenses/by/4.0/).

---

## 🔖 Latest Version

- **Version:** 1
- **Published:** 29 Aug 2023
- **DOI:** [10.17632/h58s544674.1](https://doi.org/10.17632/h58s544674.1)

---

## ✒️ Citation

huda, choirul huda (2023), “Tourism Dataset”, Mendeley Data, V1, [doi: 10.17632/h58s544674.1](https://doi.org/10.17632/h58s544674.1)

---