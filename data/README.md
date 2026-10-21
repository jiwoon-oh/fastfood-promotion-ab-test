# Data

The analysis uses one file, `WA_Marketing-Campaign.csv`. It is git-ignored, so download it and place it here.

| Item | Value |
|---|---|
| Source | Kaggle dataset page: [Fast Food Marketing Campaign A/B Test](https://www.kaggle.com/datasets/chebotinaa/fast-food-marketing-campaign-ab-test) |
| File | `WA_Marketing-Campaign.csv` |
| Size | 548 rows, 7 columns |
| Location | `data/WA_Marketing-Campaign.csv` (the notebooks read `DATA_DIR / "WA_Marketing-Campaign.csv"`, where `DATA_DIR` comes from `config.py`) |

Columns: `MarketID`, `MarketSize` (Small, Medium, Large), `LocationID`, `AgeOfStore`, `Promotion` (1, 2, 3), `week` (1–4), `SalesInThousands`.

The dataset has 137 stores observed for four weeks each. `SalesInThousands` is the weekly sales of the new menu item, not total store sales. The dataset's scenario text matches IBM's description of the SPSS sample file `testmarket.sav`, which IBM labels hypothetical; I could not confirm that the two files are identical, so the data are treated as hypothetical sample data. Please check the dataset page for its license and terms before reuse.
