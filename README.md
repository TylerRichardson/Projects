# Overview
The purpose of this project was to get my hands dirty with the data. As so much
of what a Data Analyst does is data cleaning, I thought this was an excellent
opportunity to do just that. **My goal here isn't to analyze, rather to make the
data clean, thereby making it more useful.** 


# Attributes
- UniqueID
- ParcelID
- LandUse
- SalePrice
- LegalReference
- SoldAsVacant
- OwnerName
- OwnerAddress
- OwnerCity
- OwnerState
- PropertyAddress
- PropertyCity
- SaleDate
- Acerage
- TaxDistrict
- LandValue
- BuildingVale
- TotalValue
- YearBuilt
- Bedrooms
- FullBaths
- HalfBaths


### Process
- Standardize Date Formatting: DATETIME unnecessary (HH:MM:SS not included)
- Fill PropertyAddress NULL values using corresponding ParcelIDs
- Split PropertyAddress column (Address, City, State)
- Split OwnerAddress column (Address, City)
- Standardize SoldAsVacant Formatting: Change Y/N values to "Yes" and "No"
- Remove duplicate ecords
- Delete newly redundant records
