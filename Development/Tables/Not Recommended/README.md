These approaches are Not Recommended!

I don’t know when or why Apple started to create tables like these, fill them with all kinds of different data cells. But indeed they started a bad trend, and most probably a lot of apps and blogs did the same and followed along.

- Using tables to show different data cells is going to make your code complex.
- You are using many different custom cells and mixing them in the same view.
- Not easy and nice scaling and future proof.
- You have to take care of cell identifiers.
- You have to take care of cell rows, heights, sections, headers, footers etc.
- Just take a look at your table code, its delegate and data source – do you really like what you see?

+ Instead, try to use a view or a scroll view – and you won’t have to deal with tables, delegates and data sources.
+ Just put out the labels, buttons, text fields and switches… BOOM! You are good to go!
+ Or, try using paginated views which create a nice user experience – for instance when a user has to register or something similar where you can keep things simple & clean page by page.

