\documentclass{extarticle} % Note the extarticle document class
% Using the geometry package with a small
% page size to create the article graphic
\usepackage[paperheight=6in,
   paperwidth=5in,
   top=10mm,
   bottom=20mm,
   left=10mm,
   right=10mm]{geometry}
\usepackage{moresize}
\begin{document}

{The size of this text is \verb=\normalsize= but now it is \tiny tiny
until we make it \small small or \ssmall ``ssmall'' via the moresize package.
Let's revert to \normalsize normal size then {\ttfamily \scriptsize use monospaced
\verb=\scriptsize= text in a group} then back to normal. Now, try 
\verb=\large= \large text then {\sffamily \Large \verb=\Large= sans serif text}
 and finally {\HUGE really big (\verb=\HUGE=) and {\bfseries  bold} text}
\end{document}
