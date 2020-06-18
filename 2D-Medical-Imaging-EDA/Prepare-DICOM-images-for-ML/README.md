
## Prepare DICOM Images for ML
A small set of seven DICOM images. Here, rather than extracting the image itself from the DICOM file, we'll be extracting other attributes that tell us about the image and the patient who is represented in it.<br>

create a single dataframe that has the following columns:<br>
- Patient ID
- Patient Age (as an integer)
- Patient Sex (M/F)
- Imaging Modality
- Type of finding in the image
- Number of rows in the image
- Number of columns in the image

Print the contents of this dataframe.