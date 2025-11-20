# 🌐 KAIZEN – Transporte Executivo

## 👥 Integrantes da Dupla e Papéis
| Integrante | Papel |
|-----------|--------|
| **João Pedro Alves Simmer** | Desenvolvedor Front-End,  Estrutura HTML, CSS, prototipagem, testes, conteúdo, repositório Git e GitHub |
| **João Victor Caires Dionísio** | Desenvolvedor Front-End,  Estrutura HTML, CSS, prototipagem, testes, conteúdo, UI, responsividade |
---

## 🏢 Descrição do Pequeno Negócio
A **Kaizen Transporte Executivo** é uma empresa especializada em atendimento profissional para **embaixadas, governo federal e empresas**.  
Oferece transporte seguro, confortável e de alto padrão, incluindo serviços como:

- Motoristas executivos
- Frota premium
- Viagens corporativas e aeroportuárias
- Suporte e atendimento direto pelo WhatsApp  

O site tem como objetivo apresentar esses serviços, transmitir profissionalismo e facilitar o contato com clientes por meio de um formulário e links diretos de WhatsApp.

---

## 📝 Wireframe Detalhado no Figma
🔗 **Link para o Wireframe:** https://www.figma.com/design/VrRiYFgAAuDBjQRwkkqrBO/Sem-t%C3%ADtulo?node-id=0-1&t=GuI8sB7Ki8PpsVL8-1

---

## 🛠 Tecnologias Utilizadas
- **HTML5** (estrutura e conteúdo do site)  
- **CSS3** (estilização, layout e responsividade)  
- **iFrame** para reutilização de componentes (header, section e footer)  
- **Formspree** para envio do formulário de contato  
- **VS Code + Live Server** para testes locais  

---

## 📁 Estrutura de Pastas Explicada
```
kaizen/
│
├── index.html → Página inicial
├── html/
│ ├── sobre.html → Informações da empresa
│ ├── contato.html → Formulário + WhatsApp
│ └── componentes/
│ ├── header.html → Menu e ícone do WhatsApp (reutilizável)
│ ├── section.html → Seção principal (banner + chamada)
│ └── footer.html → Rodapé com contatos (reutilizável)
│
├── css/
│ ├── style.css → Estilos principais, paleta, responsividade
│ └── style.min.css → Versão minificada do CSS
│
├── img/
│ ├── logo.png
│ ├── favicon.png
│ ├── icone-whatsapp.png
│ ├── icone-mala.png
│ ├── icone-aviao.png
│ ├── icone-carro.png
│ └── demais imagens utilizadas
│
└── README.md
```

---

# 📌 Resumo das 3 Partes do Projeto

## **🔹 Parte 1 – Planejamento (Wireframe e Estrutura Inicial)**
- Criação do wireframe no Figma.  
- Definição das páginas principais: **Início, Sobre e Contato**.  
- Planejamento da paleta preto/branco e layout minimalista.  
- Organização inicial das pastas e dos componentes reutilizáveis.

---

## **🔹 Parte 2 – Desenvolvimento do Layout**
- Codificação das páginas em HTML e CSS.  
- Criação dos componentes separados: **header, section, footer**.  
- Implementação dos iframes para reutilizar esses componentes.  
- Ajustes de acessibilidade (textos alternativos, estrutura semântica).  
- Design responsivo com media queries (768px e 1024px).  
- Ajuste dos links e caminhos relativos para funcionar no Live Server.

---

## **🔹 Parte 3 – Finalização e Integrações**
- Integração do formulário com **Formspree**.  
- Botão fixo de **WhatsApp** funcionando.  
- Organização completa dos arquivos e limpeza do código.  
- Preparação do projeto para publicação no **GitHub Pages**.  
- Finalização deste README.md completo.

---

# 🌍 Acesso ao site  
-🔗 **GitHub Pages**: (https://joaopsimmer02-creator.github.io/kaizen/) 

-🖼️ **Preview do site** :
<img width="1895" height="902" alt="image" src="https://github.com/user-attachments/assets/edc439a1-c4a3-4440-87a4-0735ba917ac1" />

- **Data de publicação**: 18/11/2025


---

## 🧪 Testes Realizados

### ✔ Navegadores Testados
- Google Chrome (desktop)
- Microsoft Edge (desktop)
- Mozilla Firefox
- Chrome Mobile (Android)
- Safari Mobile (iOS) *(testado via simulação)*

---

### ✔ Dispositivos e Resoluções Testadas
- **Desktop 1920×1080**
- **Notebook 1366×768**
- **Tablet 768px**
- **Smartphone 414px**
- **Smartphone 360px**

---

### ✔ Problemas Encontrados e Soluções

#### 1. **Componentes via iframe não apareciam no GitHub Pages**
- **Problema:** Caminhos relativos não funcionavam após publicar.
- **Causa:** GitHub Pages exige caminhos relativos exatos a partir da raiz do repositório.  
- **Solução:** Ajuste dos caminhos para `kaizen/html/componentes/header.html`, `kaizen/html/componentes/footer.html`, etc., respeitando a estrutura real publicada.

#### 2. **Footer funcionava em apenas uma página**
- **Problema:** O footer aparecia somente em *index.html*.  
- **Causa:** O caminho para o arquivo `footer.html` estava incorreto nas outras páginas.  
- **Solução:** Uniformização dos caminhos relativos nas três páginas.

#### 3. **Imagens não carregando no Live Server**
- **Problema:** Algumas imagens apareciam “quebradas”.  
- **Causa:** A pasta `img` estava fora do local esperado.  
- **Solução:** Reorganização da estrutura de pastas e atualização dos caminhos.

#### 4. **Links do menu abrindo em nova aba**
- **Problema:** Usuário clicava em “Início / Sobre / Contato” e o site abria outra aba.  
- **Causa:** Atributo `target="_blank"` dentro do header.  
- **Solução:** Adição do atributo "_top"para que os links abram na mesma aba.

---

### ✔ Limitações Conhecidas
- O uso de **iframes** pode dificultar:
  - SEO (Google indexa páginas iframe com limitações)
  - Ajustes avançados de responsividade
  - Scripts que precisam atuar na página inteira
- O GitHub Pages pode ter atrasos no carregamento de componentes por iframe.
- No iPhone (Safari), a rolagem dentro de iframes pode depender da configuração de CSS.

---

### ✔ Evidências (prints dos testes)
- 📁 **Link da pasta docs:** (https://onedrive.live.com/?redeem=aHR0cHM6Ly8xZHJ2Lm1zL2YvYy85ZmJkMDI3OGE0MmUzOTAyL0VtbVlENWNZRHdSQXRGWXFhbUs1aGI0QmU3VVFMc0QtY0FqYkRWd08wQ3ZSVGc%5FZT0xM29rZHI&id=9FBD0278A42E3902%21s970f98690f184004b4562a6a62b985be&cid=9FBD0278A42E3902)  
-

---

## 🧩 Depoimentos dos Integrantes – Aprendizados e Experiência

---

# 👤 Integrante 1 – João Pedro Alves Simmer

Ao longo do desenvolvimento deste projeto, refinei minhas competências em HTML e CSS, particularmente na estruturação de componentes reutilizáveis e na adaptação para diferentes tamanhos de tela.  O aspecto mais complicado foi lidar com iframes, especialmente devido aos caminhos relativos e ao funcionamento no GitHub Pages.  Atualmente, tenho muito mais controle sobre a estrutura de pastas, a organização do código e a solução de problemas técnicos.  Foi positivo trabalhar em dupla: compartilhamos as responsabilidades de forma eficiente e mantivemos uma comunicação constante, o que facilitou muito o progresso do projeto. 

---

# 👤 Integrante 2 – João Victor Caires Dionísio

Ao longo deste semestre, desenvolvi muito minhas habilidades em front-end, aprendendo a estruturar páginas com HTML e CSS, organizar pastas de forma mais profissional e criar layouts responsivos usando tanto Media Queries quanto a abordagem Mobile First. Também aprendi a interpretar e transformar wireframes do Figma em código, além de publicar projetos no GitHub Pages utilizando Git e GitHub para versionamento. Passei a ter mais cuidado com acessibilidade, usando atributos alt corretamente e aplicando pequenos detalhes visuais como efeitos de hover. Mesmo sem usar JavaScript, consegui trabalhar bem com componentes estáticos e entender como manter um padrão visual consistente. No geral, evoluí bastante no desenvolvimento, na organização do projeto e na forma de pensar interfaces, ganhando mais confiança para enfrentar projetos futuros.

---

## 🤝 Reflexão da Dupla – Evolução, Feedbacks e Relevância

Desde o início, o projeto passou por uma evolução considerável, transformando-se de um simples wireframe em um site completo com design melhorado, componentes reutilizáveis, responsividade, estrutura de pastas organizada e ajustes significativos nos caminhos dos iframes. Isso resultou em um layout profissional que está em sintonia com a proposta da Kaizen.  Os feedbacks recebidos foram fundamentais para aprimorar a clareza, o contraste, o alinhamento e os elementos de contato, resultando em um visual mais limpo e coerente. Além disso, esses feedbacks inspiraram melhorias futuras, como aumentar a acessibilidade e substituir os iframes.  No âmbito empresarial, o site valoriza a transmissão de profissionalismo, simplifica o contato e fortalece a confiabilidade do serviço de transporte executivo, representando um exemplo concreto de domínio técnico e colaboração — um elemento que definitivamente merece ser incluído no portfólio.

---


## 🔮 Próximos Passos e Melhorias Futuras

### 🛠️ Melhorias Técnicas Planejadas
- [ ] Implementar menu hambúrguer funcional no mobile.
- [ ] Adicionar novas funcionalidades interativas no site
- [ ] Melhorar a acessibilidade, incluindo textos alternativos mais completos e melhor contraste
- [ ] Implementar pequenas animações e interações usando JavaScript
- [ ] Aprender e aplicar um framework moderno como **React** ou **Vue** em uma próxima versão do projeto

---

### 📚 Conhecimentos a Aprofundar
- Aprofundar em boas práticas de acessibilidade seguindo as diretrizes **WCAG**
- Estudar animações avançadas com **CSS** e microinterações
- Entender melhor manipulação de API e integração com back-end
- Melhorar organização de projetos utilizando **Git** e versionamento colaborativo
- Aprender sobre componentes reutilizáveis sem iframes (templating ou frameworks)

---

### 🎓 Aplicação em Disciplinas Futuras
Os aprendizados deste projeto serão úteis em várias próximas disciplinas.  
Pretendemos aplicar:

- Melhor organização de código e estrutura de pastas em futuros trabalhos
- Uso adequado de responsividade e acessibilidade em qualquer interface que formos desenvolver
- Integração de formulários reais com back-end ou serviços externos
- Conhecimentos de versionamento com Git em projetos colaborativos
- Evolução para frameworks modernos, ampliando a complexidade e qualidade dos próximos projetos

Este projeto servirá como base para desenvolver sites mais completos, profissionais e tecnicamente consistentes ao longo do curso.


