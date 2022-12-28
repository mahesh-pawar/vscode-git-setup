# MySQL shutdown unexpectedly

#### Steps to solve "Error: MySQL shutdown unexpectedly"
1. Navigate to `C:\xampp\mysql` folder.
1. Rename your folder `data` to `data_old`.
2. Make a copy of `backup` folder and name it as `data`.
3. Copy all your database folders from `data_old` into `data` (except `mysql`, `performance_schema`, and `phpmyadmin` folders).
4. Copy the`data_old/ibdata1` file into `data` folder.
5. At last, Start MySQL from XAMPP control panel.
