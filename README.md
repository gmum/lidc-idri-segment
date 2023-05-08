# lidc-idri-segment

Reference segmentation masks for the LIDC-IDRI dataset in NIfTI format. Filenames correspond to the series_instance_uid DICOM attribute in 
LIDC-IDRI metadata (as returned by pylidc). Can be read using the nibabel library. All segmentation masks were prepared by a team of three trained radiologists.

The original LIDC-IDRI data can be downloaded from: https://wiki.cancerimagingarchive.net/pages/viewpage.action?pageId=1966254

Tools:
* pylidc https://github.com/notmatthancock/pylidc
* nibabel https://github.com/nipy/nibabel
