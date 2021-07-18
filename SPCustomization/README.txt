jQeury 

jQuery gives us a variable called $ or jQuery 

hmtl get element by ID 
document.getElementById('id1') returns an html with id of id1

The same thing can be achieved by jQuery as below 

$('#id1')

REST API - Respresentational State Transfer 

SharePoint 2013+  REST API support 

My SP Site Collection URL (siteUrl)
https://tgarijune2021.sharepoint.com/sites/demo1

SP REST API for the above SP Site is 
siteUrl/_api/site - Gives information about the Site collection 
Example: https://tgarijune2021.sharepoint.com/sites/demo1/_api/site 


Root web or just web information 
url/_api/web

All SharePoint list 

url/_api/web/lists

Filtering specific type of lists (oData $filter)

url/_api/web/lists?$filter=property operator value  

.../_api/web/lists?$filter=Hidden eq false

If we need few properties like Title, Description, ItemCount, Hidden properties (we use oData $select)

.../_api/web/lists?$select=Title,Description,ItemCount,Hidden

Combination of the filtering and Select oData 

..../_api/web/lists?$filter=Hidden eq false&$select=Title,Description,ItemCount,Hidden

Get Specific List by its title 
.../_api/web/lists/getbytitle('listTitle')

Example .../_api/web/lists/getbytitle('Products')?$select=Title,ItemCount,Hidden,Description

Get all the list columns (fields)

../_api/web/lists/getbytitle('Customers')/fields

get all the items 

../_api/web/lists/getbytitle('Customers')/items

../_api/web/lists/getbytitle('Customers')/items(7)?$select=Title,Id,last_name,gender,email,Phone

different SP REST API oDATA 

$fiter
$select
$top
$expand 
$orderby
$skip


created on Dates between 7/1/2021-7/18/2021 
2021-07-1T00:00:00Z - 2021-07-18T00:00:00Z

d>=startDate and d<=endDate

d>=2021-07-1T00:00:00Z and d<=2021-07-18T00:00:00Z


/_api/web/lists/getbytitle('infolist')/items?$filter=StartDate ge datetime'2021-07-1T00:00:00Z' and StartDate le datetime'2021-07-18T00:00:00Z'


number betwen 5 and 10 

n>=5 and n<=10

Example:
/_api/web/lists/getbytitle('infolist')/items?$filter=StartDate le datetime'2016-03-26T09:59:32Z'

2021-07-18T00:00:00Z
