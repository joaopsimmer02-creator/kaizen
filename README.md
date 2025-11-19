# 🌐 KAIZEN – Transporte Executivo

## 👥 Integrantes da Dupla e Papéis
| Integrante | Papel |
|-----------|--------|
| **João Pedro Alves Simmer** | Desenvolvedor Front-End, prototipagem, testes, conteúdo, repositório Git e GitHub |
| **João Victor Caires Dionísio** | Desenvolvedor Front-End, Estrutura HTML, CSS, testes, UI e Responsividade |

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
├── html/
│ ├── index.html → Página inicial
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

# ▶️ Instruções para Rodar o Projeto Localmente
1. Baixe o repositório ou faça o clone:
git clone https://github.com/usuario/nome-do-repositorio.git

2. Abra a pasta no **VS Code**.

3. Instale a extensão **Live Server** (caso ainda não tenha).

4. Clique com o botão direito no arquivo **inicio.html**  
→ opção **“Open with Live Server”**.

5. O site irá abrir no navegador em:
http://127.0.0.1:5500


*Obs.: É importante abrir pelo Live Server porque os iframes usam caminhos relativos.*

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
- **Solução:** Ajuste dos caminhos para `../componentes/header.html`, `../componentes/footer.html`, etc., respeitando a estrutura real publicada.

#### 2. **Footer funcionava em apenas uma página**
- **Problema:** O footer aparecia somente em *inicio.html*.  
- **Causa:** O caminho para o arquivo `footer.html` estava incorreto nas outras páginas.  
- **Solução:** Uniformização dos caminhos relativos nas três páginas.

#### 3. **Imagens não carregando no Live Server**
- **Problema:** Algumas imagens apareciam “quebradas”.  
- **Causa:** A pasta `img` estava fora do local esperado.  
- **Solução:** Reorganização da estrutura de pastas e atualização dos caminhos.

#### 4. **Links do menu abrindo em nova aba**
- **Problema:** Usuário clicava em “Início / Sobre / Contato” e o site abria outra aba.  
- **Causa:** Atributo `target="_blank"` dentro do header.  
- **Solução:** Remoção do atributo para que os links abram na mesma aba.

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
- 📁 **Navegadores:** `tests/navegadores/`  
- 📁 **Dispositivos:** `tests/dispositivos/`  
- 📁 **Problemas e correções:** `tests/problemas/`

*(Apenas substituir os caminhos acima pelos nomes reais das pastas no repositório, caso sejam diferentes.)*

---

## 🧩 Depoimentos dos Integrantes – Aprendizados e Experiência

---

# 👤 Integrante 1 – João Pedro Alves Simmer
Durante o desenvolvimento deste projeto, aprimorei minhas habilidades em HTML e CSS, especialmente na organização de componentes reutilizáveis e na responsividade. O conceito mais desafiador foi trabalhar com iframes, principalmente por causa dos caminhos relativos e do comportamento no GitHub Pages. Hoje tenho muito mais domínio sobre estrutura de pastas, organização de código e resolução de problemas técnicos. Trabalhar em dupla foi positivo: dividimos bem as tarefas e mantivemos uma comunicação constante, o que facilitou bastante o andamento do projeto. O maior desafio foi fazer os iframes funcionarem corretamente em todos os ambientes, mas superamos com testes e ajustes. Se pudesse voltar atrás, evitaria o uso de iframes e adotaria outra forma de reutilizar componentes.

---

# 👤 Integrante 2 – João Victor Caires Dionísio
*(Texto pronto para editar)*  
Durante o projeto, desenvolvi melhor minhas habilidades técnicas, especialmente no uso de HTML, CSS e na organização dos arquivos. O conceito mais desafiador para mim foi entender os fluxos de navegação com iframes e como cada página se conectava. Senti que evoluí bastante na compreensão da estrutura do site e na colaboração em um projeto compartilhado. Trabalhar em dupla foi importante para dividir responsabilidades e alinhar decisões ao longo do processo. Nosso maior desafio foi lidar com erros de carregamento e caminhos quebrados, mas resolvemos com testes e ajustes até tudo funcionar corretamente. Se pudesse refazer algo, teria planejado a estrutura com mais antecedência para evitar retrabalho.

---

## 🤝 Reflexão da Dupla – Evolução, Feedbacks e Relevância

### 🚀 Evolução do Projeto
O projeto evoluiu significativamente desde a Parte 1. Começamos apenas com o wireframe e a estrutura inicial das páginas, e ao longo das etapas adicionamos design, componentes reutilizáveis, responsividade e integração com formulário. As maiores melhorias foram a organização das pastas, a padronização visual do site, a correção dos caminhos relativos dos iframes e a implementação final do layout profissional da Kaizen. O resultado final atende completamente à proposta inicial: criar um site moderno, claro e funcional para apresentar os serviços de transporte executivo.

### 🗣️ Feedbacks Recebidos
Os feedbacks dos colegas ajudaram bastante, principalmente em relação à clareza dos textos, ao contraste visual e à importância de manter um padrão entre as páginas. Os comentários mais úteis foram os que apontaram ajustes simples, como reorganizar margens, alinhar elementos e melhorar o botão de contato. Esses feedbacks contribuíram diretamente para deixar o site mais limpo e agradável. Pretendemos aplicar essas sugestões em versões futuras, incluindo melhorias na acessibilidade e, possivelmente, substituindo iframes por outra solução mais robusta.

### 💼 Relevância para o Negócio
Acreditamos que o site realmente agregaria valor ao pequeno negócio escolhido, pois transmite profissionalismo, organização e facilidade de contato — pontos essenciais para um serviço de transporte executivo. Se pudéssemos apresentá-lo ao dono da empresa, destacaríamos que o site reforça a credibilidade da marca e facilita a captação de novos clientes. Sim, usaríamos este projeto no portfólio, pois ele demonstra domínio de HTML, CSS, responsividade, trabalho em equipe, organização de pastas, resolução de problemas e capacidade de entregar um site completo e funcional.

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


