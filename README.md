# Useful_data
Welcome to the Useful_Data. In this repository, I will introduce some useful database websites that provide free data may be useful in your project. Here is the list:
1. Stooq: Stooq offers historic daily, hourly, and minutely data on indicies, ETFs, stocks, bonds, forex and cryptocurrencies. So far(Feb 2024), the pandas.datareader api only supports single ticker download, which means manually download is required for multiple download. In stooq notebook, I downloaded US daily data and store it into HDF5 format with a multiindex dataframe.
2. CSI.h5: The file includes daily trading data from  2019-01-01 to 2023-12-31 of CSI's constituents. The directory under CSI.h5 is '/constituents'.
