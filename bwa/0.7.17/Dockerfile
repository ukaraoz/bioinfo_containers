################## BASE IMAGE ######################
FROM ulaskaraoz/bioinfocontainers_base:1

################## METADATA ######################
LABEL base_image="bioinfocontainers_base:1"
LABEL version="1"
LABEL software="bwa"
LABEL software.version="0.7.17"
LABEL about.summary="Burrow-Wheeler Aligner for pairwise alignment between DNA sequences"
LABEL about.home="http://bio-bwa.sourceforge.net/"
LABEL about.documentation="http://bio-bwa.sourceforge.net/"
LABEL about.license_file="http://bio-bwa.sourceforge.net/"
LABEL about.license="SPDX:GPL-3.0"
LABEL extra.identifiers.biotools="bwa"
LABEL about.tags="Genomics"

################## MAINTAINER ######################
MAINTAINER Ulas Karaoz <ukaraoz@lbl.gov>

################## INSTALLATION ######################

RUN conda install bwa=0.7.17

WORKDIR /data/

CMD ["bwa"]

