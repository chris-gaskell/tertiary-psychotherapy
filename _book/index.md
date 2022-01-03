--- 
title: "Effectiveness of Tertiary Care Outpatient Psychological Interventions; A Benchmarking Study"
author: "Chris Gaskell"
date: "2022-01-03"
output:
  bookdown:: pdf_book
  word_document: default
  pdf_document:
    fig_caption: true
    toc: false
    toc_depth: 1
fontsize: 12pt
indent: true
bibliography:
- BIB/book.bib
- BIB/packages.bib
- BIB/Empirical.bib
csl: apa.csl
classoption: openany
always_allow_html: yes
description: NA
documentclass: book
github-repo: rstudio/SPS
subparagraph: yes
header-includes:
- \AtBeginDocument{\let\maketitle\relax}
- \setlength{\parskip}{0pt}
- \usepackage{fancyhdr}
- \pagestyle{fancyplain}% <- use fancyplain instead fancy
- \fancyhf{}
- \fancyhead[R]{\thepage}
- \setlength{\headheight}{15pt}
- \renewcommand{\headrulewidth}{0pt}
- \usepackage{floatrow}
- \floatsetup{capposition=top}
- \usepackage{setspace}
- \usepackage{todonotes}
- \usepackage[export]{adjustbox}
- \usepackage{lscape} 
- \usepackage{lipsum}
- \usepackage{titlesec}
- \usepackage{xcolor}
- \usepackage{pdfpages}
- \usepackage{apacite}
- \usepackage{caption}
- \usepackage[labelfont=bf]{caption}
- \usepackage[labelsep=newline,singlelinecheck=false]{caption}
- \usepackage{amsmath}
- \usepackage{float}
- \usepackage{mathptmx}
- \titleclass{\part}{top}
- \setlength{\parindent}{4em}
- \usepackage{indentfirst}
- \usepackage{dpfloat}
- \maxdeadcycles=200
- \pagestyle{plain}
- \newcommand{\periodafter}[1]{#1.}
- \titleformat{\part}[display]
  {\centering\normalfont\Huge\bfseries}{\titlerule[0pt]\vspace{3pt}\titlerule[0pt]\vspace{3pt}\MakeUppercase{\partname} \thepart}{0pt}{\titlerule[0pt]\vspace{1pc}\huge\MakeUppercase}
- \titlespacing*{\part}{0pt}{0pt}{20pt}
- \titleformat{\chapter}[display]
  {\normalfont\huge\bfseries\filcenter}{\chaptertitlename\ \thechapter}{0pt}{\normalsize}
- \titlespacing*{\chapter}
  {0pt}{0pt plus 0pt minus 0pt}{0pt plus 0pt minus 0pt}
- \titleformat{\section}[display]
  {\normalfont\bfseries}{\sectiontitlename\ \thechapter}{10pt}{\normalsize}
- \titlespacing*{\section}
  {0pt}{0pt plus 0pt minus 0pt}{0pt plus 0pt minus 0pt}
- \titleformat{\subsection}[display]
  {\normalfont\bfseries\slshape}{\sectiontitlename\ \thechapter}{10pt}{\normalsize}
- \titlespacing*{\subsection}
  {0pt}{12pt plus 0pt minus 0pt}{0pt plus 0pt minus 0pt}
- \titleformat{\subsubsection}[runin]
  {\normalfont\bfseries}{\sectiontitlename\ \thechapter}{\hspace{2em}}{\periodafter}
- \titlespacing*{\subsubsection}{\parindent}{1ex}{1em}
- \usepackage{caption}
- \captionsetup[table]{textfont={it}, labelfont={bf}, singlelinecheck=false, labelsep=newline}
- \AtBeginDocument{\renewcommand
  {\chaptername}{}}
- \captionsetup{justification=raggedright,singlelinecheck=false}
- \captionsetup{font={stretch=1.5}}


link-citations: yes
biblio-style: apalike
site: bookdown::bookdown_site
geometry: "left=4cm, right=2cm, top=2cm, bottom=2cm"
---
\frontmatter

\frontmatter
\setcounter{page}{17}





\part{Empirical Project}
\begin{center}
\linespread{1.2}\huge {\bfseries Effectiveness of Tertiary Care Outpatient Psychological Interventions; A Benchmarking Study }\\[1cm]
\linespread{1}
\includegraphics[width=5cm]{images/tuoslogogrey.png}\\[.8cm]
{\Large Chris Gaskell}\\[.8cm]
{\large \emph{Supervisors:}}\\[0.4cm] 
\large Dr. Stephen C. Kellett\\[0.4cm]
\large Dr. Mel Simmonds-Buckley\\[0.4cm]
\large Dr. Jaime Delgadillo\\[0.4cm]

\end{center}
\pagebreak


\onehalfspacing

```{=tex}
\setcounter{tocdepth}{1}
\tableofcontents
\fontsize{12}{10}
\doublespacing
```

\addcontentsline{toc}{section}{List of Tables}
\listoftables

\addcontentsline{toc}{section}{List of Figures}
\listoffigures

\pagebreak


\doublespacing


```{=tex}
\pagebreak
\hspace{0pt}
\vfill
\begin{center}
\large \emph{This page is intentionally left blank}
\vfill
\end{center}
\hspace{0pt}
\pagebreak
```
```{=tex}
\pagebreak
\doublespacing
```





\mainmatter

\setcounter{page}{63}


# Abstract {-#Abstract}

\noindent 
**Background:** When patients are not responsive to primary care interventions then they can be referred to further tiers of the stepped-care system (i.e. to secondary/tertiary care). However, evidence regarding the effectiveness of tertiary care psychological therapy is very scarce.
**Objectives:** To explore the effectiveness of psychological interventions delivered in a tertiary care psychotherapy service using equivalent service benchmarks.
**Methods:** A retrospective analysis of psychotherapy outcomes on the Outcome Questionnaire-45 (OQ-45) over a
10
year period
(2011-2021)
in a tertiary care psychotherapy service based in the United Kingdom. The service delivered three interventions; cognitive behavioural, cognitive analytic and psychoanalytic. Rates of effectiveness were calculated at the service level and also for different treatment modalities using pre-post treatment effect sizes (Cohen’s d) and clinical recovery indices. Trajectories of change were examined using growth curve modeling.
**Results:**
Baseline distress on the OQ-45 was higher than comparative norms 
(M = 102.57,
SD =  22.79,
N = 364).
The average number of sessions was 48.68
 (SD = 42.14,
 range = 5-335).
There was a small pre-post effect small effect  small effect
(*d* = 0.46, 95% CI = 0.37-0.55) that was lower than available OQ-45 and tertiary benchmarks.
Mean change between different treatments was comparable (overlap between confidence intervals).
The recovery rate was 10.16% and 29.95% made a reliable improvement.
Change in OQ-45 score over time was best explained using a nonlinear (cubic) time trend.
**Conclusions:**
Patients receiving tertiary care psychotherapy in the present sample had higher baselines distress and outcomes were suppressed accordingly. Suggestions are made regarding the role of tertiary care psychotherapy in mental health services.  
\newline
**Keywords:** 'Psychotherapy', 'effectiveness', 'tertiary-care', 'growth curves.'
\newline
**Practitioner Points:**

- There are a sub-sample of tertiary care patients who do not respond to treatment. For these patients there is limited evidence for extending therapy beyond 100 sessions.
- Outcomes monitoring within supervision may provide a suitable means of determining when treatment should end.
- There was limited evidence to favor one psychological modality over another; however evidence was promising for CAT. 
