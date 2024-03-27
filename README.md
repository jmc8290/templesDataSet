# templesDataSet
Curated dataset of temples of the Church of Jesus Christ of Latter-Day Saints. Created from publicly available information on churchofjesuschristtemples.org. Churchofjesuschristtemples.org is regarded as the authority when it comes everything concerning temples of the Church of Jesus Christ. Information about every temple is kept up-to-date (typically within a day of any change) including construction updates, announcements, dedicatory prayers, pictures, and more. What is of interest is that 'more' part. The website has many statistical tables that are easy to scrape and process for data analysis. This dataset was made by combining two of the many datasets available on the website.

### Included Files
DatasetCuration.ipynb is the notebook where the data was pulled and curated

templeDimensionElevation.csv is the final dataset. Includes the following columns:
---------------------------------------------------------------------------------------------------------------
Temple             (String)  Name of temple

Instruction Rooms  (Int)     Number of rooms used during the endowment (Excludes celestial room)

Sealing Rooms      (Int)     Number of sealing rooms

Baptismal Fonts    (Int)     Number of baptismal fonts

Square Footage     (Int)     Square footage of the interior of the temple (including annexes)

Acreage            (Float)   Acreage of the plot on which the temple is built

Elevation (Feet)   (Float)   Elevation (in feet) where the temple is built

--------------------------------------------------------------------------------------------------------------
