# web scrapers
 a collection of web scrapers using various tools and methods

##Scrapers made for https://books.toscrape.com/index.html

The aim is to scrape all book titles, prices and availability into an excel workbook, with different sheets for each category.

![Screenshot (217)](https://github.com/dedederinsola/web-scrapers/assets/12772185/7487247f-0d09-4499-bed9-3ca4537fa71a)
The result looks like so

 1. booksimplegui.py: Uses openpyxl to write to the workbook and PySimpleGUI to allow user to select directory to save it in, using Save As dialog box.
 2. booktkinter.py: Uses openpyxl to write to the workbook and Tkinter to allow user to select directory to save it in, using Save As dialog box.
 3. bookuserpath.py: Uses openpyxl to write to the workbook and prompts the user to enter the path manually.
