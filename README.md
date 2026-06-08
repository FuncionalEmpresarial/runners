## Visão Geral

O Dashboard de Atividades Strava é uma solução de análise e consolidação de dados esportivos que permite coletar informações de atividades de atletas autorizados e disponibilizá-las em painéis analíticos e relatórios.

O objetivo da aplicação é fornecer métricas e indicadores de desempenho para atletas e grupos de treinamento por meio de ferramentas de Business Intelligence, como Power BI.

---

## Funcionalidades

* Autenticação segura utilizando o protocolo OAuth 2.0 do Strava.
* Coleta de dados de atividades autorizadas pelos atletas.
* Consolidação de informações de múltiplos atletas.
* Atualização automática dos dados utilizando tokens de acesso fornecidos pelo Strava.
* Integração com plataformas de análise e visualização de dados.
* Geração de relatórios e indicadores de desempenho esportivo.

---

## Como Funciona a Autorização

Esta aplicação utiliza o processo oficial de autenticação do Strava.

Ao conectar sua conta:

1. O atleta é redirecionado para a página de autorização do Strava.
2. O Strava apresenta as permissões solicitadas.
3. O atleta escolhe conceder ou não o acesso.
4. Após a autorização, o Strava fornece um código temporário para a aplicação.
5. A aplicação obtém os tokens de acesso necessários para consultar os dados autorizados.
6. Apenas os dados permitidos pelo atleta são acessados.

Em nenhum momento a aplicação solicita ou armazena a senha da conta Strava.

---

## Dados Utilizados

Dependendo das permissões concedidas, a aplicação poderá acessar:

* Informações básicas do perfil do atleta.
* Histórico de atividades.
* Distância percorrida.
* Tempo de atividade.
* Ganho de elevação.
* Estatísticas de treinamento.
* Dados relacionados às atividades registradas no Strava.

Os dados são utilizados exclusivamente para fins de análise e geração de relatórios.

---

## Armazenamento de Dados

A aplicação poderá armazenar:

* Identificador do atleta.
* Token de atualização (refresh token).
* Dados das atividades autorizadas.

Essas informações são utilizadas exclusivamente para manter a atualização dos relatórios e dashboards disponibilizados aos usuários autorizados.

---

## Revogação de Acesso

O atleta pode revogar o acesso da aplicação a qualquer momento:

1. Acesse sua conta Strava.
2. Vá em **Configurações**.
3. Acesse **Meus Aplicativos**.
4. Localize esta aplicação.
5. Clique em **Revogar Acesso**.

Após a revogação, a aplicação deixará de obter novos dados da conta do atleta.

---

## Privacidade

Esta aplicação:

* Não comercializa dados dos usuários.
* Não compartilha informações com terceiros sem autorização.
* Utiliza os dados exclusivamente para fins analíticos e estatísticos.
* Segue as políticas e diretrizes estabelecidas pelo Strava para desenvolvedores.

---

## Suporte

Caso encontre algum problema ou tenha dúvidas sobre a utilização da aplicação, abra uma solicitação na área de Issues deste repositório.

Ao reportar um problema, informe:

* Descrição detalhada do ocorrido.
* Data e horário aproximados.
* Capturas de tela (quando aplicável).
* Identificador do atleta (opcional).

---

## Contato

Para suporte técnico ou dúvidas relacionadas à aplicação:

* E-mail: marketing@funcional.com

---

## Isenção de Responsabilidade

Esta aplicação não é afiliada, patrocinada ou endossada pelo Strava.

Strava é uma marca registrada da Strava, Inc.

Todos os dados das atividades pertencem aos respectivos atletas e são acessados apenas mediante autorização explícita concedida por cada usuário.

---

## Conformidade

Esta aplicação foi desenvolvida em conformidade com:

* Termos da API do Strava.
* Políticas para Desenvolvedores do Strava.
* Padrão OAuth 2.0 para autorização segura.

O uso desta aplicação está sujeito aos termos e condições definidos pelo Strava.
