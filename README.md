# The BioSRA - easy SRA files downloading and converting


<p align="right">
<img  src="https://github.com/jkubis96/GEDSpy/blob/main/fig/logo_jbs.PNG?raw=true" alt="drawing" width="250" />
</p>


### Author: Jakub Kubiś 

<div align="left">
 Institute of Bioorganic Chemistry<br />
 Polish Academy of Sciences<br />
 Department of Molecular Neurobiology<br />
</div>


## Description


<div align="justify"> The BioSRA was developed for multiprocessing downloading SRA files with converting to *.fastq.gz format </div>
<div align="justify"> The BioSRA uses SRAtoolkit with the NCBI tools license. See license [https://github.com/ncbi/sra-tools] </div>


</br>



## Installation

#### Download:

```
git clone https://github.com/jkubis96/BioSRA.git
```

#### Get BioSRA directory:

```
cd BioSRA
```

#### Run script:

```
./run
```

#### Run installation:

```
Select: 1
```

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s4.bmp" alt="drawing" width="600" />
</p>


#### VDB configuration:

```
Select: 2
```

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s5.bmp" alt="drawing" width="600" />
</p>

```
Select: e
```

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s1.bmp" alt="drawing" width="600" />
</p>

```
Select: s
```

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s2.bmp" alt="drawing" width="600" />
</p>

```
Select: o
```


<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s3.bmp" alt="drawing" width="600" />
</p>


```
Select: x
```


#### Quit:

```
Select: 3
```

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s6.bmp" alt="drawing" width="600" />
</p>


## Usage

<div align="justify"> After installing all functions of BioSRA and SRAtoolkit can be called from the console in any directory  </div>

### Parallel downloading multiple SRA files in BioSRA

#### 1. Choose directory for downloaded files

#### 2. Download SraAccList.txt from Sequence Read Archive

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s7.bmp" alt="drawing" width="600" />
</p>

#### 3. Run function

```
SRAtoFAST_download SraAccList.txt
```

#### 4. Wait for downloading and converting all files

<p align="center">
<img  src="https://github.com/jkubis96/BioSRA/blob/main/fig/s8.bmp" alt="drawing" width="600" />
</p>


