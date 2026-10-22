# GameTide dataset

Created by **Ritesh Naik** as a nonprofit learning project.

## Download the data

- [Download GameTide v1.0 from GitHub Releases](https://github.com/GameTideData/SaaS-Data/releases/tag/v1.0). Open **Assets** to find 120 monthly zip files, the combined SQLite database zip, the verification zip, and the license.
- [Browse and download individual tables on Hugging Face](https://huggingface.co/datasets/GameTideData/SaaS-Data), including CSV and Parquet formats.

The dataset download files are attached to the GitHub release. The repository's main file list contains this overview.


GameTide is a **fictional** US sports performance and operations software company. This dataset is its integrated
company data from its founding, 2020-01-01 to 2029-12-31: CRM, accounting, payments, HR and payroll, marketing, web analytics,
ads, commissions, sales tax, support, product usage, customer success, bank and treasury, planning, equity,
recruiting, implementation projects, engineering time, cloud costs, hardware inventory, and software and AI spend, all
linked to the same customers, people, products and departments, and all tying to the general ledger. Each system
starts in the month GameTide adopted it; the books are in QuickBooks Online until December 2022 (`accounting_qbo`) and
in Sage Intacct from January 2023 (`accounting`), joined by a conversion journal and the warehouse crosswalks.

GameTide is not affiliated with any real company with a similar name. Real software vendor names appear only as
suppliers and as the layout each system file follows; prices and terms are illustrative and no vendor is endorsed or
blamed. No real customer, school, team, conference or person appears in the data.

## Layouts

- **By month** (GitHub release assets): one zip per month-end folder (all 120 released together), plus one SQLite file holding
  every month (table names equal file names without the date).
- **By table** (Hugging Face `by_table/`): each table in its own folder with every month's CSV and one Parquet file of all months.

## Verification package

`verification/` holds everything the engine used and everything needed to check results: the assumptions (and the
settings file the engine reads), policies, story bible, company profile, data dictionary, data map, metric definitions, the
answer key, every planted event, every month in review and the full acceptance test report (11,867 checks,
0 failed).

## License

Data published under Creative Commons Attribution 4.0 International (CC BY 4.0). The full license text is in
`LICENSE.txt` (from https://creativecommons.org/licenses/by/4.0/legalcode.txt). Credit: GameTide (gametidedata.org).
