# MORITS

This is the official repository for the MHC outward-facing residue identifying tool for sequence alignment (MORITS).

MORITS is ready to be used under Microsoft Windows. You can use the two provided input files to run a peptide search between environmental allergens and SARS-CoV-2 by 
1. loading them in the MORITS tool
     - Input 1 via the "Load Sequence 1" button
     - Input 2 via the "Load Sequence 2" button
3. select at least one desired TCEM (all three simultaneously is also possible)
     - TCEM 1 for similarities in MHC I
     - TCEM 2a and 2b for similaries in MHC II
     - more details: Bremel et al., 2015 https://www.frontiersin.org/journals/immunology/articles/10.3389/fimmu.2015.00538/full
4. select the stringency of filtering
     - 100% match = no mismatches allowed
     - 80% match = 1 mismatch along TCEM allowed
     - you have to select at least one (both also works)
6. press "Find Matches". Depending on the size of your input files, the tool will take a while to perform the alignment and will be unresponsive until it is finished.
7. save your result list in the end as .txt file

The output list can be important in Microsoft Excel (or your preferred Software) for filtering. For MHC binding prediction, save tab-separated files using Microsoft Excel and generate .fasta files using https://sequenceconversion.bugaco.com/converter/biology/sequences/tab_to_fasta.php. The MHC binding prediction is not part of the MORITS tool and can be done under https://www.iedb.org/home_v3.php or with your software of choice.
