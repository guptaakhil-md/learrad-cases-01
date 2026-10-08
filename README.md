# learrad-cases-01

Imaging studies for the [Learrad](https://github.com/guptaakhil-md/learrad) radiology
reporting simulator. Each folder is one case: the complete study as plain DICOM files
(one sub-folder per series) plus `study.json`, an index the viewer reads.

**Not for clinical use.** For education only.

## Source, licence and attribution

All studies in this repository come from the **ReMIND** collection on The Cancer Imaging
Archive (TCIA) and are redistributed under the
[Creative Commons Attribution 4.0 International licence (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/).

**Images modified (de-identified and re-indexed).** The images were de-identified and
defaced by the original authors. For this repository they were changed further: only the
pre-operative MRI study of each case is included; patient name/ID, all instance UIDs and
all dates in the DICOM headers were replaced; private and clinical-trial tags were
removed; files were renamed and grouped into one folder per series; `study.json` was
generated from the headers. Pixel data is unchanged.

Data citation:

> Juvekar, P., Dorent, R., Kögl, F., Torio, E., Barr, C., Rigolo, L., Galvin, C.,
> Jowkar, N., Kazi, A., Haouchine, N., Cheema, H., Navab, N., Pieper, S., Wells, W. M.,
> Bi, W. L., Golby, A., Frisken, S., & Kapur, T. (2023). The Brain Resection Multimodal
> Imaging Database (ReMIND) (Version 1) [dataset]. The Cancer Imaging Archive.
> https://doi.org/10.7937/3RAG-D070

Publication: Juvekar, P., et al. (2024). Scientific Data, 11.
https://doi.org/10.1038/s41597-024-03295-z

TCIA: Clark, K., et al. (2013). The Cancer Imaging Archive (TCIA): Maintaining and
Operating a Public Information Repository. Journal of Digital Imaging, 26(6), 1045–1057.
https://doi.org/10.1007/s10278-013-9622-7

## Data usage policy

This data is covered by the
[TCIA Data Usage Policy](https://www.cancerimagingarchive.net/data-usage-policies-and-restrictions/).
In particular, you must not use it, alone or with other information, to identify or
contact the individuals it came from, and you must not generate facial images or
comparable representations from it. Anyone reusing these files must keep this
attribution and pass these terms on.
