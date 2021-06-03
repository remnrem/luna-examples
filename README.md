# Luna applications

This repository is designed to illustrate some applications of the
[Luna](http://zzz.bwh.harvard.edu/luna/) software package to
polysomnography datasets, with an emphasis on the sleep EEG during
childhood.

Examples using Luna

 - Dataset preparation (EDFs and annotations)
   - [PATS](1-preparation/pats/README.md) : preparing [Pediatric Adenotonsillectomy Trial for Snoring](https://patstrial.org) data
   - [NCH-SDB](1-preparation/nch-sdb/README.md) : preparing [Nationwide Childrens Hospital Sleep DataBank](https://sleepdata.org/datasets/nchsdb) data, available at [National Sleep Research Resource](http://sleepdata.org)
   - [Sleep-EDF](1-preparation/sleep-edf/README.md) : preparing [Sleep-EDF](https://physionet.org/content/sleep-edfx/1.0.0/) data, available at [PhysioNet](https://physionet.org)

 - Macro-architecture
   - [Hypnograms](2-macro/hypnograms/README.md) : basic summaries of manual sleep staging
   - [SOAP](2-macro/soap/README.md) : model-based assessments of manual staging
   - [SUDS](2-macro/suds/README.md) : automated sleep staging

 - Micro-architecture
   - [Spectral power](3-micro/power/README.md) : (Welch, multitaper spectrograms)
   - [Principal Spectral Components](3-micro/psc/README.md) : multi-channel intra- and inter-cohort PSC analysis 
   - [Spindles & slow oscillations](3-micro/spindles/README.md) : occurrence, morphology, coupling and propagation
   - [Connectivity](3-micro-connectivity/README.md) : coherence, phase slope index & Granger prediction during REM & NREM

 - Association analysis
   - [Development](4-association/development/README.md) : changes in the sleep EEG across childhood 
   - [Cross-domain](4-association/cross-domain/README.md) : analyses across sleep EEG domains

---
