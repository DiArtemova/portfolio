# Daten

## Datenquelle
Kaggle (link)

## Name der Originaldatei
### train.csv
The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
    * store_nbr identifies the store at which the products are sold
    * family identifies the type of product sold. 33 families total
    * sales gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips)
    * onpromotion gives the total number of items in a product family that were being promoted at a store at a given date.

### test.csv
The test data, having the same features as the training data. The dates in the test data are for the 15 days after the last date in the training data.

### stores.csv
Store metadata, including city, state, type, and cluster. cluster is a grouping of similar stores.

### transactions.csv
date, store, transations

### holidays_events.csv

### oil.csv


## Lokaler Speicherort
data/raw/

Die Originaldateien bleiben unverändert und werden nicht in dieses Repository aufgenommen.

Die Zugangsbedingungen und die Bedingungen für eine Weitergabe des Datensatzes müssen noch geprüft werden.
