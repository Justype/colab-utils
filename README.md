# colab-utils

`ipynbs` in [Google Colab](https://colab.research.google.com/) for simple bioinfo tasks:

| File Manipulation Task  | ipy Notebook | Description |
| :---------------------- | :----------- | :---------- |
| `fastq.ora` decompression | <a target="_blank" href="https://colab.research.google.com/github/Justype/colab-utils/blob/main/sequencing/ORAD.ipynb">  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/> </a> | convert `fastq.ora` to `fastq.gz` using Illumina GRAGEN |

　

| Data Retrieving Task     | ipy Notebook | Description |
| :---------------------- | :----------- | :---------- |
| Get file meta info from [GDC](https://portal.gdc.cancer.gov/) |  <a target="_blank" href="https://colab.research.google.com/github/Justype/colab-utils/blob/main/download/GDC-files.ipynb"> <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/> </a> | Use filters to get **file IDs** and their **demographic** and **diagnostic** info, then sampling |

## Colab is an Ubuntu Container

```bash
!lscpu               # View CPU Info
!lsmem               # View Memory Info
!df -h               # View Disk Usage
!cat /etc/os-release # Check Linux Distro
```

- n1-highmem-2 instance
- 2vCPU @ 2.2GHz
- 13GB RAM
- 100GB Free Space

## Bookmarks

| Website                  | Usage              |
| :----------------------- | :----------------- |
| https://openincolab.com/ | Make Colab Badge   |
| https://tinypng.com/     | Shrink PNG and JPG |
