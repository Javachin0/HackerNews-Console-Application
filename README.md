# HackerNews Console Application
 WebScraper for pulling data out of HackerNews

Compiled with win64 runtimes included, to allow running in self containted mode.

Only external library included is Newtonsoft Json; Included it because it makes serializing object collections a piece of cake.

How to use:

<<<<<<< HEAD
    1) Open a cli and navigate to the HackerNews.exe (from the application root) HackerNews-Console-Application/bin/Release/netcoreapp3.1/win10-x64/publish
=======
    1) Open a cli and navigate to the HackerNews.exe (from the application root) HackerNews-Console-Application/bin/Release/netcoreapp3.1/win10-x64
>>>>>>> 1184ff60d99344f5681a35738834010b19639d5e
    
    2) Execute by entering HackerNews.exe followed by args if desired (default will return 1 page). Use ./HackerNews.exe if using the bash shell. 
    
    3) --help argument is there for displaying available args/options 

notes:
    - If some posts are missing from the response, this is because they're job vacancies/adverts - so delibertatly didnt match them in the Regular Expression.
