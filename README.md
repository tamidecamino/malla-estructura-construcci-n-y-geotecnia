# malla-estructura-construcci-n-y-geotecnia
# 🎓 MALLA ING MENCION ESTRUCTURA, CONSTRUCCIÓN Y GEOTECNIA UCH


```mermaid
graph TD

%% PRIMER SEMESTRE
CALC1["Introducción al Cálculo"]
ALG1["Álgebra"]
FISMOD1["Física Moderna"]
BIOING["Aplicaciones de la Biología a la Ingeniería y Ciencia"]
DESAFIOS["Desafíos de Innovación en Ingeniería y Ciencias"]
HERR["Herramientas Computacionales"]

%% SEGUNDO SEMESTRE
FISMOD2["Introducción a la Física Moderna"]
CALC2["Cálculo Diferencial e Integral"]
ALG2["Álgebra Lineal"]
PROG1["Introducción a la Programación"]
PROY["Proyectos de Innovación en Ingeniería y Ciencias"]
FORM1["Formación Integral"]

%% TERCER SEMESTRE
METEXP["Métodos Experimentales"]
MEC["Mecánica"]
CALCVAR["Cálculo en Varias Variables"]
EDO["Ecuaciones Diferenciales Ordinarias"]
QUIM["Química"]

%% CUARTO SEMESTRE
ELEC["Electromagnetismo"]
CALCAV["Cálculo Avanzado y Aplicado"]
ECO["Economía"]
MODULO["Módulo Interdisciplinario"]
TERM["Termodinámica"]

%% QUINTO SEMESTRE
PROBA["Probabilidades y Estadísticas"]
OPT["Optimización"]
MECAS["Mecánica Estructural"]
FLU["Mecánica de Fluidos"]
ANST["Análisis de Sistemas de Transporte"]

%% SEXTO SEMESTRE
NUM["Cálculo Numérico para Ingeniería Civil"]
HID["Ingeniería Hidráulica"]
ESTRUC["Ingeniería Estructural"]
AMBI["Ingeniería Ambiental"]
TOPO["Topografía"]
TALL1["Taller de Práctica Profesional I"]

%% SÉPTIMO SEMESTRE
EVAL["Evaluación de Proyectos"]
GEOT["Ingeniería Geotecnia"]
DIN["Dinámica de Estructuras"]
MAT["Ingeniería de Materiales"]
PTOPO["Práctica I Topografía"]
ELEC1["Electivo"]

%% OCTAVO SEMESTRE
CONST["Construcción"]
PLAN["Planificación y Gestión de Proyectos"]
DISIS["Diseño Sísmico de Estructuras"]
HORM["Diseño de Hormigón Armado"]
FORM2["Formación Integral"]
TALL2["Taller de Práctica Profesional II"]

%% NOVENO SEMESTRE
DISGEO["Diseño Geotécnico"]
DISACERO["Diseño de Estructuras de Acero"]
PHORM["Proyecto de Hormigón Armado"]
PCONST["Proyecto de Construcción"]
ELEC2["Electivo"]
PRACT2["Práctica Profesional II"]

%% DÉCIMO SEMESTRE
HABIL1["Trabajo de Habilitación Profesional I"]
SUELOS["Mecánica de Suelos Avanzada"]
PACERO["Proyecto de Estructuras de Acero"]
ESTRUCAV["Ingeniería Estructural Avanzada"]
ESP1["Electivo Especialidad 1"]
ESP2["Electivo Especialidad 2"]

%% ÚLTIMO SEMESTRE
HABIL2["Trabajo de Habilitación Profesional II"]
FORMESP["Formación Integral de Especialidad"]
PRACT3["Práctica Profesional III"]

%% REQUISITOS
CALC1 --> CALC2
ALG1 --> ALG2
CALC1 --> FISMOD2
ALG1 --> FISMOD2
FISMOD1 --> FISMOD2
BIOING --> FISMOD2
DESAFIOS --> PROY
DESAFIOS --> FORM1
CALC2 --> CALCVAR
CALC2 --> EDO
ALG2 --> CALCVAR
ALG2 --> EDO
CALC2 --> METEXP
FISMOD2 --> METEXP
ALG2 --> MEC
CALC2 --> MEC
CALCVAR --> ELEC
EDO --> ELEC
MEC --> ELEC
CALCVAR --> CALCAV
EDO --> CALCAV
MODULO --> TERM
MEC --> TERM
CALCVAR --> TERM
PROY --> MODULO
METEXP --> MODULO
FORM1 --> MODULO
CALCAV --> PROBA
CALCAV --> OPT
MEC --> MECAS
CALCAV --> FLU
TERM --> FLU
METEXP --> FLU
ECO --> ANST
CALCAV --> TOPO
METEXP --> TOPO
PROBA --> NUM
MECAS --> ESTRUC
FLU --> AMBI
FLU --> HID
TOPO --> PTOPO
TALL1 --> PTOPO
MECAS --> PTOPO
FLU --> PTOPO
ANST --> PTOPO
ECO --> EVAL
PROBA --> EVAL
MECAS --> GEOT
FLU --> GEOT
NUM --> DIN
ESTRUC --> DIN
NUM --> MAT
MECAS --> MAT
TOPO --> CONST
EVAL --> CONST
EVAL --> PLAN
GEOT --> DISIS
ESTRUC --> DISIS
ESTRUC --> HORM
MAT --> HORM
DISIS --> PHORM
HORM --> PHORM
CONST --> PCONST
MAT --> PCONST
GEOT --> DISGEO
ESTRUC --> DISACERO
MAT --> DISACERO
DISIS --> PACERO
DISACERO --> PACERO
DISIS --> ESTRUCAV
HABIL1 --> HABIL2
DISGEO --> SUELOS
DISACERO --> PACERO
DISIS --> PACERO
FORM2 --> FORMESP
TALL2 --> PRACT2
PRACT2 --> PRACT3

