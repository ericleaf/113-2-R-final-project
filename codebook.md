## Dataset description

This dataset contains village-level information for 7,723 villages across Taiwan, including geographic identifiers (county, town, village), income statistics, and electoral data. It records the vote shares of the four major political parties—DPP, KMT, TPP, and NPP—in the 2024 election, alongside the median and standard deviation of village income in 2021.

## Obs

7,723 Obs. of 9 variables.

## Variable descriptions

| Variable | Class in R | Description                                                                |
| -------- | ---------- | -------------------------------------------------------------------------- |
| county   | character  | The county (直轄市、縣或市) where the village is located.                  |
| town     | character  | The town (鄉、鎮、市或區) where the village is located.                    |
| vill     | character  | The village (村或里) name.                                                 |
| dpp      | numeric    | Vote share of the Democratic Progressive Party (DPP) in the 2024 election. |
| kmt      | numeric    | Vote share of the Kuomintang (KMT) in the 2024 election.                   |
| tpp      | numeric    | Vote share of the Taiwan People's Party (TPP) in the 2024 election.        |
| npp      | numeric    | Vote share of the New Power Party (NPP) in the 2024 election.              |
| median   | integer    | Median of income in the village in 2021 (Unit: NT$1000).                   |
| sd       | numeric    | Standard deviation of income in the village in 2021 (Unit: NT$1000).       |

## Single variable summaries

```json
{
  "description": "Summary of each variable in the 'prec_income' data frame based on its class and contents.",
  "summary": {
    "county": {
      "class": "character",
      "description": "The county (直轄市、縣或市) where the village is located.",
      "sample_values": ["臺北市", "新北市", "基隆市", "桃園市", "新竹市"],
      "n_unique": 22,
      "n_missing": 0
    },
    "town": {
      "class": "character",
      "description": "The town (鄉、鎮、市或區) where the village is located.",
      "sample_values": ["北投區", "士林區", "大同區", "中山區", "松山區"],
      "n_unique": 354,
      "n_missing": 0
    },
    "vill": {
      "class": "character",
      "description": "The village (村或里) name.",
      "sample_values": ["建民里", "文林里", "石牌里", "福興里", "榮光里"],
      "n_unique": 5096,
      "n_missing": 0
    },
    "dpp": {
      "class": "numeric",
      "description": "Vote share of the Democratic Progressive Party (DPP) in the 2024 election.",
      "mean": 0.3752,
      "sd": 0.1071,
      "min": 0,
      "max": 0.7311,
      "n_missing": 0
    },
    "kmt": {
      "class": "numeric",
      "description": "Vote share of the Kuomintang (KMT) in the 2024 election.",
      "mean": 0.3534,
      "sd": 0.102,
      "min": 0.0658,
      "max": 0.8889,
      "n_missing": 0
    },
    "tpp": {
      "class": "numeric",
      "description": "Vote share of the Taiwan People's Party (TPP) in the 2024 election.",
      "mean": 0.2013,
      "sd": 0.0455,
      "min": 0.0164,
      "max": 0.4419,
      "n_missing": 0
    },
    "npp": {
      "class": "numeric",
      "description": "Vote share of the New Power Party (NPP) in the 2024 election.",
      "mean": 0.0227,
      "sd": 0.0098,
      "min": 0,
      "max": 0.288,
      "n_missing": 0
    },
    "median": {
      "class": "integer",
      "description": "Median of income in the village in 2021 (Unit: NT$1000).",
      "mean": 442.1897,
      "sd": 106.2304,
      "min": 203,
      "max": 2923,
      "n_missing": 0
    },
    "sd": {
      "class": "numeric",
      "description": "Standard deviation of income in the village in 2021 (Unit: NT$1000).",
      "mean": 882.6757,
      "sd": 775.9117,
      "min": 253.36,
      "max": 23689.75,
      "n_missing": 0
    }
  }
}
```

## Data summary

This study utilizes a village-level dataset, **vote_income**, which combines electoral results from the 2024 presidential election in Taiwan with socioeconomic indicators of income for each village. The dataset encompasses a total of 5,096 unique villages, nested within 354 towns and 22 counties across the country. Sample county names include Taipei City (臺北市), New Taipei City (新北市), and Hsinchu City (新竹市), while representative town names include Beitou District (北投區), Shilin District (士林區), and Zhongshan District (中山區).

The electoral component of the dataset contains vote share variables for the four major political parties. On average, the Democratic Progressive Party (DPP) secured 37.52% of the vote across villages (SD = 10.71%, min = 0%, max = 73.11%). The Kuomintang (KMT) recorded a similar mean vote share of 35.34% (SD = 10.20%, min = 6.58%, max = 88.89%). The Taiwan People's Party (TPP) received an average of 20.13% of votes (SD = 4.55%, min = 1.64%, max = 44.19%), while the New Power Party (NPP) had a much smaller average vote share of 2.27% (SD = 0.98%, min = 0%, max = 28.80%).

In terms of economic indicators, the median income in 2021 at the village level was NT$442,189, with a standard deviation of NT$106,230. The distribution spans from a minimum of NT$203,000 to a maximum of NT$2,923,000, reflecting considerable variation in local income levels. Additionally, the within-village standard deviation of income averaged NT$882,676, but ranged widely from NT$253,360 to NT$23,689,750, indicating substantial heterogeneity in income dispersion across villages.

No missing values were observed for any variable in the dataset, ensuring a complete basis for subsequent empirical analysis. This rich and comprehensive dataset enables a detailed examination of how socioeconomic characteristics relate to political preferences at a granular spatial scale.
