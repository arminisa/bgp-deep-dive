# Scenario Configurations

Each file in this folder is a **complete snapshot** of the BGP attributes 
configuration for a specific test scenario.

## 🎯 How to Use

1. Pick a scenario (e.g., `05-med.cfg`)
2. Copy the entire config to your router
3. Apply: `clear ip bgp * soft`
4. Verify with corresponding file in `verification/`

## 📋 Scenarios

| # | File | Description | Verification |
|---|---|---|---|
| 01 | `01-weight.cfg` | Weight (outbound) | `verification/06-weight.txt` |
| 02 | `02-localpref.cfg` | Local Preference | `verification/07-localpref.txt` |
| 03 | `03-weight-vs-localpref.cfg` | Attribute Priority | `verification/08-weight-vs-localpref.txt` |
| 04 | `04-selective.cfg` | Selective Advertisement | `verification/09-selective-advertisement.txt` |
| 05 | `05-med.cfg` | MED (inbound) | `verification/10-med.txt` |
| 06 | `06-best-path.cfg` | Best Path Selection | `verification/12-best-path.txt` (coming) |

## 💡 Notes

- These are **snapshots** of a working configuration.
- You can apply them in **any order**.
- Each scenario is **independent** of others.
- The live router is reset between scenarios, but these files remain.
