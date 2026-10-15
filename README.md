# Merchant Category Codes (MCC)

A list of 983 merchant category codes (MCCs) with their descriptions, as JSON and CSV.

An MCC is the four-digit code a card network assigns to a merchant to describe its type of business, for example `5734` (Computer Software Stores) or `7311` (Advertising Services). Card issuers use MCCs to decide which purchases a card may make, so an MCC is often the reason a card works in most shops but is declined in one.

## Files

- `mcc.json`: an object of `"code": "description"` pairs
- `mcc.csv`: two columns, `mcc` and `description`, sorted by code

## Look up a code

To search these codes in the browser, use the free [MCC lookup tool](https://zikcards.com/tools/mcc-lookup) by ZikCards.

## Notes

Descriptions follow the commonly published Visa and Mastercard merchant category lists. Networks and acquirers sometimes use their own wording, so treat the descriptions as a guide.

Visa and Mastercard are trademarks of their respective owners.

## License

MIT. Use it however you like.
