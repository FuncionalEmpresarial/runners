# Política de Privacidade

## Dados Coletados

A aplicação consulta exclusivamente o endpoint:

```text
/athlete/activities
```

Os seguintes campos podem ser coletados das atividades autorizadas pelo usuário:

* name
* distance
* moving_time
* elapsed_time
* total_elevation_gain
* sport_type
* achievement_count
* kudos_count
* comment_count
* athlete_count
* start_latlng
* end_latlng
* average_speed
* max_speed
* elev_high
* elev_low
* pr_count
* total_photo_count
* start_date_local

Nenhum dado adicional é coletado além das informações disponibilizadas por este endpoint e autorizadas pelo próprio usuário através do Strava.

---

## Finalidade da Coleta

Os dados são utilizados exclusivamente para:

* Consolidação de atividades esportivas.
* Geração de métricas e indicadores de desempenho.
* Construção de relatórios e dashboards analíticos.
* Acompanhamento estatístico de atividades físicas.

Os dados não são utilizados para fins comerciais, publicidade ou compartilhamento com terceiros.

---

## Armazenamento dos Dados

Os dados obtidos através da API do Strava são processados pelo Microsoft Power BI utilizando o recurso Power Query.

As informações permanecem apenas na memória e no conjunto de dados utilizado pelo dashboard, sendo sobrescritas a cada atualização executada.

A aplicação não mantém banco de dados próprio para armazenamento permanente das atividades coletadas.

---

## Atualizações e Sobrescrita

A cada atualização do dashboard:

1. Os dados são novamente consultados na API do Strava.
2. O conjunto de informações anterior é substituído pelos dados mais recentes disponíveis.
3. Não é mantido histórico separado fora do conjunto de dados utilizado pelo Power BI.

---

## Revogação de Acesso

O usuário pode revogar a autorização concedida ao aplicativo a qualquer momento através das configurações de sua conta Strava.

Após a revogação:

1. O aplicativo deixa de possuir autorização para consultar novas informações.
2. Na próxima atualização do dashboard, os dados do usuário deixam de ser retornados pela API.
3. Como o conjunto de dados é sobrescrito durante a atualização, as informações anteriormente disponíveis são automaticamente removidas do ambiente analítico.

Não é necessária nenhuma solicitação adicional para remoção dos dados após a revogação da autorização.

---

## Compartilhamento de Dados

Esta aplicação não vende, aluga ou compartilha dados pessoais com terceiros.

Os dados coletados são utilizados exclusivamente para fins de análise e visualização autorizados pelos próprios usuários.

---

## Segurança

O acesso aos dados é realizado exclusivamente através do mecanismo oficial de autenticação OAuth fornecido pelo Strava.

Em nenhum momento esta aplicação solicita, armazena ou possui acesso à senha da conta Strava do usuário.

---

## Alterações nesta Política

Esta Política de Privacidade poderá ser atualizada periodicamente para refletir alterações técnicas, operacionais ou exigências da plataforma Strava.

A versão mais recente estará sempre disponível neste repositório.

---

## Contato

Para dúvidas sobre esta Política de Privacidade ou sobre o tratamento dos dados coletados:

* E-mail: administrador.pbi@funcional.com
