### Código Abierto en Química Computacional
Dr. Marcos Rivera Almazo <a href="https://molecular-mar.github.io/"><img src="img/github.png" height=50px></a> <a href="https://www.researchgate.net/profile/Marcos-Rivera-Almazo"><img src="img/rglogo.png" height=50px></a><br>

Contacto: mrivera@izt.uam.mx

|||
|--|--|
|<img src="img/logo_uam2.png" height=140px)>|<img src="img/logoVGGbn2.png" height=140px)>|


### Versión en linea

<img src="img/qrCeua.png" height=300px>

https://molecular-mar.github.io/openChem_ceuami


## Contenido

* ### Código abierto
* ### Casos
  * ### Dinámica Molecular
  * ### Química Cuántica
  * ### Visualización


## Pero primero...


## CEUAMI: 20 años

<div class="r-stack">
<img class="fragment" src="img/ceuami/ceua1.jpeg" height="400">
<img class="fragment" src="img/ceuami/ceua3.jpeg" height="400">
<img class="fragment" src="img/ceuami/ceua2.jpeg" height="400">
<img class="fragment" src="img/ceuami/ceua4.jpeg" height="400">
<img class="fragment" src="img/ceuami/super1.jpeg" height="400">
</div>

---

## Código abierto
<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div class="column">                           

* Termino propuesto en los 90's. Software que cumpla con:
  * Acceso libre al código
  * Modificable
  * Redistribuible
  * Descentralizado

</div>
<div class="column">                           
  <img src="img/linux.gif" height="300px">
</div>
</div>


## Química Computacional

* Uso de herramientas computacionales para asistir en la resolución de problemas químicos
* Primeros usos, junto con las primeras computadoras digitales (40's)

EDSAC, Universidad de Cambridge (50's)

<img src="img/edsac3.jpg" height="200px">


* Programas más eficientes en los 70's (Gaussian)
* Inicios *abiertos*: códigos accesibles mediante el QCPE (tarjetas perforadas, diskets, cd, FTP).
* Favoreció el desarrollo: probar ideas, colaborar.

<img src="img/pople.webp" height="300px">

---

## Algunos ejemplos:


## Dinámica Molecular

* Simular el movimiento y comportamiento de moléculas.
* Efectos de fuerzas por molécula (distancias, ángulos) y entre ellas.
* Campos de fuerzas

<img src="img/membrane.gif" height="300px">


## Códigos:

* GROMACS: 1991, Groeningen, Holanda. Berendsen Group.
* Ampliamente usado para sistemas biológicos
* Ejecución en CPU/GPU.

<img src="img/gmx_logo_blue.png" height="300px">


<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div class="column">                           

* LAMMPS: 90's, Sandia Laboratory, EU. 
* Masivamente paralelizable (MPI, OpenMP, GPU)

</div>

<div class="column">                           

<img src="img/logo.gif" height="100px">

<img src="img/virus_bud.png" height="300px">
</div>

---

# Química cuántica

* Describimos el comportamiento de los electrones. Protagonistas en Química (enlaces).
* Descripción a nivel cuántico.
* Alta precisión, alto costo computacional.

<img src="img/water-trimer.gif" height="200px">


### Ejemplo: interacción Benceno-MOF
<!-- |||
|--|--|
|<img src="img/aimSc.png" height=330px> |<model-viewer bounds="tight" enable-pan src="mfmIn_bpath_New.glb" ar ar-modes="webxr scene-viewer quick-look" camera-controls environment-image="neutral" camera-orbit="0deg 90deg 2m" poster="img/poster.png" shadow-intensity="0" auto-rotate interaction-prompt=none></model-viewer>| -->

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div data-markdown class="column" style: "vertical-align: middle;">
<img src="img/aimSc.png" height=330px>
</div>
<div style="margin: 3em auto; display: flex; flex-direction: column; max-width: 400px;max-height: 330px; border-radius: 6px; box-shadow: 0 3px 10px rgba(0, 0, 0, 0.25); overflow: hidden">
        <model-viewer bounds="tight" 
 	        enable-pan src="models3D/mfmIn_bpath_New.glb"
	        camera-controls environment-image="neutral" 
            camera-orbit="-4.9deg 86.11deg 3.512m" field-of-view="25.77deg" ar ar-modes="scene-viewer webxr quick-look"
        	poster="img/poster.png" 
        	shadow-intensity="0" auto-rotate
            interaction-prompt=none>
        </model-viewer>
    </div>
</div>

<span class="attribution">Rivera-Almazo, M. et al. Isostructural MFM-300(Sc) and MFM-300(In): Adsorption Behavior to Determine Their Differences. J. Phys. Chem. C 300, (2022).</span>


## Algunos ejemplos

<img src="img/Nwhem.png" height=200px)> 

* NWChem: 1992, PNNL, EU.
* Diversos métodos: DFT, CC, MD.
* Escalable: amplio uso en supercómputo


* Otros ejemplos:
  * CP2K, Quantum ESPRESSO, SIESTA, Psi4, PySCF

* Para moléculas, sistemas periódicos (polímeros, superficies, cristales).

---

## Visualización

* Auxiliares para interpretrar/comunicar resultados de simulaciones/experimentos.

<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div data-markdown class="column" style: "vertical-align: middle;">

* Avogadro: 2007.
* Algunas capacidades:
  * Visualizar archivos *moleculares*
  * Construir/editar moléculas
  * Dinámica molecular básica
  * Auxiliar para otros programas.

</div>

<div class="column">

<img src="img/avog.png" height=300px)> 
</div>
</div>


<div style="-webkit-column-count: 2; -moz-column-count: 2; column-count: 2; -webkit-column-rule: 1px dotted #e0e0e0; -moz-column-rule: 1px dotted #e0e0e0; column-rule: 1px dotted #e0e0e0;">
<div data-markdown class="column" style: "vertical-align: middle;">

* Jmol: 2000's
  * Visualizar dinámicas
  * Animaciones
  * Basado en Java. Puede usarse en el navegador.
  * Lectura de una gran variedad de formatos

</div>

<div class="column">

<img src="img/jmol.png" height=200px)> 

</div>
</div>

---

## Beneficios del código abierto en QC

* Accesibilidad
* Plataformas para desarrollo
* Implementaciones tempranas
* Comunidad 


## ¿Cómo contribuir?

* GitHub
* GitLab
* Google Summer of Code


## ¡Gracias por la atención!
### ¿Preguntas?
### https://linktr.ee/malmazo

<img src="img/malmazoW.png" height=200px)> 

