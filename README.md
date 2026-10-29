# SOC Wiki Entry Builder

A single HTML page that generates MediaWiki markup for:

- **Daily report** entries
- **FalsePositives** table rows (including the exclusion line for the IDSAlertCluster triage filter)
- **Assets** table rows

## Usage

1. Download or clone the repository.
2. Open `index.html` in a browser (double-click it). No server, installation or internet connection is needed.
3. Fill in the fields, click **Copy**, and paste the markup into the wiki.

Nothing is saved or sent anywhere. Everything you type stays in the open page and is gone when you close it.

## Notes

- Dates in table rows are written as DD.MM.YYYY.
- The **Defang** option replaces dots in IP addresses and domains with `[.]` in the daily report.
- For FalsePositives entries from the IDSAlertCluster dashboard, tick the box to build the exclusion line. Entries from other dashboards get `-` in the Exclusion column.
- Report links are built from the report date as `[[Dailyreports#29th_of_October]]`-style anchors.
