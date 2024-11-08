# DM-DBT-Combined-Method-For-Breast-Cancer-Classification
This repo is for paper "A Digital Mammograhpy and Digital Breast Tomosynthesis Combined Method for Breast Cancer Classification", and we will open source the datasets and annotations used in our article.

![image](https://github.com/user-attachments/assets/678a49b4-329b-499c-be01-76d171000a84)

\begin{table}[t]
\centering
\caption{Results of Different Breast Cancer Classification Models and Inputs}
\label{tab:cls_results} 
\resizebox{0.5\textwidth}{!}{ 
\begin{tabular}{c c c c c c c }
\hline
 &Total& Mass & Cal. & FA. & AD. & Mass\&Cal  \\ \hline
ResNet50\cite{he2016deep}& 0.813 & 0.839   & 0.766  & 0.489 & 0.517   & 0.969   \\
DensNet121\cite{huang2017densely} &0.808& 0.812   & 0.732 & 0.652  & 0.433  & 0.932  \\
ViT-T\cite{dosovitskiy2020image} &0.833 & 0.827  & 0.835 & 0.516  & 0.481  & 0.956   \\
Swin-T\cite{liu2021swin} &0.845 & 0.839  & \textbf{\textcolor{red}{0.837}} & 0.522  & 0.483  & \textbf{\textcolor{red}{0.992}}   \\
\hline
Full DBT &0.785 & 0.804  & \textbf{\textcolor{blue}{0.532}} & \textbf{\textcolor{red}{0.621}}  & \textbf{\textcolor{red}{0.650}}  & 0.873   \\
DBT Dynamic Image\cite{liang2019joint} & 0.814 & 0.831 & \textbf{\textcolor{blue}{0.562}} & 0.513  &  0.464 & 0.982   \\
DBT Selected Frame & 0.822 & 0.853  & \textbf{\textcolor{blue}{0.572}} & 0.461  & 0.483  & 0.972   \\
\hline。
DM+Full DBT &0.845 & 0.854  & 0.760 & 0.527  & 0.550  & 0.964   \\
DM+DBT Dynamic Image\cite{liang2019joint} & 0.851 & 0.841  & 0.723 & 0.513  & 0.564  & 0.982   \\
DM+DBT Selected Frame & \textbf{\textcolor{red}{0.868}} & \textbf{\textcolor{red}{0.861}}  & 0.784 & 0.604  & 0.600  & 0.989   \\

\hline
\end{tabular}
}
\end{table}
