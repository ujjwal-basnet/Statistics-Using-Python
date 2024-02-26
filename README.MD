# Project Title
This is repo for learning Stastics using python for Machine learning 

## Table of Contents
[person's correlation
## Assumption of pearson's correlation 
1) Both Variables should be normally distributed 

2) There should be no significant outliesrs

3) Each variable should be continious 

4) Two variable should have linear relation ship ( draw scattter plot and see wetiher they have linear relation ship or not )

\documentclass{article}
\usepackage{xepersian}

\begin{document}
\title{ضریب همبستگی پیرسون}
\author{نام شما}
\maketitle

ضریب همبستگی پیرسون بین دو متغیر $X$ و $Y$ به صورت زیر تعریف می‌شود:

\begin{equation}
r_{XY} = \frac{\sum{(X_i - \bar{X})(Y_i - \bar{Y})}}{\sqrt{\sum{(X_i - \bar{X})^2}\sum{(Y_i - \bar{Y})^2}}}
\end{equation}

که در آن:
\begin{itemize}
    \item $r_{XY}$ ضریب همبستگی پیرسون بین $X$ و $Y$ است.
    \item $X_i$ و $Y_i$ مقادیر مشاهده شده از متغیرهای $X$ و $Y$ به ترتیب هستند.
    \item $\bar{X}$ و $\bar{Y}$ نشان دهنده میانگین متغیرهای $X$ و $Y$ هستند.
\end{itemize}

\end{document}
