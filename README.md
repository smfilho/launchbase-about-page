<h1 align="center">
    <img alt="Launchbase" src="https://storage.googleapis.com/golden-wind/bootcamp-launchbase/logo.png" width="400px" />
</h1>

<blockquote align="center">“Sua única limitação é você mesmo!”</blockquote>

<p align="center">

  <a href="https://rocketseat.com.br">
    <img alt="Made by Rocketseat" src="https://img.shields.io/badge/made%20by-Rocketseat-%23F8952D">
  </a>

  <a href="LICENSE" >
    <img alt="License" src="https://img.shields.io/badge/license-MIT-%23F8952D">
  </a>

</p>


## :rocket: Sobre o desafio
- Criar um arquivo html que contenha um [favicon](favicon.ico) e um header com 3 links: Comunidade, Email e Telefone.
- A partir do arquivo do desafio 2-1, adicionar um novo link no header chamado Sobre. Essa página deverá mostrar informações referentes a Rocketseat.
- A partir do arquivo do desafio 2.2, adicionar no header um link chamado Conteúdos. Essa página deve conter um grid onde devem ser mostrados os 3 principais cursos da Rocketseat: Starter, Launchbase e GoStack. Ao clicar em um dos cursos, deve ser aberta uma modal onde um iframe irá carregar as informações do curso selecionado.

### Informações da página
##### 2.1
O favicon é o ícone que aparece na aba do navegador. O arquivo está disponível com o nome favicon.ico. Para utilizá-lo é necessário importá-lo com a tag link no html. ser dada a dica de utilizar a tag link na head do html.

```html
<link rel="icon" href="favicon.ico" type="image/x-icon" />
```
- `Comunidade`: Link que deve apontar para o convite da comunidade aberta da rocketseat `(https://discordapp.com/invite/gCRAFhc)`

- `Email`: Link que deve chamar o comando de enviar email para o destinatário `oi@rocketseat.com.br`. Dica: utilize o comando `mailto` dentro do `href`;

- `Telefone`: Link que deve chamar o comando de realizar uma ligação para o número `+5547992078767`. Dica: utilize o comando `tel` dentro do `href`;

##### 2.2
- Uma imagem da logo da empresa
- O nome da empresa
- Uma breve descrição da empresa
- Uma lista com as principais tecnologias utilizadas. Dica: utilize a tag `ul` para lista e `li` para o item da lista.
- Links para as redes sociais da empresa (Github, Instagram e Facebook)

##### 2.3
- Título da página
- Grid com 3 colunas e 1 linha onde serão apresentados os cards dos cursos
- Informações do card:
  - Logo do curso ([Starter](https://skylab.rocketseat.com.br/static/64c237ccff807c054339a62d53b4b402.svg), [Launchbase](https://skylab.rocketseat.com.br/static/0828532024cb46921a6b5e941f8d788d.svg) e [GoStack](https://skylab.rocketseat.com.br/static/83a178a0653dab1d55e2ed7946465975.svg))
  - Título do curso
  - Quantidade de módulos dos cursos
  - Informação se o curso é gratuito ou pago
- Modal: O modal deve conter um iframe que busca a página do curso (dica: basta adicionar `starter`, `launchbase` ou `gostack` ao final de `https://rocketseat.com.br/`). Além do botão de fechar o modal, é preciso implementar a funcionalidade de maximizar o modal (dica: utilize a mesma lógica implementada para fechar o `modalOverlay`, mas trabalhe com a classe `modal` e utilize o método `contains` do `classList` para verificar se o elemento está ou não com a classe `maximize`).


### Estilização
##### 2.1 - Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:
- Deve ser aplicado um background
- Deve ser utilizada a fonte Roboto
- O header precisa ocupar todo o espaço lateral e superior (body sem margin)
- O header precisa ter um espaçamento interno de 30px em todas as direções
- Os links devem ter um espaçamento de 30px entre si

##### 2.2 - Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:
- A imagem deve ter uma borda e um formato circular.
- Deve ser utilizada a fonte Roboto
- O nome da empresa e a imagem devem ser destacar do restante
- Os links das redes sociais devem ter alguma alteração visual quando o cursor do mouse passar por cima

##### 2.3 - Você tem liberdade para escolher a estilização que preferir para esse desafio, mas alguns pontos são obrigatórios:
- Deve ser utilizado o grid para organizar os cursos
- O modal nunca deve abrir maximizado


Esse projeto está sob a licença MIT. Veja o arquivo [LICENSE](../LICENSE) para mais detalhes.
