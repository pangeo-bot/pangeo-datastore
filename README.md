# pangeo-datastore
This repository represents a work in progress - the automation of data catalogging for Pangeo. At the moment, there is stll much to be done:

- The current catalog only accounts for zarr stores - we will need to add functionality for netCDF and other file types.
- The current scripts are only able to create a catalog from scratch - in the future, 
it would be much more efficient to simply update the existing catalog based on changes to the storage bucket(s).
- This script could be automated - either to check and update the catalog on a timed interval or even on a trigger 
when data is uploaded to the bucket.
