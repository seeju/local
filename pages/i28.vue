<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 3 - Mobiliário e Equipamentos</h1>
    <h4>28. Sanitários, banheiros e vestiários - Mictório<br /><br /></h4>

    <div>
      <form action="/i29">
        <p>
          205. Permite área de aproximação frontal para pessoas com mobilidade
          reduzida (P.M.R.)?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          206. A válvula está instalada a uma altura de até 1,00 m do piso
          acabado, e tem preferencialmente sensor eletrônico, ou dispositivo
          equivalente ou fechamento automático?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          207. Existem barras de apoio laterais de no mínimo 0,70 m de
          comprimento e instaladas a 0,75cm do piso acabado?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <input type="submit" value="Próximo" />
      </form>
    </div>
  </div>
</template>