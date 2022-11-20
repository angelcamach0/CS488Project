# CS488Project

\documentclass[12pt,journal,compsoc]{IEEEtran}

% *** CITATION PACKAGES ***
%
\ifCLASSOPTIONcompsoc
  % IEEE Computer Society needs nocompress option
\else
  % normal IEEE
  % \usepackage{cite}
\fi

\usepackage[final]{pdfpages}
\usepackage{listings}
\usepackage{xcolor}
\usepackage[utf8]{inputenc}
\usepackage[letterpaper, portrait, margin=1in]{geometry}

% *** GRAPHICS RELATED PACKAGES ***
%
\ifCLASSINFOpdf
  \usepackage[pdftex]{graphicx}
  % declare the path(s) where your graphic files are
  % and their extensions so you won't have to specify these with
  % every instance of \includegraphics
  % \DeclareGraphicsExtensions{.pdf,.jpeg,.png}
\else

\fi



% correct bad hyphenation here
\hyphenation{op-tical net-works semi-conduc-tor}


\begin{document}
%
% paper title
% can use linebreaks \\ within to get better formatting as desired
\title{\LARGE \bf
"Report" Project Stage V}
% \title{Report_Dataming}
\author{
        Angel ~Camacho†~\IEEEmembership{Student,~NMSU,}
        Mathew ~Groover†~\IEEEmembership{Student,~NMSU,}
        Courtney ~Mueller,~\IEEEmembership{Student,~NMSU,}% <-this % stops a space

% note need leading \protect in front of \\ to get a newline within \thanks as
% \\ is fragile and will error, could use \hfil\break instead.
\IEEEcompsocitemizethanks{
    \IEEEcompsocthanksitem A. Camacho is a student in the Computer Science department of New Mexico State University. \protect\\
    E-mail: angelcam@nmsu.edu
    \IEEEcompsocthanksitem M. Groover is a student in the Computer Science department of New Mexico State University. \protect\\
    E-mail: mgroov@nmsu.edu
    \IEEEcompsocthanksitem C. Mueller is a student in the Computer Science department of New Mexico State University. \protect\\
    E-mail: cmuel10@nmsu.edu
    

}% <-this % stops a space
\thanks{Manuscript received November 15, 2022; revision is scheduled for late November 2022.}}

\markboth{\textit{CS 488/508 DATA MINING I} at New Mexico State University under Dr. Huiping Cao}%
{Shell \MakeLowercase{\textit{et al.}}: Bare Demo of IEEEtran.cls for Computer Society Journals}

\markboth{\textit{CS 488/508 DATA MINING I} at New Mexico State University under Dr. Huiping Cao}%
{Shell \MakeLowercase{\textit{et al.}}: Bare Demo of IEEEtran.cls for Computer Society Journals}

\IEEEcompsoctitleabstractindextext{%
\begin{abstract}
%\boldmath
This report details the preliminary motivation and description of the "-----------------," assignment in  \textit{CCS 488/508 DATA MINING I} at New Mexico State University.
\end{abstract}

\begin{IEEEkeywords}
Computer Society, IEEEtran, journal, \LaTeX, Date Mining I, Scikit learn.
\end{IEEEkeywords}}
\maketitle
\IEEEdisplaynotcompsoctitleabstractindextext

\IEEEpeerreviewmaketitle
\section{Motivation}
\IEEEPARstart{O}{v}er the years, technology has adapted and become more included in our society. Video games being one of the things that have advanced technologically over the years and have increased in popularity. With the COVID pandemic over the last few years increasing the amount of time people spend inside, it accelerated the popularity of video games as most social activity came with a large risk. We seek to help address that new trend amongst both novice and veteran games by using data mining techniques to create a video game recommendation system. This system will attempt to analyze a player's preference in their favored genre of video game and recommend them new ones based off of the data we are able to gather. We are basing the idea of our project off of an anime recommendation system that was found while researching online. We thought it would be an enjoyable and rewarding experience as we not only work to practice our coding skills using data mining techniques but also get to implement something all of our group members have in common / enjoy doing in our free time. 
% You must have at least 2 lines in the paragraph with the drop letter
% (should never be an issue)


\hfill NMSU
 
\hfill November 1th, 2022

\subsection{INTRODUCTION}
 This is an interesting real world project application as we are working with preferences and advertisement and recommendations to propose suggested games for a dedicated audience (gamers). This is applicable in the real world in numerous ways.  For example, video game designers could use the data from our product to analyze what type / genre of video games their consumers are playing in relation to their product. In the case of data mining techniques, there are several techniques that we can use in order to understand how to better derive the useful information from an agglomeration of video game preferences. Some of the data mining techniques we foresee being beneficial to our research and overall project would be prediction and classification. Prediction being used to recommend video game titles, genres etc. based off data collected from the user. Classification would be used to classify and group each of the video game titles present in the system by genre. Individually each of our team members actively play video games and our knowledge of that will help understand how best to achieve reasonable results that can impact our user base.

\IEEEpubidadjcol

\subsection{      \t PROPOSED SOLUTION}
For majority of our data, we will be pulling information about majority of well-known video games from the internet and be implementing that data into our system. Video games have been around for a long time and have only become more and more complex and advanced as time went on. Due to this, there are thousands of video game titles out there. We have recognized this may cause issues when trying to account for all games in our system. For that reason, we have created potential adaptations in our project including only account for triple A games rather than all games including titles from indie development companies. The main motivation for our project is based on the fact that all of our group members have a shared passion when it comes to gaming and playing video games in our free time. We all agreed it would be more enjoyable to be involved with a project that involved something we were all actively interested in.

\subsection{      \t RESULTS }


\subsection{      \t FUTURE IMPROVEMENTS }

\IEEEpubidadjcol
% \subsection{      \t REFERENCES}
% Jonathan Bouchet. 2017. Pokemon battles. (October 2017). Retrieved February 23, 2022 from https://www.kaggle.com/jonathanbouchet/pokemon-battles/report

\begin{thebibliography}{1}

\bibitem{1}
S.~someone, \emph{-----------}, (MONTH YYYY).\hskip 1em plus
  0.5em minus 0.4em\relax Retrieved February 23, 2022 from https://www.kaggle.com/-----------/------------/--------

\end{thebibliography}

\newpage

\subsection{      \t Graphs}

\ifCLASSOPTIONcompsoc
  % The Computer Society usually uses the plural form
  \section*{Acknowledgments}
\else
  % regular IEEE prefers the singular form
  \section*{Acknowledgment}
\fi
Thank you to Dr. Huiping Cao, ----------------, and -of NMSU, as well as:  IEEE and Overleaf and the \LaTeX \;community for making documentation and presets readily available to us during this paper. 


\ifCLASSOPTIONcaptionsoff
  \newpage
\fi

\end{document}
