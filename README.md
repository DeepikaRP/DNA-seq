<h2> Bacterial variant calling analysis </h2> 
<p> Variant calling is a DNA-Seq analysis to identify different variants and analyze like SNPs, In-Dels, SNVs, etc... Here we are trying to analyze the potential variants observed in E.coli K-12 bacteria that was treated with Doxycycline for AMR studies. </p>
<p> This workflow was a part of my dissertation & currently I am automating this using Nextflow.</p>
<br>
<p> Workflow </p>
<p> QC & Trimming: Fastqc & Fastp </p>
<p> Reference genome De novo assembly : Spades or Velvet </p>
<p> Indexing & Alignment: BWA </p>
<p> Bam file indexing, Sorting and Filtering : Samtools</p>
<p> Variant calling : BCFTools</p>
<p> Annotation : SnpEff </p>
