# mitoconstrictor

Set of python scripts for mtDNA annotation. Run as:</br>
python gff2gb.py fasta_file</br>
Prerequisites:</br>
-python (currently version 2.7 is supported)</br>
-Biopython https://biopython.org/
(and several other python libraries easily installed with pip)</br>
-wise2 https://www.ebi.ac.uk/~birney/wise2/, version 2.2 should be available for most linux distributions but recommended version is 2.4.1</br>
-tmhmm https://services.healthtech.dtu.dk/software.php</br>
-infernal http://eddylab.org/infernal/</br>
-arwen http://130.235.244.92/ARWEN/arwen1.2.3.c</br>
-glimmer3 http://ccb.jhu.edu/software/glimmer/index.shtml (needed icm profile for glimmer, included)</br>
-critica http://www.life.illinois.edu/gary/programs/CRITICA/critica105b.tar.gz (need modified perl files for modern BLAST, included)</br>
-vmatch http://www.vmatch.de/</br>
-blast+ https://ftp.ncbi.nlm.nih.gov/blast/executables/blast+/LATEST/</br>
-EMBOSS (getorf) ftp://emboss.open-bio.org/pub/EMBOSS/emboss-latest.tar.gz </br>
-ViennaRNA package (with python bindings) https://github.com/ViennaRNA/ViennaRNA </br>
-Databases:</br>
+database of mitochondrial genomes, blast-formatted, with corresponding lineage specification (for mgcode and profile customization, included, can be customized at will)</br>
+individual blast-formatted sub-databases of major clades (for critica, examples included)</br>
+hmmer v2 profiles of mitochondrial proteins (included, these can be customized with hmmer)</br>
+cm profiles of rRNAs and tRNAs (included, these can be customized with locarna, rRNA files must be indexed with cmpress from infernal package)</br>
+pfam database (part A, hmm file pressed with hmmer, non-essential, not included) </br>
Produces annotated GenBank file as well as several pdf and text files describing the features of the mitogenome (including tbl file needed for GenBank submission).</br>
</br>
Several dependencies run on linux only but Win10 linux subsystem is also adequate. Everything is commandline-only.</br>

Publication with some examples of usage is freely available at:</br>
https://www.nature.com/articles/s41598-020-67976-6
