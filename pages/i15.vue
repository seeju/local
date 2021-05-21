<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 2 - Sinalização</h1>
    <h4>15. Estacionamentos<br /><br /></h4>

    <div>
      <form action="/i16">
        <p>
          116. Existe rota acessível interligando as vagas do estacionamento até
          o interior da edificação?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          117. Existe alarme visual e sonoro instalados em saídas de garagens e
          de estacionamentos nos passeios públicos?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          118. Existe demarcação e sinalização vertical e horizontal de vagas
          reservadas para veículos que conduzam ou sejam conduzidos por pessoas
          idosas ou com deficiência?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          119. Possui faixa de circulação livre de obstáculos (1.20m) localizada
          ao lado da vaga de estacionamento, para a pessoa com deficiência?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          120. A sinalização vertical das vagas reservadas não interfere com as
          áreas de acesso ao veículo e com a circulação de pedestres?
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