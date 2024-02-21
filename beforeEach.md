# beforeEach()

beforeEach(() => {
  // root-level hook
  // runs before every test block
})

Antes de cada teste realiza esta execução

beforeEach(function(){
        cy.visit('./src/index.html')
    })


Realiza a visita ao index sempre antes de realizar os testes

