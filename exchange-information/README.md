# Exchange Information View Formatting

SharePoint Online view formatting sample for displaying the current exchange rate and MRV fee in a compact information card.

## Preview

![Exchange Information preview](./assets/exchange-information-preview.png)

## SharePoint fields

This formatting expects the following internal field names:

| Field | Purpose |
|---|---|
| `Title` | Current exchange rate |
| `MRVFee` | Current MRV fee |

## Installation

1. Open the SharePoint list.
2. Select **View options**.
3. Select **Format current view**.
4. Open **Advanced mode**.
5. Copy the contents of `exchange-information-view.json`.
6. Paste the JSON into the formatting editor.
7. Select **Save**.

## Notes

- Confirm that `MRVFee` is the internal name of the SharePoint column.
- The view hides the standard column headers and selection controls.
- The layout uses the Cashiering Services navy and champagne design palette.
