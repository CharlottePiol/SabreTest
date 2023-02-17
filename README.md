# SabreTest

Sabre Technical Exam for Senior Developer.

Summary:

In this exam we would want to test your skills in doing integrations from other software. 
So to start You will be creating an application that will call an API.

1. Create a function that calls a Web API with SSL Security.
     a. Return of an API is compose of JSON Data {“DocEntry”: 1, “Customer”: “C001”, “OrderNumber”: 12345, “Lines”: [{“LineNum”: 1,“ItemCode”: “I001”, “Qty”: “2.00”,             “Warehouse”: “WMS” ,”Price”: null }, {“LineNum”: 2,“ItemCode”: “I002”, “Qty”: null, “Warehouse”: “WMS”,”Price”: 108.06}].
     b. Table Header will have a field of DocTotal: sum of Table Details.Price.
     c. Once API was retrieved, it will be saved to a Table Header and Table Details for Lines.
***Note: Price and Amount field should accept null values.****

2. Creates a simple application that incorporates wpf form(With button to Consume an API) and auto auto run of WPF Application (Consuming the api).
