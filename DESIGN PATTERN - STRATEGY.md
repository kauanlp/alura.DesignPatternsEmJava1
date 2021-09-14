# DESIGN PATTERN - STRATEGY #

A ideia é que sempre que eu tenho um algoritmo, validação, calculo, etc. Ela varia de acordo com o parâmetro eu tenho um código cheio de if/else ou switch case. para eliminar esse problema usamos o strategy, em vez dessa informação ser uma string/enum ela se transforma em uma classe e nela a gente usa polimorfismo (interface), deixando o código mais coeso, simples, flexível e mais fácil de se reutilizar.

Este padrão pode ser utilizado quando há diversos possíveis algoritmos para uma ação (como calcular imposto, por exemplo). Nele, nós separamos cada um dos possíveis algoritmos em classes separadas.