# Geocoding EHRI camps to detect potential errors
The purpose of this notebook is to retrieve the entire list of concentration camps provided by the EHRI Portal using its GraphQL API, find the camps that already contain longitude and latitude values, geocode them again based on their names and alternative names using the Nominatim API and then compare the results to detect potential errors in the EHRI datasets.

The files in this repository are meant to be run in a local notebook environment. However, a version that runs in the Google Colab environment has also been created and can be found here: https://colab.research.google.com/drive/1GMUDuj42UJ_kOtq3Cy8LRsre1Z2Y8OX1?usp=sharing

If you are not familiar with running Jupyter notebooks locally, I'd suggest you visit this notebook in Google Colab.
