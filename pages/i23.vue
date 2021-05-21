<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 2 - Sinalização</h1>
    <h4>23. Alarmes<br /><br /></h4>

    <div>
      <form action="/i24">
        <p>
          175. Existem alarmes visuais e sonoros instalados em quartos,
          banheiros e sanitários em locais de hospedagem, em instituições de
          idosos e em hospitais?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          176. Existem alarmes visuais e sonoros instalados em sanitários
          acessíveis, boxes, cabines e vestiários isolados?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          177. Os alarmes nos espaços confinados estão ao alcance manual (40 cm
          do piso)?
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