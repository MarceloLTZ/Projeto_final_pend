# Painel ENEM Pro

Aplicação web de página única (One Page) com ferramentas de apoio ao assistente de coordenação durante a aplicação do ENEM.

**Acesse o projeto publicado:** [https://marceloltz.github.io/Projeto_final_pend/](https://marceloltz.github.io/Projeto_final_pend/)

Projeto final da unidade curricular de Front-end.

---

## Tema escolhido

No dia de prova, o assistente de coordenação cuida de muita coisa ao mesmo tempo: malotes, equipe de fiscais, horários dos portões e ocorrências. O Painel ENEM Pro reúne essas tarefas em um só lugar, com um checklist da operação, uma calculadora de insumos, protocolos para situações de emergência e um formulário para registrar ocorrências.

O projeto é acadêmico e independente. Não é um site oficial do INEP.

## Tecnologias utilizadas

- **HTML5**, com seções estruturadas por `section`, `nav` e `footer`
- **CSS3**, com variáveis, efeitos de hover e ajustes de layout
- **JavaScript (ES6+)**, com manipulação do DOM e `localStorage`
- **Bootstrap 5.3**: navbar responsiva, cards, accordion, modais, barra de progresso, formulário e sistema de grid
- **Bootstrap Icons** e **Google Fonts (Inter)**

## Recursos em JavaScript

1. **Modo escuro e claro:** o botão da navbar alterna o tema, e a escolha fica salva no navegador.
2. **Contadores animados:** os números do banner principal (salas, fiscais e candidatos) sobem até o valor final ao carregar a página.
3. **Checklist da operação:** lista de tarefas com filtros (todos, pendentes e concluídos), barra de progresso e botão para reiniciar. O andamento fica salvo no navegador.
4. **Calculadora logística:** a partir do número de salas e da média de candidatos, estima água, fiscais de corredor, envelopes porta-objetos e canetas reservas.
5. **Formulário com validação:** confere nome, e-mail em formato válido, local, categoria e descrição (mínimo de 10 caracteres). Mostra mensagens de erro nos campos e um aviso de sucesso ou erro, com indicador de carregamento durante o envio.
6. **Limpeza de dados:** um link no rodapé apaga o tema e o checklist salvos no navegador.

## Seções da página

- Navbar fixa com logotipo, links para as seções e botão de modo escuro
- Banner principal com chamada para ação e indicadores
- Atribuições do assistente, em cards
- Guia de diretrizes, em accordion
- Checklist de operação diária
- Calculadora logística
- Protocolos de contingência, em cards que abrem modais com o passo a passo
- Formulário de registro de ocorrências
- Rodapé com links rápidos, links oficiais, redes sociais e direitos autorais

## Formulário de contato

O formulário tem cinco campos: nome, e-mail, escola ou local, categoria e descrição. A validação é feita em JavaScript antes do envio. Como o projeto roda inteiramente no navegador, o envio é simulado: ao enviar, a página mostra uma mensagem de sucesso com um número de protocolo, mas nenhum e-mail é disparado.

## Estrutura do projeto

```
/
├── index.html
└── README.md
```

O HTML, o CSS e o JavaScript ficam no mesmo arquivo, `index.html`.

## Como executar localmente

Não há dependências para instalar. Baixe ou clone o repositório e abra o arquivo `index.html` no navegador. É preciso ter internet para carregar o Bootstrap, os ícones e a fonte.

```bash
git clone https://github.com/MarceloLTZ/Projeto_final_pend.git
```

## Autoria

- Marcelo ([@MarceloLTZ](https://github.com/MarceloLTZ))
