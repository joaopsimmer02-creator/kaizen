🌐 KAIZEN – Transporte Executivo com Conforto e Segurança
👥 Integrantes e Papéis
Integrante	Função
João Pedro Alves Simmer:	Desenvolvedor Front-End e Designer UI.
João Victor Caires Dionísio: Desenvolvedor Front-End e Designer UI.
💼 Descrição do Negócio e Objetivos do Site

Kaizen é uma empresa de transporte executivo especializada em atender embaixadas, governo federal e empresas.
O site foi desenvolvido com o objetivo de:

Apresentar os serviços e diferenciais da empresa;

Facilitar o contato com clientes através de um formulário online e link direto para WhatsApp;

Transmitir uma imagem de profissionalismo, conforto e segurança, valores fundamentais da marca.

🧭 Link para o Wireframe no FIgma (Parte 1)

🔗 Acesse o Wireframe no Figma: https://www.figma.com/design/VrRiYFgAAuDBjQRwkkqrBO/Sem-t%C3%ADtulo?node-id=0-1&t=GuI8sB7Ki8PpsVL8-1


📁 Estrutura de Pastas e Principais Arquivos da Parte 2 (Fizemos alterções no código incluindo adição de pastas e arquivos, por exemplo, a implementação da página de contato e um menu de navegação tradicional com 3 links)
kaizen/
│
├── html/
│   ├── inicio.html
│   ├── sobre.html
│   ├── contato.html
│   └── componentes/
│       ├── header.html
│       ├── section.html
│       └── footer.html
│
├── css/
│   └── style.css
│
├── img/
│   ├── logo.png
│   ├── icone-whatsapp.png
│   ├── icone-mala.png
│   ├── icone-aviao.png
│   ├── icone-carro.png
│   └── demais ícones e imagens da frota
│
└── README.md

🚀 Melhorias Implementadas na Parte 2
🧩 Componentes Modularizados

Os seguintes componentes foram separados em arquivos independentes para facilitar manutenção e reaproveitamento:

Header: contém o menu de navegação e o ícone do WhatsApp;

Section inicial: apresenta a chamada principal com imagem de destaque e botão “Agende Agora”;

Footer: reúne informações de contato e botão de ação principal.

Justificativa:
Essa modularização reduz repetição de código e garante consistência visual entre todas as páginas.
A reutilização é feita por meio de iframes, o que simplifica a manutenção e centraliza atualizações de conteúdo.

♿ Ajustes de Acessibilidade

Inclusão do link “Pular para o conteúdo principal” para navegação via teclado.

Uso de textos alternativos (alt) em todas as imagens.

Estrutura semântica e hierarquia de títulos (uso correto de <h1>, <h2>, <h3>).

Contraste de cores adequado entre texto e fundo (preto e branco).

📱 Ajustes de Responsividade

O site foi adaptado para telas de diferentes tamanhos utilizando media queries:

Layout responsivo em 768px e 1024px.

Redimensionamento automático de imagens e fontes.

Ajustes no menu de navegação e botões para melhor visualização em dispositivos móveis.

🔗 Integrações Externas Adicionadas

Formulário de Contato: integração com Formspree
 para envio de mensagens via e-mail.

WhatsApp: botão com link direto para contato (https://wa.me/5561982705656).

Google Maps (planejado): futura adição do mapa com localização da empresa na seção “Contato”.

⚙️ Justificativas Técnicas
Decisão Técnica	Justificativa
Uso de iframes para componentes	Facilita a reutilização e centralização de manutenção.
Estrutura modular (header, section, footer)	Melhora a organização do código e a escalabilidade.
CSS responsivo com media queries	Garante acessibilidade e boa experiência em diferentes dispositivos.
Paleta de cores em preto e branco	Reflete sofisticação, elegância e clareza visual.
Fonte “Poppins”	Moderniza o layout e melhora a legibilidade.
Formspree e WhatsApp	Tornam o contato rápido e funcional, sem necessidade de backend.
🧩 Desafios Encontrados e Soluções
Desafio	Solução
Caminhos relativos quebrando dentro dos iframes	Ajuste nas referências de diretório usando ../ para corrigir a origem dos arquivos.
Responsividade inconsistente entre componentes	Criação de breakpoints específicos (768px e 1024px) para harmonizar o layout.
Excesso de código repetido entre páginas	Modularização de header, section e footer via iframes.
Centralização de imagens e textos no mobile	Uso de flexbox e ajustes de padding/margin com media queries.
🔮 Próximos Passos Planejados

Adicionar integração com Google Maps na página de contato.

Implementar menu hambúrguer funcional para mobile.

Criar uma página de orçamento com cálculo automático de valor estimado.

Otimizar o site para SEO e melhor tempo de carregamento.

Publicar o projeto no GitHub Pages para acesso público.

🖼️ Preview

(Adicione aqui uma imagem ou GIF da interface se desejar)
Exemplo:


🧾 Licença

Projeto desenvolvido para fins educacionais — Todos os direitos reservados a Kaizen Transporte Executivo.
