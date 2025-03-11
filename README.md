# **How do the Stars Live?**
This project was developed as the final project for UFRGS's "Astrofísica B" course, that focuses on stellar evolution and structure.

Here we will analyze a star's life cycle, from its birth, understanding how it behaves at each stage on its evolution based on its physical properties, until its death. All made in python.


The dataset was provided by professor Alejandra Romero, and the analyzed star has the following characteristics:


*    $Mass=0.95M_\odot$
*   $Metalicity \ (Z) = 0.004$

> Initially, the graphs in this project were created with Matplotlib. However, I chose to use it as a foundation to train my skills with Plotly, a Python library for building interactive graphs. This allowed me to optimize the project and enhance my knowledge of Plotly.

---

### **Understanding the properties in each column:**
1. **Log L**: logarithm of luminosity in solar luminosity units $log(L/L_ \odot)$, where $L_ \odot=3.846 \cdot 10^{26} \ ergs/s$.
2. **Log Teff**: logarithm of effective temperature in K.
3. **Tc**: logarithm of the core temperature in millions of K.
4. **Roc**: logarithm of central density in $g/cm^3$.
5. **log(age/Myr)**: logarithm of age in millions of years.
6. **Massa**: total mass in mass solar units ($M_ \odot = 1.9891 \cdot 1033 \ g$ ).
7. **Lpp**: logarithm of luminosity produced by hydrogen fusion through the p-p cycle, in units of solar luminosity.
8. **Lcno**: logarithm of luminosity produced by hydrogen fusion through the CNO cycle, in units of solar luminosity.
9. **LHe**: logarithm of luminosity produced by the helium fusion, in units os solar luminosity.
10. **Hcen**: central hydrogen abundance.
11. **Hecen**: central helium abundance.
12. **C12cen**: central abundance of carbon 12.
13. **O16cen**: central abundance of oxygen 16.

---

Sources:\
https://www.ucolick.org/~woosley/ay112-14/texts/pols11.pdf \
https://www.if.ufrgs.br/~fatima/ead/estrelas.htm \
http://astro.if.ufrgs.br/estrelas/estrelas.htm \
http://astro.if.ufrgs.br/estrelas/node2.htm \
http://astro.if.ufrgs.br/estrelas/node14.htm 

