# QueryStringEncrypter
Encryption of query strings using the Base64String 
#### By Carmel Schvartzman
#####The present MVC C# code is the companion for the following Tutorial: http://themvcclub.blogspot.com/2015/04/how-to-do-query-strings-encryption-in-5-minutes.html


This is a simple query strings' obfuscator, not a sophisticated security tool.
The present utility transforms a query string like the following:
"$ilikebender@gmail.com$MySubject$20150321"

into an obfuscated query string like this:
"mlzcmFlbEBnbWFpbC5jb20kTXlTdWJqZWN0JDIwMTUvMDMvMjE%3D"

The encrypted string will later be Url encoded, since it is meant to output to an URI address.


http://themvcclub.blogspot.co.il/
