# Home_sales
*   We will use pyspark and sql to perform some analysis of home prices.
*   We load the file from AWS S3 and read it into a dataframe.
*   Create a temporary file to use in the analysis.
*   We compute avarage sale price of houses based on: 

            *   Year the house was built.

            *   Number of Bedrooms.

            *   Number of Bathrooms.

            *   Square footage.

*   We create a cache for the temporary file and check to ensure it is created
*   We partiton the dataframe and save a parquet
*   We compare the run times for the temporary file, cached file and the parquet file.
*   We uncache the temporary file and confirm the same.