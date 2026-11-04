# Cavaleiros da Antiga República — Guia da HQ
 
- **Tema:** HQ *Cavaleiros da Antiga República*
- **Aluna:** Leticia Melchioretto
- **Turma:** DS M3 2025/1 M3
- **Unidade curricular:** Programação de Aplicativos
## Descrição
 
Site de cinco páginas que apresenta a HQ *Knights of the Old Republic* (*Cavaleiros da Antiga República*), seu universo, personagens e volumes publicados. Inclui uma tabela de dados, um formulário de inscrição para receber mais informações da HQ e uma página de contato.
 
## Como abrir o projeto
 
Baixe ou clone o repositório e abra o arquivo `index.html` em qualquer navegador. Não é necessário instalar nada.
 
## Páginas
 
- `index.html` — Início: apresenta o tema e convida a navegar.
- `sobre.html` — Sobre: textos sobre universo e personagens, curiosidade, glossário e fontes.
- `dados.html` — Dados: tabela dos volumes da série.
- `cadastro.html` — Cadastro: inscrição para receber mais informações da HQ.
- `contato.html` — Contato: endereço, e-mail e telefone fictícios, horário de atendimento e formulário de mensagem.
## Acessibilidade
 
- Link "Pular para o conteúdo" como primeiro elemento do `<body>` de todas as páginas.
- Estrutura com `header`, `nav`, `main` e `footer`; menu com `aria-current="page"` na página atual.
- Textos alternativos descritivos nas imagens e `alt=""` na imagem decorativa.
- Formulários com `label` associado a cada campo, `fieldset` e `legend`.
- Tabela com `caption`, `scope` em cabeçalhos de coluna e de linha, e datas marcadas com `<time datetime>`.
- Idioma da página declarado com `lang="pt-BR"`.
### Resultado do teste de teclado (Tab)
 

| Página | Resultado |
|---|---|
| index.html | Todos os links ficaram circulados em preto e os endereços aparecem na parte inferior da tela, além de quando apertei TAB em voltar aoo topo ele voltou
| sobre.html | Todos os links ficaram circulados em preto e os endereços aparecem na parte inferior da tela, além de quando apertei TAB em voltar aoo topo ele voltou
| dados.html | Todos os links ficaram circulados em preto e os endereços aparecem na parte inferior da tela, além de quando apertei TAB em voltar aoo topo ele voltou
| cadastro.html | Todos os links ficaram circulados em preto e o formulario não enviou em branco pois tinha campos obrigatrios, além de quando apertei TAB em voltar aoo topo ele voltou
| contato.html | Todos os links ficaram circulados em preto e o formulario não enviou em branco pois tinha campos obrigatrios, além de quando apertei TAB em voltar aoo topo ele voltou

 
## Fontes
 
### Imagens
 
Todas as imagens estão na pasta `img/`, em formato SVG, com menos de 300 KB cada.
 
| Arquivo | Fonte | Licença |
|---|---|---|
| `img/linha-do-tempo.svg` | Ilustração criada com auxílio de IA (Claude, da Anthropic)
| `img/taris.svg` | Ilustração criada com auxílio de IA (Claude, da Anthropic) 

 
### Informações
 
- Dark Horse Comics, editora da série: https://www.darkhorse.com/
- Wikipédia, Star Wars: Knights of the Old Republic (comics): https://en.wikipedia.org/wiki/Star_Wars:_Knights_of_the_Old_Republic_(comics)
- Wookieepedia, Mandalorian Wars: https://starwars.fandom.com/wiki/Mandalorian_War (conteúdo sob licença CC BY-SA)
- Wookieepedia, 3976 BBY: https://starwars.fandom.com/wiki/3976_BBY (conteúdo sob licença CC BY-SA)
- Arquivo da Wookieepedia, Old Sith Wars (cronologia das guerras): https://starwars.archivum.wiki/article/Old_Sith_Wars
- Arquivo da Wookieepedia, 3956 BBY: https://starwars.archivum.wiki/article/3956_BBY