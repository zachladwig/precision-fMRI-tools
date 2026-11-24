# precision-fMRI-tools
Some tools for working with precision fMRI data 

I assume you've already done the major processing (fmriprep + xcp-d or equivalent) and you now have a fully preprocessed and concatenated CIFTI per individual.

These tools will 
1. Create an individual reliability curve
2. Calculate a measure of "Network Signal" in your data (using code from XXXZ)
3. Estimate individual topography of large-scale functional networks

They also include some reference data of various quality that I use to benchmark new data against. 
