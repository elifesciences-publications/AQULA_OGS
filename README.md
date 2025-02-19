

### This code is associated with the paper from Fallon et al., "Firefly genomes illuminate parallel origins of bioluminescence in beetles". eLife, 2018. http://dx.doi.org/10.7554/eLife.36495

## *Aquatica lateralis* Official Geneset
This is the Official Geneset (OGS) for [*Aquatica lateralis* (ヘイケボタル)](https://en.wikipedia.org/wiki/Aquatica_lateralis)

As reported in this preprint: [https://www.biorxiv.org/content/early/2018/02/25/237586](https://www.biorxiv.org/content/early/2018/02/25/237586)

Genome version: Alat1.3
Geneset version: AQULA_OGS1.0

This GIT repository is meant to keep track of any changes to the OGS, and hopefully have a useful audit log which describes what changes occured.

Also see: [fireflybase.org](http://www.fireflybase.org)

### Where can I download an official version of the data?
See [Releases](https://github.com/photocyte/ILUMI_OGS/releases)

### Dependencies
(Executable from your local command line)

* [gt](http://genometools.org/index.html)
* [igvtools](https://software.broadinstitute.org/software/igv/download) (also available in [IGV](https://software.broadinstitute.org/software/igv/home) GUI)
* [seqkit](https://github.com/shenwei356/seqkit)
* [gffutils](http://daler.github.io/gffutils/installation.html)

### Reporting gene model problems

Report issues [here](https://github.com/photocyte/ILUMI_OGS/issues)

### Making direct gene model or annotation changes

 1. Fork this repository
 2. Download and edit the [AQULA_OGS*.gff3](./AQULA_OGS1.0.gff3) file
 3. Sort the GFF3 file and regenerate dependent files (CDS, mRNA, peptide) files using the [utility_scripts/sort-and-regenerate-OGS-GFF.sh](utility_scripts/sort-and-regenerate-OGS-GFF.sh) script.
 4. Commit your changes back to your repository, with an informative message for the changes that were made
 5. Submit a pull request to this repository
 6. If all looks good I'll merge the pull request

### Future
 
Get a proper relational database ala [Chado](http://gmod.org/wiki/Chado_-_Getting_Started), and/or a collaborative GUI editing interface, ala [Apollo](http://genomearchitect.github.io).

### License

Data files (e.g. geneset .fa.gz files, gff3 files) are licensed under the [Creative Commons CC-BY-SA 4.0 International license](https://creativecommons.org/licenses/by-sa/4.0/).  Software (e.g. BASH scripts) is licensed under the [MIT license](https://opensource.org/licenses/MIT)

<img src="https://mirrors.creativecommons.org/presskit/buttons/88x31/png/by-sa.png" alt="Drawing" style="width: 100px;"/>
