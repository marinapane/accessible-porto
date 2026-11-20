# Accessible Porto

A meeting prototype for a community directory to help disabled people find support, services, and useful access information in Porto.

**All eight listings and the sample reviews are fictional.** The name is provisional. This example is for discussion and must not be used as a verified service directory.

## Project objectives

- Make everyday support and access information easier to find in one searchable place.
- Cover the priorities identified by disabled people, including transport, daily support, equipment, health, public services, and community activities.
- Describe specific access features instead of relying on a single “accessible” label. Distinguish Yes, No, and Unknown.
- Build a website people can use on phones and computers, with keyboard and assistive technology support. Target WCAG 2.2 Level AA and validate with disabled participants before launch.
- Plan Portuguese and English content, reviewed by speakers of each language.
- Let volunteers maintain approved information through a simple spreadsheet workflow.
- Make information trustworthy through clear sources, verification dates, moderation, and a way to report corrections.
- Keep private submissions and contributor contact details separate from public listings.

## Objectives for the meeting

1. Try the prototype and discuss whether the search and access filters are useful.
2. Agree the initial audience and geographical coverage: Porto city or Greater Porto.
3. Choose the first categories and access details to collect.
4. Identify project owners, volunteer editors, translators, and disabled participants to guide testing.
5. Agree how listings will be checked, approved, corrected, and kept current.
6. Plan a pilot with 20–30 real, carefully checked listings.

See `MEETING-GUIDE.txt` for a short demonstration walkthrough and questions for Luis.

## Open the example on a computer

1. Open the **Porto Help Page** folder. If you received it as a ZIP, extract it first. On Windows, right-click the ZIP and select **Extract All**.
2. Double-click `index.html`. If prompted, choose a modern web browser.

The website works offline. No installation, account, or spreadsheet connection is required. Keep the extracted folders together so the database download links continue to work.

## Share the example

- Compress the whole project folder into a ZIP, then attach it to an email or message or share it through a file-sharing service.
- Ask recipients to extract it and open `index.html` using the instructions above.
- Links to files on your computer do not give other people access. Send the actual ZIP file.
- Share the full folder so the page can load its logo from `assets` and the database downloads from `outputs`.
- This prototype has not been published online. A shared website address would require hosting.

## Use it on a cellphone

The layout adapts to small screens, with stacked controls, single-column listings, larger touch targets, and wrapping navigation.

Opening a downloaded HTML file depends on the phone and the app used to open it. Some file viewers do not run the page's interactive features. If a phone cannot open it in a browser, use a computer for this offline version. Hosting the site would provide a more convenient link for phone users.

The mobile styles have been implemented, but visual testing on an actual phone remains outstanding.

## Try the directory

1. Search for **taxi** and open the result's details.
2. Select **Clear filters**.
3. Select **Step-free access** and **Hearing support** together.
4. Try a category or area filter.
5. Clear the filters again and open **Central Porto Taxi** to see examples of all three values: Yes, No, and Unknown.

When you select multiple access features, a result must have Yes for every selected feature. No and Unknown do not qualify.

Use **Print meeting copy** near the bottom of the page to print or save a PDF. This resets the filters so the printed copy includes every sample listing.

## Open and edit the example database

Open `outputs/porto-demo/porto-example-database.xlsx` in Excel or another compatible spreadsheet application. You can also import the workbook into Google Sheets; review formatting and dropdowns after import.

| Tab | Contents |
| --- | --- |
| Listings | The same eight fictional listings shown on the website, with access values and fields for future contact details and translations. |
| Categories | Category IDs and English names, with space for Portuguese names. |
| Parishes | The seven official parishes available in the Area filter. |
| Reviews | Two fictional draft reviews demonstrating a possible future moderation structure. They are not displayed on the website. |
| Editing guide | Instructions for IDs, access values, sources, verification dates, and publication status. |

CSV copies of Listings, Categories, Parishes, and Reviews are in the same folder. CSV files contain one table each and do not preserve workbook formatting or dropdowns.

Keep listing and category IDs stable. Use **Unknown** when an access detail has not been confirmed. Blank contact details, translations, and verification dates in the examples are intentional.

**Editing the spreadsheet or CSV files does not update the website.** The current page uses embedded sample data. Connecting approved spreadsheet data to a website publishing process is a future implementation step.

## What works and what remains

Working features include offline keyword search, category and area filters, combined access filters, listing detail dialogs, database downloads, responsive styles, and printing. The page has no third-party asset or network dependencies and does not collect or send visitor data.

Before a public launch, the project still needs real listings, community validation, translations, a spreadsheet publishing connection, moderated submissions and corrections, hosting, and accessibility testing. The prototype has not undergone a full accessibility audit and is not a WCAG conformance certification.

## Files in the meeting kit

```text
README.md
index.html
MEETING-GUIDE.txt
assets/
  accessible-porto.jpeg
outputs/
  porto-demo/
    porto-example-database.xlsx
    listings.csv
    categories.csv
    parishes.csv
    reviews.csv
```
