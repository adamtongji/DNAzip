README
=============
#DNAzip -- Compressing sequencing data

usage:  usage: DNAzip <-f file> <-d> [-o output prefix] [options]
    Example: DNAzip -f ecoli.fasta -t fasta -o ecoli
             DNAzip -f sample.fastq -t fastq -o sample




###optional arguments:
  -h, --help            show this help message and exit
  -v, --verbose         increase ouput verbosity.
  -q, --quiet           No output log file.
  -t FILE_TYPE, --type FILE_TYPE
                        fasta or fastq
  -f INPUT_FILE, --file INPUT_FILE
                        input filename
  -o OUTPUT_FILE, --output OUTPUT_FILE
                        Output filename prefix(Default:noname)
  -d, --decode          extract from the compressed file
  -w OUT_WIDTH, --width OUT_WIDTH
                        Define width of outputfile. Default:0(no limits)
  -l LEVEL, --level LEVEL
                        Compression level. Default:6
  --version             show program's version number and exit
