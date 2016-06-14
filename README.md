# scrapethemaps
Scrape google maps's coordinate settings through using a .csv file. 

You'll need the .csv file "hello.csv" in order to get the code as is to work, plus that file has to be located on your desktop.
You can change the code to put your own list of addresses in, but you'll have to tinker the line that says 
"data<-read.csv(file = "desktop/hello.csv")"
in the part that says "desktop/hello.csv" in order to get it to work.
Plus, you can only scrape 250 addresses a day like this, so using a file that has more addresses than that is probably not going to work.
