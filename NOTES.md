# Phase 2 Evidence

## ContosoPizza API

### GET
Tested GET /Pizza successfully.
Status code: 200 OK.

![alt text](GET.png)
![alt text](GET1.png)

### POST
Added an additional pizza using POST /Pizza.
Status code: 201 Created.

![alt text](POST.png)

### PUT
Updated the pizza using PUT /Pizza/{id}.
Status code: 204 No Content.

![alt text](PUT.png)


### DELETE
Deleted the pizza using DELETE /Pizza/{id}.
Status code: 204 No Content.
![alt text](DELETE.png)

## Sales Summary

Added the CreateSalesSummary function to generate a sales summary report.

The report includes:
- Total sales
- Total sales for each individual file
- Currency formatting

The generated report is located at:

Sales/salesTotalDir/sales_summary.txt

----------------------------
Total Sales: R$ 2.012,20

Details:
    sales.json: R$ 88,88
    sales.json: R$ 501,22
    salestotals.json: R$ 0,00
    sales.json: R$ 1.234,22
    salestotals.json: R$ 0,00
    sales.json: R$ 99,00
    salestotals.json: R$ 0,00
    sales.json: R$ 88,88
    salestotals.json: R$ 0,00
PS C:\Users\samba\mslearn-dotnet-files\Sales> 