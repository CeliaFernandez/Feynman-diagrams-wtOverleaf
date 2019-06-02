# Feynman-diagrams-wtOverleaf

Repositorio para describir como generar diagramas de Feynman utilizando el paquete *feynmp-auto*, disponible en Overleaf.

Para cargar los ejemplos en Overleaf:

<ul>
  <li> Descargar el paquete ZIP del código (*clone or download*)</li>
  <li> Cargar el paquete en Overleaf. Al hacerlo, es importante mantener la estructura o redefinirla de acuerdo al modelo de texto.</li>
<ul>

## Tutorial: Modelo de *Long-lived Higgs Boson to scalar bosons with a four leptons final state*

El primer ejemplo se encuentra en el fichero *Examples.tex*. El diagrama se define en un entorno dentro del primer entorno *figure*.

# Definición del frame del diagrama:

`\begin{fmffile}{FeynmanH2XX24l}
\begin{fmfgraph*}(180,90) %\fmfpen{thick}`
  
