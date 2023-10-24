# minicurso-gee


![image](https://github.com/LambdaGeo/minicurso-gee/assets/86836/4f2ad158-a135-4efc-81e2-1137d05b9b0f)


![image](https://github.com/LambdaGeo/minicurso-gee/assets/86836/d42227ab-65dc-488a-af85-941e5fab355f)



\begin{itemize}
    \item POINT(-44.29777178028425 -2.5313470294034044)
    \item LINESTRING(-44.300075363904284 -2.543551794770009,-44.315009903699206 -2.5610438856080293,-44.3201597450078 -2.5655883603806258,-44.33234770277147 -2.5655883603806258,-44.338527512341784 -2.564387934650711)
    \item POLYGON ((-44.29622682789167 -2.5235440348039972,-44.30652651050886 -2.526973928317386,-44.30300745228132 -2.5364918353169004,-44.29777178028425 -2.54360878308611,-44.28627046802839 -2.5348626489898383,-44.29622682789167 -2.5235440348039972))
\end{itemize}



\begin{lstlisting}[language=javascript]
var image = ee.Image('LANDSAT/LC08/C01/T1/LC08_220062_20190504');
\end{lstlisting}

Esse identificador é criado com base em diversas características, o nome e a versão do satélite, que neste caso é Landsat 8. As informações seguintes, \texttt{C01} e \texttt{T1} representa o número da coleção e o nível de processamento. Os valores 200 e 062 referem a localização desta imagem, que esta no \textit{path} 200 e \textit{row} 062. Por fim, 20190504 refere à data da imagem no formato ``AAAAMMDD'', que representa 04 de maio de 2019
