<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 3 - Mobiliário e Equipamentos</h1>
    <h4>33. Vegetação<br /><br /></h4>

    <div>
      <form action="/i34">
        <p>
          227. Ramos, raízes, plantas entouceiradas, galhos de arbustos e de
          árvores) e suas proteções (muretas, grades ou desníveis) não
          interferem nas rotas acessíveis e áreas de circulação de pedestres?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          228. A vegetação nas áreas adjacentes às rotas acessíveis e áreas de
          circulação de pedestres não tem espinhos, raízes que prejudiquem o
          pavimento ou toxicidade?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          229. Vasos de plantas estão fora de rotas acessíveis, rampas, portas,
          ou qualquer área que comprometa a circulação?
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