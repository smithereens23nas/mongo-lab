# mongo-lab

See the notion (https://www.notion.so/Mongo-Lab-4b92157ab9254162af08ead76d068735) for instructions on how to complete this lab. Remember to fork over this repo, make your changes to your version, then push up the changes and finally submit it with a pull request.

db.employees.insert
-insert many documents into your employees collection

db.employees.find
-To find all the documents in our collection with certain criteria

There are several comparisons we can perform

- $lt (less than)
- $lte (less than or equal to)
- $gt (greater than)
- $gte (greater than or equal to)
- $ne (not equal to)
- $exists (does the property exist on an object -- either true or false)
- $in (does the value exist within the given array)

db.employees.update
-update certain values in our DB
    -increase or decrease
    -multiple values
    -push values
    -pop values
    -Remove a property altogether
    -Rename a field

Upserts
-Upserts will insert a value if it doesn't exist. If it does, it will update it.