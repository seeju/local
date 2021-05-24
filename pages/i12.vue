<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 1 - Circulação e Acessos</h1>
    <h4>12. Rota de fuga<br /><br /></h4>

    <div>
      <form action="/i13">
        <p>
          94. Existe trajeto contínuo, protegido, a ser percorrido pelo usuário,
          em caso de sinistro de qualquer ponto da edificação, até atingir uma
          área segura?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          95. As rotas de fuga e as saídas de emergência estão sinalizadas, para
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
          96. Se as rotas de fuga incorporarem escadas de emergência, possuem
          uma área de resgate de 0,80 m x 1,20 m, ventilada e fora do fluxo de
          circulação, para cada 500 pessoas?
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