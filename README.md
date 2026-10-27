# govradar-data

Filtered mirror of Thai government procurement open data (ภาษีไปไหน / e-GP, กรมบัญชีกลาง + DGA), license CC-BY.
Only projects with budget >= 500,000 THB. Used to seed the GovRadar database.

- `data/contract-<FY>-*.csv.gz` — contracted projects + winner/contract (FY2565–2569), one row per contract
- `data/submit-2569-*.csv.gz` — all bidders per project item (FY2569 only; DGA has no earlier bidder data)
- `data/dept-001.csv.gz`, `data/subdept-001.csv.gz` — procuring agency master lists

Source: https://govspending.data.go.th/bulk/download
