<template>
  <div>
    <Header />
    <NavBarQuestions />
    <h1>Seção 3 - Mobiliário e Equipamentos</h1>
    <h4>29. Sanitários, banheiros e vestiários - Acessórios<br /><br /></h4>

    <div>
      <form action="/i30">
        <p>
          208. Os acessórios - porta-objeto, cabides, saboneteiras e toalheiros
          – estão instalados dentro da faixa de alcance acessível (entre 0,80 e
          1,20 metros), sem atrapalhar o acesso à barra de apoio?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          209. Os espelhos estão instalados entre 0,50 e 1,80 metros do piso
          acabado?
        </p>
        <input type="radio" id="yes" name="option" />
        <label for="yes">Sim</label><br />
        <input type="radio" id="no" name="option" />
        <label for="no">Não</label><br />
        <input type="radio" id="na" name="option" />
        <label for="na">N/A</label><br /><br />

        <p>
          210. Existem cabides instalados junto a lavatórios, boxes de chuveiro,
          bancos de vestiários, trocadores e boxes de bacia sanitária, e estão a
          uma altura entre 0,80 m e 1,20 m do piso acabado?
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