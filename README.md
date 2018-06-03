# procurement-analysis-sample

This is a Doku for opportunity analysis sample with Power BI.

Source: 
https://docs.microsoft.com/en-us/power-bi/sample-procurement from http://obvience.com/

The dataset: [Click here](https://drive.google.com/file/d/1s15qKFObhzhwWJ6yW6hLmwCbiEUjdEfF/view?usp=sharing)

Before going further, we need understand the concept of the data model, please read the link below:
https://en.wikipedia.org/wiki/Data_model

This analysis contains 8 entity (table) and every table has attribute.

1. currency
* Attribute: Currency,	Symbol,	Currency Abbr,	CurrencyID

2. exchange rate
* Attribute: DateID, CurrencyID,	Exchange Rate,	DateCurrencyID

3. item 
* Attribute: ItemID,	Category,	Sub Category,	Commodity,	Item,	Commodity Detail

4. location
* Attribute: LocationID,	Location, Region,	Country/Region,	Location Number,	City

5. vendor
* Attribute: VendorID,	Vendor City,	Vendor State,	Vendor Postal Code,	Vendor Country/Region,	Total Spend,	Tier,	Vendor Name

6. date
* Attribute: DateID,	Day,	DayOfWeekNo,	DayOfWeek,	DayOfYear,	WeekNo,	MonthNo,	Month,	QtrNo,	Quarter,	Year,	Mon

7. invoice
* Attribute: InvoiceID,	InvoiceDateID,	VendorID,	LocationID,	Discount Days,	Discount Percent,	Payment Terms Days

8. invoice line item fact
* Attribute: InvoiceDateID,	InvoiceID,	ItemID,	CurrencyID,	Line Item,	Line Item Quantity,	Unit Price LOC,	Invoice LOC Amount,	DateCurrencyID,	ExchangeRate,	Invoice Amount,	Savings


### Let's make the data model from the 8 entity. Just drag every [Primary Key](https://en.wikipedia.org/wiki/Primary_key) of the entity in power pivot or power bi data model

![procurement-data-model](https://user-images.githubusercontent.com/27078712/40888335-1165af78-6756-11e8-878e-11a9ad2e0e31.PNG)



### After that, create [a measure in power bi or power pivot](https://docs.microsoft.com/en-us/power-bi/desktop-tutorial-create-measures)

Below are the measure of every graph,

Note! we use the format of table and attribut with [DAX language](https://docs.microsoft.com/en-us/power-bi/desktop-quickstart-learn-dax-basics) 

Extras: [Quick Guide DAX](https://support.office.com/en-us/article/quickstart-learn-dax-basics-in-30-minutes-51744643-c2a5-436a-bdf6-c895762bec1a?omkt=en-US&ui=en-US&rs=en-US&ad=US)

---------------------------------------------------------------------------
Drag this entity for every graph: 
.
.
.coming soon!











