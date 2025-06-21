# _Bayesian Learning and Monte-Carlo simulation_ final project

This repository contains the assignment (with the PDF describing all possible projects all relative
datasets), the dataset and main source code of the final project for the
[_Bayesian Learning and Monte-Carlo simulation_](https://onlineservices.polimi.it/manifesti/manifesti/controller/ManifestoPublic.do?EVN_DETTAGLIO_RIGA_MANIFESTO=evento&aa=2024&k_cf=225&k_corso_la=481&k_indir=T2I&codDescr=055283&lang=IT&semestre=2&idGruppo=5012&idRiga=310895) 
course.\
This project was developed in group (made up of 4) and represented the final examination of the aforementioned course.

## Description of the project
The detailed version of the assignment can be found under `assignment/Project2025.pdf` under
paragraph 3.6. It consists in modelling two time-series (US GDP and ICP) in order to make predictions
on its future values. In order to do this, a portion of each the time-series was to learn an
appropriate modelling, whereas the final part was used to evaluate predictive capabilities of the
learned model. Each time-series was modelled in several ways (MA(1), RA(n), ARMA(1, 1), ...) and 
appropriate _(mainly bayesian)_ metrics were used to evaluate them and perform model selection.\
A report describing the whole development process, intuitions and results can be found in this
repository.