# geocoding_EHRI_camps
The purpose of this notebook is to retrieve the entire list of concentration camps provided by the EHRI Portal using its GraphQL API, find the camps that already contain longitude and latitude values, geocode them again based on their names and alternative names using the Nominatim API and then compare the results to detect potential errors in the EHRI datasets.
