# 2E-LRP-ECB
Two-Echelon Location-Routing Problem with Eco-conscious Customers Behavior

This repository contains the code and the supplementary material for the paper: 
"V.Bonomi, D.Jorge, T.Ramos, A. Barbosa-Póvoa. Eco-Conscious Customers Behavior in Capacitated Two-Echelon Location-Routing Models for Sustainable Last-Mile Delivery."
Preprint: https://zenodo.org/records/17209985?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImRmZTY4ZWZiLWExMTItNGI4OS04MmU3LWUzYjYyYmM4N2I1ZSIsImRhdGEiOnt9LCJyYW5kb20iOiIwMGUyODM5OTc3ZmM5OWFmYTU0YmU4NWVkNjRmZmQ0NCJ9.2vScL8EIHHih9ANYy5Gvyc1ye6ydonGrmgIyg13117m3VIaQMGUzw0RdRonf4HC10ezZ3xWwP3XhSV_AKrWlZw
Dataset: https://zenodo.org/records/17215425?token=eyJhbGciOiJIUzUxMiJ9.eyJpZCI6ImY3NGVjNmY0LWM2ZjctNDA1Yi1iYjE5LTUxMzE4NmIyZmJmMyIsImRhdGEiOnt9LCJyYW5kb20iOiJmN2JmODBhOTA3YzI3NTJiN2FkNjE2YmNlYjA4OTAwZSJ9.yk8jXi_WlQaHuKbo0sQXFcV0jYh6JBV2mEBFtO66YFPy30prMwsQG8eaBf1ceBKJ_kwalOCVwtaQahZttbtnDQ


-- 
Repository structure: 
src/
 ├── Parameters.java        # Main parameters of the model
 ├── Main.java             # entry point
 ├── Model.java        # MILP model
 ├── Instance.java        # Instance with main methods for distances 
 └── InstanceReader.java    # parse Zenodo instances
