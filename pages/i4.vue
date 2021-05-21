<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 1 - Circulação e Acessos</h1>
    <h4>4. Estacionamento<br /><br /></h4>

    <div>
      <form action="/i5">
        <p>
          24. Possui 2% das vagas destinadas a pessoas com deficiência e
          mobilidade reduzida com, no mínimo, uma vaga e 5% das vagas destinadas
          a idosos com, no mínimo, uma vaga para cada grupo?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          25. A vaga está localizada próxima ao acesso ou de algum polo de
          atração e evitam circulação e passagem de pedestres entre os veículos?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          26. O piso do estacionamento é antiderrapante, nivelado e sem
          inclinação?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          27. A superfície de varredura do portão de acesso a garagens manuais
          ou de acionamento automático não invade a faixa livre de circulação de
          pedestre?
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