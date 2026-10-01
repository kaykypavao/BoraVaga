# BoraVagas

> 🚧 **Status: em planejamento.**
> Este repositório documenta a ideia, o escopo e as decisões de um projeto que ainda vai ser desenvolvido. Por enquanto não há código: o objetivo é deixar a proposta clara antes de começar a construir.

## Sobre o projeto

O **BoraVagas** é um aplicativo de vagas de emprego para Android, feito em **Dart/Flutter**, com uma ideia central: **candidatar-se deve ser simples**. O candidato escolhe a vaga, vê no mapa a região aproximada do trabalho e envia o currículo direto para a empresa, sem criar conta.

O objetivo é ter um app real, publicado e funcionando, com foco inicial no **Rio de Janeiro** e a meta de crescer para o Brasil todo.

## O problema

- Cadastros longos afastam quem só quer se candidatar a uma vaga.
- Muitas vagas não deixam claro onde o trabalho acontece, e o deslocamento pesa muito na decisão.
- Enviar um currículo costuma exigir várias telas, contas e plataformas diferentes.

## A proposta

- **Candidato sem cadastro:** escolheu a vaga, enviou o currículo.
- **Empresas se cadastram por email** para publicar vagas e receber currículos.
- **Mapa com a região aproximada** do local de trabalho (nunca o endereço exato).
- **Currículo direto para a empresa**, por email, em PDF.
- **A plataforma não guarda currículos.** Eles seguem do candidato para o recrutador, e só o recrutador tem acesso.
- **Todos os tipos de vaga:** CLT, PJ, estágio, jovem aprendiz e bicos.

## Como vai funcionar

**Para quem procura vaga**

1. Abre o app e navega pelas vagas da região.
2. Vê os detalhes da vaga e a área aproximada no mapa.
3. Preenche seus dados de contato, anexa o currículo em PDF e envia.

**Para a empresa**

1. Cadastra-se preenchendo um formulário.
2. Publica vagas informando o local de trabalho e descrição da vaga.
3. Recebe cada candidatura por email, com uma mensagem padrão e o currículo em anexo.

## Escopo do MVP

- Lista de vagas
- Tela da vaga com a região no mapa
- Envio de currículo em PDF
- Cadastro de empresa e publicação de vagas

**Ficam para depois:** filtros avançados, busca por distância, notificações e expansão para outras cidades.

## Tecnologias

| Parte | Definição |
|---|---|
| App mobile | Dart / Flutter (Android primeiro) |
| Versão web | Em avaliação |
| Mapa | API de mapa (provedor a definir) |
| Backend e envio de email | A definir |

## Privacidade e segurança

O envio de currículos envolve dados pessoais, então o projeto é pensado com a LGPD em mente: coleta mínima de informações, currículo entregue apenas ao recrutador da vaga e nenhum armazenamento do arquivo pela plataforma. O envio também terá proteções contra spam e abuso. Haverá uma política de privacidade pública antes do lançamento.

## Roadmap

- [x] Definir a ideia, o público inicial e o escopo do MVP
- [ ] Definir identidade do projeto (nome final, domínio e ícone)
- [ ] Escolher provedor de mapa e backend
- [ ] Modelar os dados de empresas e vagas
- [ ] Prototipar as telas principais
- [ ] Criar a estrutura inicial do projeto Flutter
- [ ] Desenvolver o MVP
- [ ] Teste fechado com usuários e empresas do Rio de Janeiro
- [ ] Publicação na Google Play

## Autor

Projeto idealizado por **Kayky Pavão**.
