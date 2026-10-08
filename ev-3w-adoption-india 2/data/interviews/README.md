# Driver interviews (primary research)

Real interview data is **not** stored in this repository.

`interviews_synthetic_demo.csv` is a **randomly generated** dataset (20 fictional drivers, same columns as the template). It exists only so the notebook runs end to end. It contains no real people and **must not be cited as research findings**. The notebook labels every output built from it as *SYNTHETIC DEMO DATA* and switches to your real file automatically once `interviews_anonymized.csv` exists.

## Column guide

| Column | Meaning |
|---|---|
| `driver_id` | Anonymous ID (D01, D02, …), never a name or phone number |
| `city`, `vehicle_type` | Interview location; e.g. passenger auto, e-rickshaw, cargo |
| `ownership` | `owner` or `renter` |
| `daily_km`, `income_band` | Usage and a coarse income bracket |
| `currently_ev` | Whether the driver already drives an EV |
| `barrier_*` | Barrier raised in the interview (1/0) |
| `notes` | Short, non-identifying note |

## Privacy

Remove names, phone numbers, vehicle registration numbers and exact locations before committing anything. Obtain consent for any data you publish.
