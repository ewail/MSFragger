# MSFragger
MSFragger is an ultrafast database search tool for peptide identifications in mass spectrometry-based proteomics.  It differs from conventional search engines by computing similarity scores in a fragment-centric fashion using a theoretical fragment index of candidate peptides. MSFragger has demonstrated excellent performance across a wide range of datasets and applications. The speed of MSFragger makes it particularly suitable for enzyme unconstrained searches, and for ‘open’ database searches (with the precursor mass tolerance is set to hundreds of Daltons) for the identification of modified peptides. 

MSFragger is implemented in the cross-platform Java programming language, and is available as a standalone JAR file. It is compatible with standard open file formats for mass spectrometry data (mzXML/mzML). It writes output in either tabular or pepXML formats, making it fully compatible with downstream data analysis pipelines such as Trans-Proteomic Pipeline and [Philosopher](https://nesvilab.github.io/philosopher/). On Windows, the easiest way to run MSFragger/Philosopher tools is using [FragPipe GUI](https://github.com/Nesvilab/FragPipe).

## Download
To download the latest release of MSFragger:
1.	Complete the license agreement form on the [U-M Tech Transfer site](http://inventions.umich.edu/technologies/7143_msfragger-ultrafast-and-comprehensive-identification-of-peptides-from-tandem-mass-spectra). The software is available free of charge for academic and non-profit research, and for educational purposes. For other uses, please contact the U-M Tech Transfer Office.
2.	Download the initial release of MSFragger software using instructions received from the U-M Tech Transfer Office.
3.	Once you obtained the MSFragger software, the latest version of the software can be downloaded (under the same license terms as the original version) using the [Upgrade site](https://msfragger.arsci.com/upgrader/). 

## Release Notes
The latest version of MSFragger was released on 2018-11-10. 

Check [here](CHANGELOG.md) for the full list of MSFragger versions and changes.

## How to Cite
Kong AT, Leprevost FV, Avtonomov DM, Mellacheruvu D, Nesvizhskii AI. MSFragger: ultrafast and comprehensive peptide identification in mass spectrometry-based proteomics. Nature Methods 14:513–520 (2017). [Manuscript](https://www.nature.com/articles/nmeth.4256) 
