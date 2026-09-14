# Central Refrimáquinas

Site: https://refrimaquinas-of.github.io/central/

Painel: https://refrimaquinas-central-oficial.refrimaquinas.chatgpt.site/admin/login

## Publicação de 14/09/2026

Páginas pré-renderizadas com endereço, telefone e horário no HTML inicial; metadados e canonical por rota; sitemap; página de erro própria; busca e filtros de unidades; WhatsApp central com mensagem inicial Olá!; mapas sob demanda; avaliações; layout responsivo; imagens locais otimizadas; duas fontes; QR Code carregado sob demanda.

O GitHub Pages usa sua construção Jekyll existente apenas para transformar os arquivos page-*.html em rotas com permalink. Não adicionar .nojekyll sem antes mudar a estratégia de publicação: isso impediria a geração das rotas. Os arquivos já chegam pré-renderizados, sem necessidade de execução React no servidor do GitHub.

O painel e os dados continuam no servidor original. A página consulta os dados ao abrir e ao recuperar o foco; quando falha, mostra o conteúdo da última publicação com aviso. Atualizações do painel são refletidas no navegador; atualizar o HTML pré-renderizado para robôs sem JavaScript exige novo build/publicação.

Os eventos da Central no GitHub são registrados automaticamente de forma agregada. Não usamos cookies de rastreamento, identificadores de visitantes, IP bruto, localização precisa ou parâmetros de campanha. Cada UUID deduplica uma ação, não uma pessoa. Os dados históricos foram preservados; ações não registradas antes desta atualização não podem ser recuperadas.

Campanhas e cartões já têm início e término; o término é a validade, sem criar um segundo campo expiresAt divergente. O painel oferece Campanha sazonal, Catálogo, Nova unidade, Vaga de emprego e Contato comercial. Campanhas vigentes, produtos e canais adicionais dependem de conteúdo confirmado.

A equipe pediu para manter domínio próprio, dados institucionais, ano de fundação, campanhas e catálogo, e configuração de contas individuais pendentes. Nenhum desses dados foi inventado. O acesso administrativo foi preservado no rodapé por solicitação expressa anterior da equipe; a segurança depende da autenticação, não de esconder o link.

## Acesso offline

O botão Disponibilizar para acesso offline baixa as páginas e recursos essenciais somente por solicitação. O vídeo não é baixado para uso offline. Os dados offline refletem a última publicação, com aviso quando a API não pode ser consultada. As APIs administrativas e serviços externos não entram no cache.

