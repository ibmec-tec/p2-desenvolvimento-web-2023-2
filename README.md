# p2-desenvolvimento-web-2023-2

# Objetivo
Reproduzir o comportamento da [página de exemplo](#página-de-exemplo).

# Restrições
1. CSS e Javascript devem ser em arquivos separados
1. É preciso usar armazenamento local para viabilizar a solução de autorização
1. A listagem de atletas e a página de detalhes só devem ser acessíveis a usuários autorizados :eyes:
1. A senha deve estar disponível na página de entrada (é só uma demonstração) :relieved:
1. A comparação entre as senhas deve usar um HASH md5 calculado pela biblioteca [md5](https://pajhome.org.uk/crypt/md5/)
1. A página principal deve obter os elencos com chamadas, *obrigatoriamente* 👮, aos end-points: 
   1. `https://botafogo-atletas.mange.li/all`
   1. `https://botafogo-atletas.mange.li/masculino`
   1. `https://botafogo-atletas.mange.li/feminino`
1. Os dados da página de detalhes devem ser obtidos do end-point `https://botafogo-atletas.mange.li/{atleta-id}`
1. A página de detalhes deve ser construída com a informação do *id* contida na URL
1. Não deve ser possível acessar a página de detalhes sem autorização
1. Erros na obtenção dos dados para a construção da página de detalhes devem gerar uma mensagem na tela
1. O estilo das páginas e cartões é de livre escolha, use a criatividade e garanta que não é uma cópia 😜
1. O trabalho deve ser publicado no githubPages com acesso público
   - não é obrigatório usar URL personalizada, mas se quiser pode 😎
1. Responsividade:
   - **Página de Login**:
      - vertical até 768px;   
   - **Página Detalhes**:
      - vertical até 768px;
   - Container de atletas da **Página Principal**:
      - uma colunas até 768px;
      - duas colunas até 1024px;
      - quatro colunas depois de 1024px;
      - largura máxima da lista de 1200px;
   - Seleção de elenco da **Página Principal**:
      - select até 768px;
      - botões para _viewports_ maiores que 768px;
## Página de exemplo:
  Sua solução deve estar **publicada no githubPages** e emular o compartamento da página: https://p2-2023-2-desweb.mange.li/
