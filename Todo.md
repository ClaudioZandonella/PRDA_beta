## Todo list

- [ ] Calcolare Cohen's d for Welch test.
https://www.datanovia.com/en/lessons/t-test-effect-size-using-cohens-d-measure/ riporta:
$$d = \frac{M_x - M_y}{\sqrt{\frac{(Var_1 + Var_2)}{2}}}$$
Non capisco se Var si intende la varianza campionaria o la stima della varianza.
Vedere anche https://stats.stackexchange.com/questions/210352/do-cohens-d-and-hedges-g-apply-to-the-welch-t-test
https://arxiv.org/pdf/1901.09581.pdf

- [ ] Controllare anche come è calcolato il Cohen's d nel caso del paired t-test.
https://www.datanovia.com/en/lessons/t-test-effect-size-using-cohens-d-measure/ riporta:
$$d = \frac{nx-2}{nx-1.25} \times \frac{mx}{sd(x)}$$

- [ ] Come calcolare il valore critico di Cohen's d dato il valre della statistica test.
https://www.bwgriffin.com/gsu/courses/edur9131/content/Effect_Sizes_pdf5.pdf riporta delle formule da controllare.
https://www.frontiersin.org/articles/10.3389/fpsyg.2013.00863/full altre formule (meglio). Ci vanno oppure no le correzioni?
  - One.sampled t-test $d = t / \sqrt{n}$
  - Paired t-test $d = \frac{t}{\sqrt{n}}+ \mu$
  - Two sampled t.test $d =  t \sqrt{\frac{n_x+n_y}{n_x n_y}} + \mu$
  - Welch t-test $d =  t \sqrt{\frac{2}{n_x n_y}\frac{n_x * var_y+n_y*var_x}{var_x + var_y}} + \mu$ (noi facciamo in realtà il smpling con entrampe le pop variance = 1 quindi dovrebbe essere uguale al t-test?)
  
  
- [ ] Troncare le distribuzioni basta eliminare i valori non voluti e continuare il sampling?

- [ ] In prospective quando utilizzo una distribuzione per definire gli effetti considero raggiunto il livello di potenza considerando la media delle potenze. Potrebbe essere meglio considerare la mediana o la media va bene?





