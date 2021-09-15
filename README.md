# An OCR Benchmarking Experiment
  
This repository holds replication materials for the manuscript ["OCR with Tesseract, Amazon Textract, and Google Document AI: A Benchmarking Experiment"](https://osf.io/preprints/socarxiv/6zfvs). It contains:

- The .RMD file of the manuscript. It should knit if you clone the repository and work within `noisy-ocr-benchmark.Rproj`.
- 51,304 .TXT files with the text output from all the OCR processing requests.
- .CSV files with data for all the figures.

The image test materials reside in a separate Zenodo repository as the ["Noisy OCR Dataset"](https://zenodo.org/record/5068735) (NOD).

Paper abstract: 

>Optical Character Recognition (OCR) can open up understudied historical
documents to computational analysis, but the accuracy of OCR software
varies. This article reports a benchmarking experiment comparing the
performance of Tesseract, Amazon Textract, and Google Document AI on
images of English and Arabic text. English-language book scans (n=322)
and Arabic-language article scans (n=100) were replicated 43 times with
different types of artificial noise for a corpus of 18,568 documents, generating
51,304 process requests. Document AI delivered the best results, and the
server-based processors (Textract and Document AI) performed substantially
better than Tesseract, especially on noisy documents. Accuracy for English
was considerably higher than for Arabic. Specifying the relative performance
of three leading OCR products and the differential effects of commonly
found noise types can help scholars identify better OCR solutions for
their research needs. The test materials have been preserved in the openly
available “Noisy OCR Dataset” (NOD) for reuse in future benchmarking studies.

Core results: 
\
\
![](images/fig4.png)
