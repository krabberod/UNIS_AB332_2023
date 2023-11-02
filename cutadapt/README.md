- Script for running cutadapt on the HPC cluster Saga
- The main script is called "cutadapt_paired_primertags.sh"
- It reads the *batch_file.tx* which can contain multiple sequencing runs and their correpsonding primer pairs with tags
     
Content of **batch_file.txt***

| R1-sequences      | R2-sequences      | FWD primers       | REV Primers       |
| ----------------- | ----------------- | ----------------- | ----------------- |
| file1_R1.fastq.gz | file1_R2.fastq.gz | FWD-primer1.fasta | REV-primer1.fasta |
| file2_R1.fastq.gz | file2_R2.fastq.gz | FWD-primer2.fasta | REV-primer2.fasta |
| Etc...            | Etc...            | Etc...            | Etc...            |
