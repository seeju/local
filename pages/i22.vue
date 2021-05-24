<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 2 - Sinalização</h1>
    <h4>22. Sinalização de emergência<br /><br /></h4>

    <div>
      <form action="/i23">
        <p>
          171. Existe sinalização de emergência que direcione o usuário para
          saídas de emergência ou rota de fuga?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          172. As rotas de fuga e as saídas de emergência são sinalizadas para
          localização, advertência e instruções, com informações visuais,
          sonoras e táteis?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          173. Existe demarcação e sinalização de área de resgate para pessoas
          com deficiência? (NBR 13434)
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          174. Existe sinalização tátil, visual e/ou sonora, informando o número
          do pavimento nas escadas que interligam os diversos pavimentos,
          inclusive nas de emergência, junto às portas corta-fogo?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <input type="submit" value="Avançar" />
      </form>
    </div>
  </div>
</template>