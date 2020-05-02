# Northwind SQL Questions

From [YugabyteDB](https://docs.yugabyte.com/latest/sample-data/northwind/):

> The Northwind database is a sample database that was originally created by Microsoft and used as the basis for their tutorials in a variety of database products for decades. The Northwind database contains the sales data for a fictitious company called “Northwind Traders,” which imports and exports specialty foods from around the world. The Northwind database is an excellent tutorial schema for a small-business ERP, with customers, orders, inventory, purchasing, suppliers, shipping, employees, and single-entry accounting. The Northwind database has since been ported to a variety of non-Microsoft databases, including PostgreSQL.

You can find a copy of the northwind database for PostgreSQL [here](https://github.com/pthom/northwind_psql/blob/d3e04e4952b834ece16adb7d5a5880c44dc2d485/northwind.sql).

## Practice Questions that require JOINs

- Who are our suppliers who provide Beverages?
- Who are our suppliers who provide Confections?
- How many orders were there in the Tampa territory for Q2 1997? (Q2 is April 1 - June 30)
- Which employees have sold orders to customers in Germany?
