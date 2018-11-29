# EulerCromer-Method

Método de Euler-Cromer
---------------

Como ejemplo, podemos resolver numéricamente la ecuación diferencial:

<math xmlns="http://www.w3.org/1998/Math/MathML">
  <mfrac>
    <mrow>
      <msup>
        <mi>d</mi>
        <mn>2</mn>
      </msup>
      <mi>x</mi>
    </mrow>
    <mrow>
      <mi>d</mi>
      <msup>
        <mi>t</mi>
        <mn>2</mn>
      </msup>
    </mrow>
  </mfrac>
  <mo>=</mo>
  <mo>&#x2212;<!-- − --></mo>
  <mi>k</mi>
  <mi>x</mi>
</math>

### Procedimiento:

La constante, los valores iniciales de $x$, $xd$ y $xdd$, el paso de tiempo $dt$ y la hora final $tf$ se establecen. Se crean tres listas vacías (t_list, x_list, y xd_list) para contener los resultados. Los valores iniciales de $t$, $x,$ y $xd$ se anexan a estas listas.
