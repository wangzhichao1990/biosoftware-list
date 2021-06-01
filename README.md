# biosoftware-list

## 序列处理

- [fastqc](https://www.bioinformatics.babraham.ac.uk/projects/fastqc/): 序列质量信息查看工具
- [cutadapt](https://github.com/marcelm/cutadapt): 去接头，长度和质量过滤等
- [Trimmomatic](http://www.usadellab.org/cms/?page=trimmomatic): 去接头，长度和质量过滤等
- [fastp](https://github.com/OpenGene/fastp): 去接头，长度和质量过滤等
- [seqtk](https://github.com/lh3/seqtk): 序列处理工具
- [seqkit](https://github.com/shenwei356/seqkit): 序列处理工具
- [fastx_toolkit](http://hannonlab.cshl.edu/fastx_toolkit/):序列处理工具
- [flash](https://ccb.jhu.edu/software/FLASH/): 双端序列合并
- [fastq-join](https://github.com/brwnj/fastq-join): 双端序列合并
- [pear](https://sco.h-its.org/exelixis/web/software/pear/doc.html): 双端序列合并

## 序列比对

[List of sequence alignment software](https://en.wikipedia.org/wiki/List_of_sequence_alignment_software)

**Short-read sequence alignment**

- [bwa](https://github.com/lh3/bwa)
- [bowtie/bowtie2](https://github.com/BenLangmead/bowtie)
- [tophat](http://ccb.jhu.edu/software/tophat/index.shtml)
- [hisat2](https://daehwankimlab.github.io/hisat2/)

## 微生物组扩增子测序分析

- [qiime2](https://qiime2.org/): 微生物组扩增子测序数据综合分析软件
- [usearch](http://www.drive5.com/usearch/): 微生物组扩增子测序数据综合分析软件
- [vsearch](https://github.com/torognes/vsearch): 微生物组扩增子测序数据综合分析软件
- [mothur](https://mothur.org/): 微生物组扩增子测序数据综合分析软件
- [rdptools](https://github.com/rdpstaff/RDPTools): 微生物组扩增子测序数据综合分析软件
- [micca](https://micca.readthedocs.io/en/latest/index.html): 微生物组扩增子测序数据综合分析软件
- [dada2](https://benjjneb.github.io/dada2/index.html): 微生物组扩增子测序数据综合分析R包
- [swarm](https://github.com/torognes/swarm): OTU聚类
- [SPINGO](https://github.com/GuyAllard/SPINGO): 物种级别OTU分类
- [MAPseq](https://github.com/jfmrod/MAPseq): 物种分类鉴定
- [dokdo](https://github.com/sbslee/dokdo): 微生物组测序下游分析python包
- [phyloseq](https://joey711.github.io/phyloseq/): 微生物组测序下游分析R包
- [MicrobiotaProcess](https://github.com/YuLab-SMU/MicrobiotaProcess): 微生物组测序下游分析R包
- [microbiomeMarker](https://github.com/yiluheihei/microbiomeMarker): 微生物组测序下游分析R包
- [MicrobiomeStatPlot](https://github.com/YongxinLiu/MicrobiomeStatPlot): 《微生物组数据分析与可视化实战》

## 进化分析

- [mafft](https://mafft.cbrc.jp/alignment/software/): 多序列比对
- [muscle](http://www.drive5.com/muscle/): 多序列比对
- [Clustal](http://www.clustal.org/): 多序列比对
- [trimal](https://github.com/scapella/trimal): 修剪多序列比对
- [iqtree](http://www.iqtree.org/): 进化树构建
- [fasttree](http://www.microbesonline.org/fasttree/): 进化树构建
- [RAXML](http://evomics.org/learning/phylogenetics/raxml/): 进化树构建
- [mega](https://www.megasoftware.net/): 进化树构建
- [phylommand](https://github.com/RybergGroup/phylommand): 创建、操作和分析进化树的工具

## 宏基因组测序分析

### 序列组装

**[GAGE](http://gage.cbcb.umd.edu/index.html)**

- [ABySS](http://www.bcgsc.ca/platform/bioinfo/software/abyss)
- [ALLPATHS-LG](http://software.broadinstitute.org/allpaths-lg/blog/?page_id=12)
- [Bambus2](http://sourceforge.net/apps/mediawiki/amos/index.php?title=Bambus2)
- [Celera Assembler](http://sourceforge.net/apps/mediawiki/wgs-assembler/index.php?title=Main_Pag\e)
- [MSR-CA](http://www.genome.umd.edu/SR_CA_MANUAL.htm) 
-  [SGA](https://github.com/jts/sga)
- [SOAPdenovo](http://soap.genomics.org.cn/soapdenovo.html)
-  [Velvet](http://www.ebi.ac.uk/~zerbino/velvet/)

**推荐**

- [spades](https://github.com/ablab/spades)
- [megahit](https://github.com/voutcn/megahit/)
- [IDBA-UD](https://github.com/loneknightpy/idba)
- [Ray](http://denovoassembler.sourceforge.net/)

### 物种鉴定

[Benchmarking Metagenomics Tools for Taxonomic Classification](https://www.cell.com/cell/fulltext/S0092-8674(19)30775-5)

**几个常用的有：**

- [kraken2](http://ccb.jhu.edu/software/kraken2/)
- [Centrifuge](http://ccb.jhu.edu/software/centrifuge/)
- [kaiju](http://kaiju.binf.ku.dk/)
- [MetaPhlAn](https://huttenhower.sph.harvard.edu/metaphlan)
- [diamond](https://github.com/bbuchfink/diamond)

## 变异分析

- [samtools](http://www.htslib.org/)/[bcftools](http://www.htslib.org/doc/bcftools.html)
- [freebayes](https://github.com/freebayes/freebayes)
- [ngsep](https://sourceforge.net/projects/ngsep/)
- [snippy](https://github.com/tseemann/snippy)
- [gatk](https://gatk.broadinstitute.org/hc/en-us)
- [vcftools](https://vcftools.github.io/index.html)
- [snpEff](https://pcingola.github.io/SnpEff/)
- [ANNOVAR](https://annovar.openbioinformatics.org/en/latest/)
- [VEP](http://asia.ensembl.org/info/docs/tools/vep/script/index.html)

## 耐药分析

- [rgi](https://github.com/arpcard/rgi): 耐药分析
- [TBProfiler](https://github.com/jodyphelan/TBProfiler): 结核耐药分析
- [mykrobe](https://github.com/Mykrobe-tools/mykrobe): 结核耐药分析

## nanopore分析常用软件

### 官方软件

[Data analysis](https://community.nanoporetech.com/technical_documents/data-analysis/）

### 社区软件

[A collection of data analysis tools which have been developed by the Nanopore Community](https://community.nanoporetech.com/info_sheets/community-developed-data-a)

## 分析流程

### 宏基因组分析

- [metscale](https://github.com/signaturescience/metscale)
- [ metaWRAP](https://github.com/bxlab/metaWRAP)
- [atlas](https://github.com/metagenome-atlas/atlas)
- [ bhattlab_workflows](https://github.com/bhattlab/bhattlab_workflows)
- [mag](https://nf-co.re/mag)
- [SqueezeMeta](https://github.com/jtamames/SqueezeMeta)

### 扩增子测序

- [ampliseq](https://nf-co.re/ampliseq)
- [mothurPipeline](https://github.com/SchlossLab/mothurPipeline)
- [16S-dada2](https://github.com/SilasK/16S-dada2)
- [Natrix](https://github.com/MW55/Natrix)
- [dadasnake](https://github.com/a-h-b/dadasnake)
- [tourmaline](https://github.com/ropolomx/tourmaline)

### 其他

- [snakemake-workflows](https://github.com/snakemake-workflows)
- [nf-core](https://nf-co.re/)

