The .NET server stack has been fully updated and tested. The gpstracker.bak file is in the sqlserver directory and was created with sql server 2012 express. The sa password is gpstracker.

Please note that this is an asp.net website, not a web application. Its means you need to put source files directly onto an asp.net web server like IIS and it will be compiled on the fly. To open this project in visual studio for web (2012), you need to go to the file menu and open website, then select you iis web server and open the gpstracker website that you created there. Visual Studio express needs to be opened as an Administrator so that you can open the website.

Please note that this is a breaking change since xml has been updated to json.
