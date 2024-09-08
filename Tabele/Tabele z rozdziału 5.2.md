<h2>Tabela 1: Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Fertility</h2>
| Algorytm                              | Dokładność     | Pole pod krzywą ROC | F1           |
|---------------------------------------|----------------|---------------------|--------------|
| K-FVSNN - 10% usuniętych etykiet      | 0.863 (0.046)  | 0.567 (0.113)       | 0.807 (0.060)|
| K-FVSNN - 30% usuniętych etykiet      | 0.867 (0.042)  | 0.511 (0.111)       | 0.808 (0.058)|
| K-FVSNN - 50% usuniętych etykiet      | 0.870 (0.040)  | 0.563 (0.119)       | 0.810 (0.057)|
| K-FVSNN - 70% usuniętych etykiet      | 0.870 (0.040)  | 0.547 (0.097)       | 0.810 (0.057)|
| K-FVSNN - 90% usuniętych etykiet      | 0.870 (0.040)  | 0.509 (0.067)       | 0.810 (0.057)|
| K-EVSNN - 10% usuniętych etykiet      | 0.863 (0.046)  | 0.555 (0.116)       | 0.807 (0.060)|
| K-EVSNN - 30% usuniętych etykiet      | 0.867 (0.042)  | 0.519 (0.107)       | 0.808 (0.058)|
| K-EVSNN - 50% usuniętych etykiet      | 0.870 (0.040)  | 0.527 (0.059)       | 0.810 (0.057)|
| K-EVSNN - 70% usuniętych etykiet      | 0.870 (0.040)  | 0.582 (0.079)       | 0.810 (0.057)|
| K-EVSNN - 90% usuniętych etykiet      | 0.870 (0.040)  | 0.508 (0.063)       | 0.810 (0.057)|
| KNN                                   | 0.847 (0.061)  | 0.722 (0.159)       | 0.844 (0.061)|
    
<h2>Tabela 2: Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Fertility</h2>
| Algorytm                              | Dokładność     | Pole pod krzywą ROC | F1           |
|---------------------------------------|----------------|---------------------|--------------|
| K-FVSNN - 10% usuniętych etykiet      | 0.870 (0.040)  | 0.586 (0.168)       | 0.810 (0.057)|
| K-FVSNN - 30% usuniętych etykiet      | 0.870 (0.040)  | 0.569 (0.144)       | 0.810 (0.057)|
| K-FVSNN - 50% usuniętych etykiet      | 0.870 (0.040)  | 0.601 (0.177)       | 0.810 (0.057)|
| K-FVSNN - 70% usuniętych etykiet      | 0.863 (0.040)  | 0.495 (0.230)       | 0.807 (0.055)|
| K-FVSNN - 90% usuniętych etykiet      | 0.867 (0.042)  | 0.561 (0.166)       | 0.808 (0.058)|
| K-EVSNN - 10% usuniętych etykiet      | 0.870 (0.040)  | 0.574 (0.166)       | 0.810 (0.057)|
| K-EVSNN - 30% usuniętych etykiet      | 0.870 (0.040)  | 0.571 (0.156)       | 0.810 (0.057)|
| K-EVSNN - 50% usuniętych etykiet      | 0.870 (0.040)  | 0.589 (0.194)       | 0.810 (0.057)|
| K-EVSNN - 70% usuniętych etykiet      | 0.870 (0.040)  | 0.520 (0.226)       | 0.810 (0.057)|
| K-EVSNN - 90% usuniętych etykiet      | 0.870 (0.040)  | 0.525 (0.178)       | 0.810 (0.057)|
| Regresja Logistyczna                  | 0.854 (0.071)  | 0.807 (0.089)       | 0.837 (0.092)|

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Fertility, średnia (odchylenie standardowe).}
\label{XGBBaseFert}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.847 (0.061)$ & $0.657 (0.148)$ & $0.835 (0.059)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.847 (0.057)$ & $0.694 (0.158)$ & $0.832 (0.049)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.843 (0.016)$ & $0.601 (0.192)$ & $0.801 (0.036)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.857 (0.022)$ & $0.473 (0.137)$ & $0.803 (0.047)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.870 (0.040)$ & $0.515 (0.184)$ & $0.810 (0.057)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.843 (0.057)$ & $0.654 (0.153)$ & $0.832 (0.055)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.847 (0.028)$ & $0.683 (0.199)$ & $0.830 (0.034)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.843 (0.016)$ & $0.688 (0.144)$ & $0.796 (0.038)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.857 (0.022)$ & $0.449 (0.161)$ & $0.803 (0.047)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.870 (0.040)$ & $0.455 (0.201)$ & $0.810 (0.057)$ \\ \hline
XGBoost & $0.847 (0.061)$ & $0.722 (0.159)$ & $0.844 (0.0.61)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Raisin, średnia (odchylenie standardowe).}
\label{KNNBaseRaisin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.825 (0.022)$ & $0.877 (0.017)$ & $0.825 (0.022)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.824 (0.023)$ & $0.872 (0.020)$ & $0.823 (0.023)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.812 (0.020)$ & $0.865 (0.016)$ & $0.812 (0.020)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.800 (0.029)$ & $0.837 (0.034)$ & $0.799 (0.030)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.787 (0.031)$ & $0.810 (0.031)$ & $0.785 (0.033)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.825 (0.023)$ & $0.877 (0.018)$ & $0.825 (0.023)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.822 (0.024)$ & $0.872 (0.021)$ & $0.822 (0.024)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.814 (0.022)$ & $0.864 (0.016)$ & $0.813 (0.022)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.801 (0.040)$ & $0.843 (0.030)$ & $0.801 (0.040)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.787 (0.042)$ & $0.812 (0.033)$ & $0.785 (0.045)$ \\ \hline
KNN & $0.832 (0.025)$ & $0.884 (0.021)$ & $0.832 (0.025)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Raisin, średnia (odchylenie standardowe).}
\label{LRBaseRaisin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.861 (0.022)$ & $0.922 (0.016)$ & $0.861 (0.022)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.856 (0.020)$ & $0.921 (0.016)$ & $0.855 (0.020)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.848 (0.017)$ & $0.915 (0.019)$ & $0.848 (0.017)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.846 (0.023)$ & $0.915 (0.023)$ & $0.846 (0.023)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.846 (0.026)$ & $0.918 (0.024)$ & $0.845 (0.026)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.861 (0.025)$ & $0.923 (0.016)$ & $0.861 (0.025)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.855 (0.021)$ & $0.919 (0.017)$ & $0.855 (0.022)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.853 (0.020)$ & $0.916 (0.017)$ & $0.852 (0.021)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.845 (0.024)$ & $0.913 (0.022)$ & $0.845 (0.024)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.842 (0.035)$ & $0.918 (0.023)$ & $0.842 (0.035)$ \\ \hline
Regresja Logistyczna & $0.857 (0.022)$ & $0.921 (0.016)$ & $0.857 (0.022)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Raisin, średnia (odchylenie standardowe).}
\label{XGBBaseRaisin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.838 (0.021)$ & $0.903 (0.016)$ & $0.838 (0.021)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.841 (0.022)$ & $0.901 (0.017)$ & $0.841 (0.022)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.838 (0.018)$ & $0.894 (0.017)$ & $0.838 (0.018)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.829 (0.022)$ & $0.885 (0.023)$ & $0.829 (0.022)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.830 (0.026)$ & $0.874 (0.026)$ & $0.829 (0.026)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.836 (0.016)$ & $0.905 (0.014)$ & $0.836 (0.017)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.841 (0.019)$ & $0.903 (0.016)$ & $0.841 (0.019)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.840 (0.017)$ & $0.896 (0.017)$ & $0.840 (0.017)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.833 (0.016)$ & $0.886 (0.017)$ & $0.832 (0.017)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.832 (0.021)$ & $0.874 (0.025)$ & $0.831 (0.021)$ \\ \hline
XGBoost & $0.841 (0.019)$ & $0.912 (0.017)$ & $0.841 (0.019)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Wisconsin, średnia (odchylenie standardowe).}
\label{KNNBaseWisconsin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.934 (0.014)$ & $0.963 (0.016)$ & $0.933 (0.014)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.936 (0.016)$ & $0.960 (0.016)$ & $0.936 (0.016)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.931 (0.019)$ & $0.950 (0.021)$ & $0.930 (0.020)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.919 (0.022)$ & $0.935 (0.026)$ & $0.917 (0.024)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.900 (0.035)$ & $0.895 (0.042)$ & $0.897 (0.038)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.933 (0.014)$ & $0.963 (0.016)$ & $ 0.932 (0.014)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.935 (0.016)$ & $0.959 (0.016)$ & $0.935 (0.016)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.930 (0.017)$ & $0.951 (0.022)$ & $0.930 (0.018)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.912 (0.023)$ & $0.934 (0.035)$ & $0.910 (0.025)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.864 (0.064)$ & $0.868 (0.072)$ & $0.852 (0.077)$ \\ \hline
KNN & $0.935 (0.015)$ & $0.963 (0.016)$ & $0.934 (0.015)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Wisconsin, średnia (odchylenie standardowe).}
\label{LRBaseWisconsin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.954 (0.015)$ & $0.993 (0.004)$ & $0.954 (0.015)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.956 (0.013)$ & $0.992 (0.005)$ & $0.955 (0.013)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.954 (0.014)$ & $0.990 (0.006)$ & $0.954 (0.015)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.948 (0.014)$ & $0.989 (0.005)$ & $0.948 (0.014)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.905 (0.040)$ & $0.943 (0.043)$ & $0.904 (0.041)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.955 (0.015)$ & $0.993 (0.004)$ & $0.955 (0.015)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.954 (0.015)$ & $0.992 (0.005)$ & $0.954 (0.015)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.952 (0.015)$ & $0.989 (0.007)$ & $0.952 (0.015)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.944 (0.022)$ & $0.986 (0.006)$ & $0.943 (0.022)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.908 (0.042)$ & $0.943 (0.056)$ & $0.906 (0.044)$ \\ \hline
Regresja Logistyczna & $0.954 (0.016)$ & $0.921 (0.016)$ & $0.954 (0.016)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Wisconsin, średnia (odchylenie standardowe).}
\label{XGBBaseWisconsin}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.965 (0.014)$ & $0.993 (0.005)$ & $0.965 (0.014)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.955 (0.016)$ & $0.991 (0.005)$ & $0.955 (0.016)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.950 (0.017)$ & $0.991 (0.006)$ & $0.950 (0.017)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.940 (0.022)$ & $0.987 (0.006)$ & $0.939 (0.022)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.908 (0.034)$ & $0.967 (0.026)$ & $0.907 (0.035)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.964 (0.014)$ & $0.993 (0.005)$ & $0.964 (0.014)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.957 (0.017)$ & $0.992 (0.005)$ & $0.957 (0.017)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.949 (0.022)$ & $0.991 (0.005)$ & $0.948 (0.022)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.936 (0.015)$ & $0.986 (0.007)$ & $0.936 (0.016)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.905 (0.026)$ & $0.965 (0.029)$ & $0.904 (0.026)$ \\ \hline
XGBoost & $0.967 (0.014)$ & $0.994 (0.005)$ & $0.967 (0.014)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Credit Approval, średnia (odchylenie standardowe).}
\label{KNNBaseCred}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.685 (0.029)$ & $0.724 (0.020)$ & $0.682 (0.030)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.675 (0.022)$ & $0.712 (0.019)$ & $0.673 (0.022)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.669 (0.028)$ & $0.698 (0.020)$ & $0.666 (0.028)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.661 (0.039)$ & $0.680 (0.048)$ & $0.658 (0.040)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.625 (0.046)$ & $0.646 (0.054)$ & $0.623 (0.046)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.684 (0.027)$ & $0.722 (0.022)$ & $0.682 (0.027)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.679 (0.021)$ & $0.704 (0.024)$ & $0.677 (0.023)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.669 (0.027)$ & $0.686 (0.029)$ & $0.665 (0.029)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.660 (0.050)$ & $0.677 (0.042)$ & $0.650 (0.060)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.600 (0.067)$ & $0.603 (0.076)$ & $0.581 (0.072)$ \\ \hline
KNN & $0.690 (0.027)$ & $0.728 (0.025) $ & $0.687 (0.027)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Credit Approval, średnia (odchylenie standardowe).}
\label{LRBaseCred}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.871 (0.022)$ & $0.935 (0.020)$ & $0.871 (0.022)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.864 (0.022)$ & $0.930 (0.022)$ & $0.865 (0.022)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.873 (0.021)$ & $0.930 (0.018)$ & $0.874 (0.020)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.855 (0.024)$ & $0.916 (0.017)$ & $0.855 (0.024)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.794 (0.042)$ & $0.856 (0.046)$ & $0.793 (0.042)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.869 (0.024)$ & $0.934 (0.020)$ & $0.869 (0.024)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.867 (0.024)$ & $0.929 (0.022)$ & $0.867 (0.024)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.862 (0.024)$ & $0.927 (0.022)$ & $0.862 (0.023)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.857 (0.021)$ & $0.915 (0.018)$ & $0.858 (0.021)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.796 (0.041)$ & $0.855 (0.056)$ & $0.795 (0.041)$ \\ \hline
Regresja Logistyczna & $0.872 (0.020)$ & $0.933 (0.020)$ & $0.873 (0.019)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Credit Approval, średnia (odchylenie standardowe).}
\label{XGBBaseCred}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.870 (0.022)$ & $0.929 (0.020)$ & $0.870 (0.022)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.866 (0.017)$ & $0.928 (0.019)$ & $0.867 (0.018)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.862 (0.024)$ & $0.926 (0.019)$ & $0.862 (0.023)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.855 (0.019)$ & $0.917 (0.018)$ & $0.855 (0.019)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.851 (0.037)$ & $0.898 (0.036)$ & $0.851 (0.036)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.869 (0.019)$ & $0.927 (0.020)$ & $0.869 (0.019)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.867 (0.016)$ & $0.926 (0.021)$ & $0.867 (0.016)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.866 (0.024)$ & $0.928 (0.018)$ & $0.866 (0.024)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.848 (0.017)$ & $0.912 (0.020)$ & $0.849 (0.016)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.844 (0.025)$ & $0.897 (0.025)$ & $0.844 (0.025)$ \\ \hline
XGBoost & $0.871 (0.027)$ & $0.931 (0.019)$ & $0.872 (0.027)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Statlog (German), średnia (odchylenie standardowe).}
\label{KNNBaseStatlog}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.694 (0.024)$ & $0.640 (0.033)$ & $0.671 (0.026)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.687 (0.022)$ & $0.626 (0.031)$ & $0.654 (0.025)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.679 (0.025)$ & $0.601 (0.026)$ & $0.643 (0.030)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.676 (0.027)$ & $0.570 (0.032)$ & $0.627 (0.031)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.669 (0.029)$ & $0.525 (0.036)$ & $0.613 (0.029)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.688 (0.022)$ & $0.634 (0.033)$ & $0.662 (0.026)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.685 (0.024)$ & $0.615 (0.030)$ & $0.652 (0.025)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.682 (0.023)$ & $0.593 (0.036)$ & $0.642 (0.031)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.677 (0.028)$ & $0.554 (0.021)$ & $0.618 (0.026)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.687 (0.019)$ & $0.507 (0.026)$ & $0.593 (0.026)$ \\ \hline
KNN & $0.690 (0.022)$ & $0.639 (0.029)$ & $0.667 (0.025)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Statlog (German), średnia (odchylenie standardowe).}
\label{LRBaseStatlog}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.774 (0.017)$ & $0.797 (0.018)$ & $0.763 (0.019)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.763 (0.016)$ & $0.789 (0.024)$ & $0.751 (0.019)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.756 (0.024)$ & $0.786 (0.024)$ & $0.743 (0.030)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.742 (0.021)$ & $0.771 (0.029)$ & $0.727 (0.032)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.721 (0.015)$ & $0.709 (0.056)$ & $0.699 (0.018)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.769 (0.018)$ & $0.798 (0.017)$ & $0.759 (0.019)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.761 (0.018)$ & $0.789 (0.024)$ & $0.749 (0.022)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.763 (0.018)$ & $0.789 (0.022)$ & $0.751 (0.022)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.743 (0.020)$ & $0.771 (0.027)$ & $0.731 (0.026)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.724 (0.024)$ & $0.712 (0.045)$ & $0.707 (0.029)$ \\ \hline
Regresja Logistyczna & $0.766 (0.021)$ & $0.799 (0.017)$ & $0.755 (0.022)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Statlog (German), średnia (odchylenie standardowe).}
\label{XGBBaseStatlog}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.759 (0.017)$ & $0.776 (0.021)$ & $0.753 (0.018)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.752 (0.008)$ & $0.760 (0.018)$ & $0.742 (0.009)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.738 (0.013)$ & $0.753 (0.022)$ & $0.727 (0.016)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.727 (0.023)$ & $0.732 (0.018)$ & $0.709 (0.034)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.688 (0.028)$ & $0.663 (0.052)$ & $0.664 (0.037)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.756 (0.016)$ & $0.777 (0.020)$ & $0.748 (0.018)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.749 (0.014)$ & $0.763 (0.022)$ & $0.741 (0.017)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.744 (0.025)$ & $0.754 (0.021)$ & $0.731 (0.031)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.722 (0.027)$ & $0.732 (0.025)$ & $0.704 (0.034)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.687 (0.034)$ & $0.667 (0.065)$ & $0.665 (0.045)$ \\ \hline
XGBoost & $0.760 (0.024)$ & $0.776 (0.026)$ & $0.753 (0.026)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Heart Failure Clinical Record, średnia (odchylenie standardowe).}
\label{KNNBaseHFCR}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.636 (0.053)$ & $0.487 (0.060)$ & $0.602 (0.046)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.613 (0.057)$ & $0.483 (0.079)$ & $0.584 (0.057)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.622 (0.051)$ & $0.501 (0.082)$ & $0.588 (0.049)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.609 (0.041)$ & $0.488 (0.072)$ & $0.575 (0.038)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.597 (0.041)$ & $0.483 (0.071)$ & $0.567 (0.048)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.641 (0.048)$ & $0.475 (0.074)$ & $0.604 (0.044)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.607 (0.056)$ & $0.470 (0.078)$ & $0.573 (0.052)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.609 (0.049)$ & $0.485 (0.070)$ & $0.573 (0.051)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.653 (0.041)$ & $0.509 (0.056)$ & $0.586 (0.043)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.681 (0.043)$ & $0.499 (0.051)$ & $0.575 (0.048)$ \\ \hline
KNN & $0.637 (0.055)$ & $0.481 (0.066)$ & $0.604 (0.052)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Heart Failure Clinical Record, średnia (odchylenie standardowe).}
\label{LRBaseHFCR}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.810 (0.029)$ & $0.846 (0.022)$ & $0.807 (0.030)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.821 (0.026)$ & $0.844 (0.028)$ & $0.817 (0.027)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.830 (0.040)$ & $0.842 (0.035)$ & $0.825 (0.042)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.812 (0.025)$ & $0.830 (0.043)$ & $0.801 (0.028)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.763 (0.044)$ & $0.753 (0.105)$ & $0.749 (0.059)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.811 (0.027)$ & $0.849 (0.019)$ & $0.808 (0.028)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.827 (0.037)$ & $0.846 (0.032)$ & $0.823 (0.038)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.822 (0.036)$ & $0.844 (0.032)$ & $0.819 (0.035)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.789 (0.025)$ & $0.821 (0.035)$ & $0.780 (0.028)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.771 (0.054)$ & $0.778 (0.081)$ & $0.765 (0.058)$ \\ \hline
Regresja Logistyczna & $0.817 (0.017)$ & $0.841 (0.023)$ & $0.813 (0.019)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Heart Failure Clinical Record, średnia (odchylenie standardowe).}
\label{XGBBaseHFCR}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.818 (0.032)$ & $0.888 (0.025)$ & $0.818 (0.031)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.821 (0.024)$ & $0.886 (0.024)$ & $0.820 (0.025)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.822 (0.029)$ & $0.874 (0.041)$ & $0.823 (0.029)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.809 (0.042)$ & $0.846 (0.047)$ & $0.807 (0.040)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.742 (0.094)$ & $0.777 (0.109)$ & $0.729 (0.093)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.814 (0.036)$ & $0.887 (0.027)$ & $0.815 (0.036)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.824 (0.035)$ & $0.884 (0.027)$ & $0.825 (0.035)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.807 (0.030)$ & $0.863 (0.041)$ & $0.808 (0.027)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.809 (0.031)$ & $0.860 (0.035)$ & $0.809 (0.029)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.762 (0.088)$ & $0.781 (0.103)$ & $0.756 (0.092)$ \\ \hline
XGBoost & $0.818 (0.026)$ & $0.896 (0.025)$ & $0.818 (0.025)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Ionosphere, średnia (odchylenie standardowe).}
\label{KNNBaseIono}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.838 (0.035)$ & $0.896 (0.031)$ & $0.824 (0.041)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.837 (0.033)$ & $0.888 (0.034)$ & $0.824 (0.038)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.814 (0.070)$ & $0.865 (0.041)$ & $0.788 (0.105)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.759 (0.093)$ & $0.817 (0.051)$ & $0.698 (0.153)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.675 (0.065)$ & $0.649 (0.099)$ & $0.556 (0.105)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.839 (0.036)$ & $0.896 (0.031)$ & $0.825 (0.042)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.838 (0.032)$ & $0.888 (0.034)$ & $0.825 (0.036)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.816 (0.070)$ & $0.866 (0.041)$ & $0.790 (0.105)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.781 (0.100)$ & $0.825 (0.059)$ & $0.732 (0.159)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.700 (0.090)$ & $0.658 (0.112)$ & $0.601 (0.149)$ \\ \hline
KNN & $0.837 (0.036)$ & $0.902 (0.027)$ & $0.823 (0.043)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Ionosphere, średnia (odchylenie standardowe).}
\label{LRBaseIono}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.863 (0.030)$ & $0.880 (0.035)$ & $0.855 (0.032)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.864 (0.026)$ & $0.868 (0.042)$ & $0.855 (0.028)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.852 (0.028)$ & $0.856 (0.058)$ & $0.840 (0.032)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.827 (0.036)$ & $0.842 (0.043)$ & $0.809 (0.044)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.727 (0.051)$ & $0.765 (0.071)$ & $0.657 (0.073)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.866 (0.034)$ & $0.881 (0.035)$ & $0.859 (0.037)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.868 (0.024)$ & $0.864 (0.045)$ & $0.860 (0.026)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.859 (0.020)$ & $0.860 (0.055)$ & $0.850 (0.023)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.830 (0.034)$ & $0.842 (0.047)$ & $0.812 (0.043)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.745 (0.054)$ & $0.776 (0.065)$ & $0.685 (0.082)$ \\ \hline
Regresja Logistyczna & $0.870 (0.032)$ & $0.894 (0.030)$ & $0.863 (0.034)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Ionosphere, średnia (odchylenie standardowe).}
\label{XGBBaseIono}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.918 (0.031)$ & $0.967 (0.017)$ & $0.916 (0.032)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.906 (0.032)$ & $0.959 (0.021)$ & $0.904 (0.033)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.904 (0.032)$ & $0.955 (0.019)$ & $0.902 (0.032)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.874 (0.023)$ & $0.929 (0.018)$ & $0.870 (0.024)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.810 (0.053)$ & $0.871 (0.065)$ & $0.801 (0.049)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.914 (0.034)$ & $0.969 (0.016)$ & $0.913 (0.035)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.906 (0.036)$ & $0.954 (0.022)$ & $0.904 (0.036)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.902 (0.033)$ & $0.951 (0.020)$ & $0.901 (0.033)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.882 (0.027)$ & $0.940 (0.025)$ & $0.879 (0.028)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.799 (0.060)$ & $0.854 (0.068)$ & $0.783 (0.070)$ \\ \hline
XGBoost & $0.918 (0.031)$ & $0.967 (0.016)$ & $0.917 (0.032)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Hepatitis, średnia (odchylenie standardowe).}
\label{KNNBaseHepatitis}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.821 (0.071)$ & $0.639 (0.141)$ & $0.767 (0.101)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.842 (0.078)$ & $0.627 (0.167)$ & $0.781 (0.110)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.630 (0.160)$ & $0.782 (0.106)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.638 (0.136)$ & $0.782 (0.106)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.622 (0.186)$ & $0.777 (0.103)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.833 (0.079)$ & $0.643 (0.139)$ & $0.775 (0.108)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.842 (0.081)$ & $0.615 (0.161)$ & $0.775 (0.106)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.599 (0.159)$ & $0.777 (0.103)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.586 (0.151)$ & $0.777 (0.103)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.503 (0.058)$ & $0.777 (0.103)$ \\ \hline
KNN & $0.829 (0.072)$ & $0.674 (0.119)$ & $0.778 (0.105)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Hepatitis, średnia (odchylenie standardowe).}
\label{LRBaseHepatitis}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.846 (0.079)$ & $0.759 (0.172)$ & $0.833 (0.095)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.846 (0.079)$ & $0.751 (0.223)$ & $0.831 (0.099)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.829 (0.095)$ & $0.808 (0.132)$ & $0.819 (0.105)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.733 (0.151)$ & $0.621 (0.194)$ & $0.741 (0.147)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.754 (0.158)$ & $0.668 (0.221)$ & $0.749 (0.131)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.850 (0.081)$ & $0.750 (0.172)$ & $0.836 (0.098)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.846 (0.088)$ & $0.768 (0.195)$ & $0.829 (0.109)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.842 (0.111)$ & $0.786 (0.149)$ & $0.829 (0.121)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.746 (0.156)$ & $0.644 (0.206)$ & $0.750 (0.150)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.746 (0.138)$ & $0.612 (0.212)$ & $0.747 (0.119)$ \\ \hline
Regresja Logistyczna & $0.854 (0.071)$ & $0.807 (0.089)$ & $0.837 (0.092)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Hepatitis, średnia (odchylenie standardowe).}
\label{XGBBaseHepatitis}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.854 (0.060)$ & $0.822 (0.110)$ & $0.844 (0.080)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.838 (0.084)$ & $0.824 (0.088) $ & $0.822 (0.108)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.842 (0.061)$ & $0.779 (0.128)$ & $0.810 (0.099)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.846 (0.086)$ & $0.834 (0.095)$ & $0.808 (0.123)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.760 (0.242)$ & $0.777 (0.103)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.838 (0.077)$ & $0.832 (0.110)$ & $0.831 (0.088)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.801 (0.127)$ & $0.836 (0.084)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.842 (0.073)$ & $0.726 (0.218)$ & $0.808 (0.118)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.842 (0.078)$ & $0.664 (0.206)$ & $0.798 (0.118)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.846 (0.074)$ & $0.641 (0.235)$ & $0.777 (0.103)$ \\ \hline
XGBoost & $0.854 (0.091)$ & $0.872 (0.084)$ & $0.846 (0.100)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu KNN dla zbioru Chronic Kidney Disease, średnia (odchylenie standardowe).}
\label{KNNBaseCKD}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.731 (0.042)$ & $0.701 (0.069)$ & $0.695 (0.052)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.715 (0.040)$ & $0.705 (0.048)$ & $0.673 (0.053)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.703 (0.044)$ & $0.684 (0.057)$ & $0.663 (0.061)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.669 (0.051)$ & $0.648 (0.060)$ & $0.627 (0.065)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.649 (0.058)$ & $0.615 (0.076)$ & $0.576 (0.101)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.728 (0.048)$ & $0.701 (0.069)$ & $0.694 (0.057)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.711 (0.038)$ & $0.701 (0.052)$ & $0.672 (0.052)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.698 (0.044)$ & $0.692 (0.055)$ & $0.655 (0.053)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.677 (0.044)$ & $0.655 (0.066)$ & $0.622 (0.069)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.636 (0.053)$ & $0.591 (0.087)$ & $0.530 (0.102)$ \\ \hline
KNN & $0.736 (0.037)$ & $0.709 (0.062)$ & $0.702 (0.049)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z regresji logistycznej dla zbioru Chronic Kidney Disease, średnia (odchylenie standardowe).}
\label{LRBaseCKD}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.863 (0.030)$ & $0.880 (0.035)$ & $0.957 (0.024)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.864 (0.026)$ & $0.868 (0.042)$ & $0.954 (0.042)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.852 (0.028)$ & $0.856 (0.058)$ & $0.927 (0.043)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.827 (0.036)$ & $0.842 (0.043)$ & $0.930 (0.031)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.727 (0.051)$ & $0.765 (0.071)$ & $0.836 (0.090)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.866 (0.034)$ & $0.881 (0.035)$ & $0.962 (0.024)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.868 (0.024)$ & $0.864 (0.045)$ & $0.954 (0.036)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.859 (0.020)$ & $0.860 (0.055)$ & $0.936 (0.031)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.830 (0.034)$ & $0.842 (0.047)$ & $0.935 (0.029)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.745 (0.054)$ & $0.776 (0.065)$ & $0.842 (0.078)$ \\ \hline
Regresja Logistyczna & $0.959 (0.024)$ & $0.994 (0.007)$ & $0.959 (0.024)$ \\ \hline
\end{tabular}
\end{table}

\begin{table}
\caption{Wyniki dla algorytmów korzystających z modelu XGB dla zbioru Chronic Kidney Disease, średnia (odchylenie standardowe).}
\label{XGBBaseCKD}
\centering
\begin{tabular}{|c|c|c|c|}
\hline
Algorytm & Dokładność & Pole pod krzywą ROC & F1 \\ \hline
K-FVSNN - $10\%$ usuniętych etykiet & $0.957 (0.023)$ & $0.992 (0.009)$ & $0.916 (0.032)$ \\ \hline
K-FVSNN - $30\%$ usuniętych etykiet & $0.954 (0.042)$ & $0.987 (0.019)$ & $0.904 (0.033)$ \\ \hline
K-FVSNN - $50\%$ usuniętych etykiet & $0.928 (0.042)$ & $0.974 (0.019)$ & $0.902 (0.032)$ \\ \hline
K-FVSNN - $70\%$ usuniętych etykiet & $0.931 (0.031)$ & $0.965 (0.036)$ & $0.870 (0.024)$ \\ \hline
K-FVSNN - $90\%$ usuniętych etykiet & $0.962 (0.023)$ & $0.887 (0.113)$ & $0.801 (0.049)$ \\ \hline
K-EVSNN - $10\%$ usuniętych etykiet & $0.954 (0.036)$ & $0.992 (0.010)$ & $0.913 (0.035)$ \\ \hline
K-EVSNN - $30\%$ usuniętych etykiet & $0.936 (0.031)$ & $0.986 (0.020)$ & $0.904 (0.036)$ \\ \hline
K-EVSNN - $50\%$ usuniętych etykiet & $0.902 (0.033)$ & $0.973 (0.026)$ & $0.901 (0.033)$ \\ \hline
K-EVSNN - $70\%$ usuniętych etykiet & $0.936 (0.028)$ & $0.971 (0.031)$ & $0.879 (0.028)$ \\ \hline
K-EVSNN - $90\%$ usuniętych etykiet & $0.851 (0.070)$ & $0.872 (0.120)$ & $0.783 (0.070)$ \\ \hline
XGBoost & $0.987 (0.015)$ & $1.000 (0.000)$ & $0.987 (0.015)$ \\ \hline
\end{tabular}
\end{table}
