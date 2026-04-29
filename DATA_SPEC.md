# R3BBIT Data Specification
The app uses a strict CSV-style string format for all logging and synchronization.

## Log Format
Each line in a log must follow this structure:
`MMM dd HH:mm,TYPE,DATA`

### Example Entries:
*   `Oct 24 14:30,Feed,120 ml` (120ml feeding logged)
*   `Oct 24 15:00,Sleep,` (Start of sleep)
*   `Oct 24 15:45,Wake,45m` (Woke up after 45 minutes)
*   `Oct 24 16:00,Diaper,Both` (Pee and Poo logged)

## Sync Logic
When using the "Paste from Clipboard" or "Import CSV" features, the app:
1. Validates the date format.
2. Checks for duplicates using a line-by-line hash comparison.
3. Sorts all entries chronologically after merging.
