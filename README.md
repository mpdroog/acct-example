# acct-example
InvoiceD accounting-db example.

How to add another year?
```
mkdir -p name/$(date +\%Y) # mkdir name/2019
cd name/$(date +\%Y)
touch .keep
cd -
git add .
git commit -m "Add another year"
```
