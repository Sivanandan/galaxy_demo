# Galaxy

* SCINet Documentation: https://scinet.usda.gov/guide/galaxy/

* Log into SCINet Galaxy at: [galaxy.scinet.usda.gov](galaxy.scinet.usda.gov)
* Panels are split into Tools, Main, and History
* Describe histories (new history)
* Get Data/Upload File
  * ftp by placing files in `/90daydata/galaxy/upload/USERNAME@usda.gov/`

```
cd /90daydata/galaxy/upload/USER.NAME@usda.gov
```

## Example Dataset 


```
# wget statements here

wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792525/SRR6792525_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792525/SRR6792525_2.fastq.gz
```

<!--
```
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/006/SRR6792526/SRR6792526_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/006/SRR6792526/SRR6792526_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/007/SRR6792527/SRR6792527_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/007/SRR6792527/SRR6792527_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/008/SRR6792528/SRR6792528_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/008/SRR6792528/SRR6792528_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/009/SRR6792529/SRR6792529_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/009/SRR6792529/SRR6792529_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/000/SRR6792530/SRR6792530_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/000/SRR6792530/SRR6792530_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/001/SRR6792531/SRR6792531_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/001/SRR6792531/SRR6792531_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/002/SRR6792532/SRR6792532_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/002/SRR6792532/SRR6792532_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/003/SRR6792533/SRR6792533_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/003/SRR6792533/SRR6792533_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/004/SRR6792534/SRR6792534_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/004/SRR6792534/SRR6792534_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792535/SRR6792535_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792535/SRR6792535_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/006/SRR6792536/SRR6792536_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/006/SRR6792536/SRR6792536_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/007/SRR6792537/SRR6792537_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/007/SRR6792537/SRR6792537_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/008/SRR6792538/SRR6792538_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/008/SRR6792538/SRR6792538_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/009/SRR6792539/SRR6792539_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/009/SRR6792539/SRR6792539_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/000/SRR6792540/SRR6792540_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/000/SRR6792540/SRR6792540_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/001/SRR6792541/SRR6792541_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/001/SRR6792541/SRR6792541_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/002/SRR6792542/SRR6792542_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/002/SRR6792542/SRR6792542_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/003/SRR6792543/SRR6792543_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/003/SRR6792543/SRR6792543_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/004/SRR6792544/SRR6792544_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/004/SRR6792544/SRR6792544_2.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792545/SRR6792545_1.fastq.gz
wget ftp://ftp.sra.ebi.ac.uk/vol1/fastq/SRR679/005/SRR6792545/SRR6792545_2.fastq.gz
```
-->

* Maize Dataset

* Walk through HiSat2
* Setting options
* 

```
squeue -u galaxy-service # quota
show jobs IDHERE
ssh 
```

/luster/project/galaxy/galaxy-py3/galaxy-base/database/jobs_directory/.../.../working


## How to request software

* Check for software on https://toolshed.g2.bx.psu.edu/
* Email VRSC@usda.gov requesting a tool and version

## Is there a way to share dataset


