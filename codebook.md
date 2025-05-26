# Dataset description

This dataset contains village-level information for 7,723 villages across Taiwan, including geographic identifiers (county, town, village), income statistics, and electoral data. It records the vote shares of the four major political parties—DPP, KMT, TPP, and NPP—in the 2024 election, alongside the median and standard deviation of village income in 2021.

# Obs

7,723 Obs. of 9 variables.

# Variable descriptions

| Variable | Class in R | Description                                                                |
| -------- | ---------- | -------------------------------------------------------------------------- |
| county   | character  | The county (直轄市、縣或市) where the village is located.                  |
| town     | character  | The town (鄉、鎮、市或區) where the village is located.                    |
| vill     | character  | The village (村或里) name.                                                 |
| dpp      | numeric    | Vote share of the Democratic Progressive Party (DPP) in the 2024 election. |
| kmt      | numeric    | Vote share of the Kuomintang (KMT) in the 2024 election.                   |
| tpp      | numeric    | Vote share of the Taiwan People's Party (TPP) in the 2024 election.        |
| npp      | numeric    | Vote share of the New Power Party (NPP) in the 2024 election.              |
| median   | integer    | Median income in the village in 2021.                                      |
| sd       | numeric    | Standard deviation of income in the village in 2021.                       |