# 🌐 KAIZEN – Transporte Executivo com Conforto e Segurança

## 👥 Integrantes e Papéis
| Integrante | Função |
|-------------|--------|
| **João Pedro Alves Simmer** | Desenvolvedor Front-End e Designer UI |
| **João Victor Caires Dionísio** | Desenvolvedor Front-End e Designer UI |

---

## 💼 Descrição do Negócio e Objetivos do Site
**Kaizen** é uma empresa de transporte executivo especializada em atender **embaixadas, governo federal e empresas**.  

O site tem como objetivos principais:
- Apresentar os serviços e diferenciais da empresa.  
- Facilitar o contato com clientes por meio de **formulário online** e **WhatsApp**.  
- Transmitir os valores da marca: **profissionalismo, conforto e segurança**.  

---

## 🧭 Link para o Wireframe (Parte 1)
🔗 **Protótipo no Figma
🔗 Protótipo completo no Figma (shift + espaço): https://www.figma.com/design/VrRiYFgAAuDBjQRwkkqrBO/Sem-t%C3%ADtulo?node-id=0-1&t=GuI8sB7Ki8PpsVL8-1**  

---

## 📁 Estrutura de Pastas e Principais Arquivos (Fizemos alterações no código e estrutura de pastas em relação a Parte 1, incluindo criação da página de contato e menu de navegação com 3 links)
kaizen/
│
├── html/
│ ├── inicio.html
│ ├── sobre.html
│ ├── contato.html
│ └── componentes/
│ ├── header.html
│ ├── section.html
│ └── footer.html
│
├── css/
│ └── style.css
│
├── img/
│ ├── logo.png
│ ├── icone-whatsapp.png
│ ├── icone-mala.png
│ ├── icone-aviao.png
│ ├── icone-carro.png
│ └── demais ícones e imagens da frota
│
└── README.md

## 🚀 Melhorias Implementadas na Parte 2

### 🧩 Componentes Modularizados
Os seguintes componentes foram separados em arquivos independentes para facilitar manutenção e reaproveitamento:

- **Header:** contém o menu de navegação e o ícone do WhatsApp.  
- **Section inicial:** apresenta a chamada principal com imagem e botão “Agende Agora”.  
- **Footer:** reúne as informações de contato e o botão principal de ação.

**Por que essa escolha?**  
A modularização reduz repetição de código, facilita atualizações e garante consistência visual entre todas as páginas.  
A reutilização é feita por meio de **iframes**, centralizando conteúdo e simplificando manutenção.

---

### ♿ Ajustes de Acessibilidade
- Adicionado link **“Pular para o conteúdo principal”** para navegação por teclado.  
- Uso de **textos alternativos (alt)** em todas as imagens.  
- Estrutura semântica com títulos organizados (`<h1>`, `<h2>`, `<h3>`).  
- Contraste adequado entre texto e fundo (preto e branco).  

---

### 📱 Ajustes de Responsividade
O layout foi otimizado com **media queries** para diferentes tamanhos de tela:

- Breakpoints: **768px** e **1024px**.  
- Imagens e fontes redimensionáveis automaticamente.  
- Ajustes de espaçamento e centralização para o menu e botões no mobile.  

---

### 🔗 Integrações Externas Adicionadas
- **Formulário de Contato:** integração com [Formspree](https://formspree.io/) para envio de mensagens por e-mail.  
- **WhatsApp:** botão com link direto para contato via `https://wa.me/5561982705656`.  
- **Google Maps (planejado):** futura adição na seção de contato, pois a empresa não tem local fixo de atendimento.  

---

## ⚙️ Justificativas Técnicas

| Decisão Técnica | Justificativa |
|------------------|---------------|
| Uso de **iframes** para componentes | Centraliza conteúdo e facilita manutenção. |
| Estrutura modular (header, section, footer) | Melhora a organização e reaproveitamento. |
| CSS responsivo com **media queries** | Garante boa visualização em dispositivos móveis. |
| Paleta de cores preto e branco | Reflete sofisticação e clareza visual. |
| Fonte “Poppins” | Proporciona modernidade e legibilidade. |
| Integração com Formspree e WhatsApp | Facilita o contato sem necessidade de backend. |

---

## 🧩 Desafios Encontrados e Soluções

| Desafio | Solução |
|----------|----------|
| Caminhos relativos quebrando dentro dos iframes | Ajuste dos diretórios com `../` para corrigir a origem dos arquivos. |
| Responsividade inconsistente entre componentes | Criação de breakpoints específicos para harmonizar o layout. |
| Código repetido entre páginas | Modularização do header, section e footer via iframes. |
| Centralização de imagens e textos no mobile | Uso de flexbox e ajustes de margin/padding com media queries. |

---

## 🔮 Próximos Passos Planejados
- Adicionar **Google Maps** na página de contato.  
- Implementar **menu hambúrguer funcional** no mobile.  
- Criar página de **orçamento automatizado**.  
- Otimizar o site para **SEO** e **melhor desempenho**.  
- Publicar no **GitHub Pages** para acesso público.  

---

## 🧾 Licença
Projeto desenvolvido para fins educacionais.  
**Todos os direitos reservados a Kaizen Transporte Executivo.**
