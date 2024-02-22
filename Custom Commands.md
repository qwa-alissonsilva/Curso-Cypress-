# Custom Commands


Cypress vem com sua própria API para criar comandos personalizados e substituir comandos existentes. Os comandos integrados do Cypress usam a mesma API definida abaixo.

**SINTAXE**


Cypress.Commands.add(name, callbackFn)
Cypress.Commands.add(name, options, callbackFn)
Cypress.Commands.addAll(callbackObj)
Cypress.Commands.addAll(options, callbackObj)
Cypress.Commands.overwrite(name, callbackFn)


Cypress.Commands.add('login', (email, pw) => {})
Cypress.Commands.addAll({
  login(email, pw) {},
  visit(orig, url, options) {},
})