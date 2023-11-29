# module_27_project
cars.py: Takes data from car_sales.json, produces a report (reports.py) with top 3 summary, then sends an email (emails.py).
emails.py: The code for preparing and sending the email.
reports.py: The code for preparing and creating the pdf report.
car_sales.json: The complete input car data: 
    ({"id",
    "car"
        {"car_model","car_year"},
    "price",
    "total_sales"}).
Not included: Output report (cars.pdf) in ~/tmp/.