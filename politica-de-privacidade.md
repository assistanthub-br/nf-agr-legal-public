# Política de Privacidade — NF Agr

**Versão:** 1.0
**Última atualização:** 22/04/2026
**Vigência:** a partir de 22/04/2026

---

## 1. Quem somos

O **NF Agr** é um serviço de emissão de nota fiscal eletrônica (NF-e) para
produtores rurais, operado pela **ASSISTANTHUB LTDA**, inscrita no CNPJ `62.850.525/0001-73`, com sede em `R ELAINE RIBEIRO DA CRUZ, Nº 151, CEP 18236-291, SÃO MIGUEL ARCANJO - SP`.

Esta Política de Privacidade explica, de forma direta, quais dados pessoais
coletamos, por que coletamos, com quem compartilhamos, e quais são os seus
direitos sobre esses dados.

**Esta política se aplica aos dados em que a AssistantHub é controladora** —
ou seja, dados do próprio usuário que contrata o NF Agr (cadastro, autenticação,
cobrança, suporte). Para os dados que você insere no sistema sobre seus
compradores (destinatários de NF-e), a AssistantHub atua como **operadora**,
e a relação é regida pelo Acordo de Tratamento de Dados (DPA) que integra os
Termos de Uso.

---

## 2. Contato do Encarregado (DPO)

Em cumprimento ao art. 41 da LGPD, nosso Encarregado de Proteção de Dados pode
ser contatado em:

- **Email:** `ehnagata@assistanthub.com.br`
- **Responsável:** `Eduardo Hideki Nagata`

Use esse canal para exercer qualquer direito previsto nesta política, esclarecer
dúvidas sobre tratamento de dados, ou reportar incidentes.

---

## 3. Quais dados coletamos

### 3.1 Dados fornecidos por você

**No cadastro e operação:**
- Nome completo
- CPF e/ou CNPJ (para emissão de NF-e como obrigação fiscal)
- Email
- Telefone (opcional, para suporte e notificações)
- Endereço da propriedade rural
- Inscrição Estadual de Produtor Rural
- Certificado Digital A1 e sua senha — transmitidos ao nosso parceiro
  Tecnospeed no momento do cadastro. **A AssistantHub não armazena o arquivo
  do certificado nem a senha em seus próprios sistemas.** Veja detalhes na
  seção 7.
- Dados de atividade produtiva (o que você produz, para configuração do sistema)

**No pagamento:**
- Dados de cobrança (nome do titular, endereço de faturamento)
- Dados de cartão de crédito são coletados e armazenados **diretamente pelo
  Stripe**, nosso processador de pagamento. A AssistantHub não armazena número
  completo do cartão em seus sistemas.

**Na interação com o suporte e com a IA do sistema:**
- Conteúdo de mensagens enviadas ao suporte ou à IA assistente
- Histórico de conversas para melhoria do atendimento

### 3.2 Dados coletados automaticamente

- Endereço IP, tipo de navegador, sistema operacional
- Logs de acesso (data, hora, ações realizadas)
- Identificadores de dispositivo
- Dados de uso (funcionalidades acessadas, tempo de sessão)

### 3.3 Dados que **não** coletamos

Para transparência, esclarecemos explicitamente:
- **Não usamos seus dados para treinar modelos de inteligência artificial.**
- **Não vendemos seus dados a terceiros.**
- **Não compartilhamos seus dados com parceiros para fins de marketing.**

Caso, no futuro, alguma dessas práticas venha a ser considerada, ela dependerá
de **consentimento explícito e opcional** da sua parte, e sua recusa não
afetará o funcionamento do serviço.

---

## 4. Por que coletamos (finalidades e bases legais)

Cada tratamento de dados na AssistantHub tem uma base legal específica, conforme
o art. 7º da LGPD:

| Finalidade | Base Legal |
|------------|------------|
| Cadastro, autenticação e prestação do serviço | Execução de contrato (art. 7º, V) |
| Emissão de NF-e e transmissão à Sefaz | Cumprimento de obrigação legal (art. 7º, II) |
| Armazenamento de NF-e emitidas e XMLs | Cumprimento de obrigação legal (art. 7º, II) |
| Processamento de pagamentos | Execução de contrato (art. 7º, V) |
| Prevenção a fraude e segurança do sistema | Legítimo interesse (art. 7º, IX) |
| Atendimento ao suporte | Execução de contrato (art. 7º, V) |
| Comunicações transacionais (cobrança, avisos de sistema) | Execução de contrato (art. 7º, V) |
| Atendimento a autoridades mediante requisição legal | Cumprimento de obrigação legal (art. 7º, II) |
| Melhoria do produto com dados agregados e anonimizados | Legítimo interesse (art. 7º, IX) |

---

## 5. Com quem compartilhamos (subprocessadores)

Para operar o NF Agr, trabalhamos com fornecedores especializados que tratam
dados pessoais em nosso nome, sob contratos que garantem padrões adequados de
proteção. Abaixo, a lista dos nossos subprocessadores atuais:

| Subprocessador | Finalidade | Localização |
|----------------|-----------|-------------|
| **Microsoft Azure** | Hospedagem da aplicação, armazenamento, infraestrutura de computação | Brasil (Brazil South e Brazil Southeast) |
| **Microsoft Azure (conteúdo estático)** | Distribuição de páginas da landing page e interfaces web | Estados Unidos (Central US) — apenas conteúdo estático, sem dados pessoais |
| **Microsoft Foundry** | Serviço de inteligência artificial generativa usado pela IA assistente | Estados Unidos |
| **MongoDB Atlas (sobre AWS)** | Banco de dados principal | Brasil |
| **Tecnospeed / PlugNotas** | Custódia de Certificado Digital, assinatura e transmissão de NF-e à Secretaria da Fazenda | Brasil |
| **Google Identity Platform** | Autenticação de usuários (login) | Operação global do Google |
| **Stripe** | Processamento de pagamentos | Estados Unidos / operação global |

Esta lista pode ser atualizada. Alterações que envolvam adição de novos
subprocessadores seguem o procedimento descrito na seção 13 (Alterações desta
Política).

### 5.1 Compartilhamento com autoridades públicas

- **Secretaria da Fazenda (Sefaz):** dados de NF-e emitidas são transmitidos
  à Sefaz do estado correspondente, conforme exigência legal.
- **Outras autoridades:** apenas mediante requisição legal formal, por ordem
  judicial ou requisição de autoridade competente com fundamento legal.

---

## 6. Transferências internacionais

Parte da nossa infraestrutura opera fora do Brasil:

- **Microsoft Azure Static Web Apps (Central US, EUA):** hospeda apenas conteúdo
  estático (HTML, CSS, imagens) das páginas web. Não recebe dados pessoais.
- **Microsoft Foundry (`Estados Unidos`):** processa solicitações da IA
  assistente.
- **Stripe:** processa pagamentos em infraestrutura global.
- **Google Identity Platform:** opera em infraestrutura global do Google.

Estas transferências se dão com base no art. 33, II da LGPD (transferências para
organismos que oferecem garantias adequadas por meio de cláusulas contratuais
padrão e compromissos de proteção equivalentes aos da LGPD) e no art. 33, IX
(quando necessária à execução do contrato entre o titular e o controlador).

Todos os nossos subprocessadores internacionais são signatários de cláusulas
contratuais que estendem a eles as mesmas obrigações de proteção que assumimos
perante você.

---

## 7. Certificado Digital — custódia pela Tecnospeed

O Certificado Digital A1 e sua senha são o dado de maior sensibilidade no
processo de emissão de NF-e. Por essa razão, adotamos uma arquitetura de
**custódia especializada**:

- No momento do cadastro, você faz upload do certificado e informa a senha.
- Estes dados são **transmitidos ao nosso parceiro Tecnospeed** por canal
  criptografado (TLS 1.2+), que os custodia em sua própria infraestrutura
  especializada para assinatura de documentos fiscais.
- A **AssistantHub não armazena persistentemente o arquivo do certificado nem
  a senha** em seus sistemas. Os dados transitam apenas durante o envio ao
  parceiro.
- Cada solicitação de emissão de NF-e feita por você é encaminhada à Tecnospeed,
  que realiza a assinatura digital e a transmissão à Sefaz.

A Tecnospeed é uma empresa especializada em infraestrutura fiscal digital,
sujeita à LGPD e contratualmente obrigada a manter padrões adequados de
segurança para custódia de certificados digitais, incluindo criptografia em
repouso, controle de acesso e auditoria.

Essa separação arquitetural tem uma consequência prática importante: mesmo em
hipótese de incidente de segurança nos sistemas da AssistantHub, seu certificado
e sua senha permanecem protegidos, pois não residem em nossa infraestrutura.

---

## 8. Segurança

Adotamos medidas técnicas e administrativas para proteger seus dados, incluindo:

- Criptografia em trânsito (TLS 1.2+) em todas as comunicações
- Criptografia em repouso para dados sensíveis
- Controle de acesso baseado em papéis (RBAC) com isolamento por locatário
- Autenticação forte para acesso administrativo
- Registro e monitoramento de acessos
- Backups periódicos com política de retenção controlada
- Revisão periódica de segurança e correção de vulnerabilidades
- Processos documentados de resposta a incidentes

Nenhum sistema é absolutamente imune a falhas. Em caso de incidente de segurança
que possa acarretar risco ou dano relevante aos titulares, comunicaremos você e
a Autoridade Nacional de Proteção de Dados (ANPD) em prazo razoável, conforme
art. 48 da LGPD.

### 8.1 Sua parte na segurança da conta

A proteção dos seus dados depende também de práticas adequadas da sua parte no
uso do serviço. É sua responsabilidade:

- Escolher uma senha forte e única para acessar o NF Agr
- Não compartilhar suas credenciais com terceiros
- Manter seu dispositivo e navegador atualizados e livres de software malicioso
- Encerrar sua sessão ao usar computadores compartilhados
- Ativar autenticação de dois fatores (2FA) quando disponível
- Notificar imediatamente nosso suporte caso suspeite de acesso indevido à sua
  conta

Para te ajudar nessa tarefa, oferecemos: política de senha forte no cadastro,
possibilidade de troca de senha a qualquer momento, recuperação segura por
email validado e, conforme o plano, autenticação de dois fatores.

Acessos realizados com suas credenciais válidas são presumidamente feitos por
você ou por pessoa autorizada por você. A AssistantHub não responde por
consequências decorrentes de compartilhamento voluntário de credenciais, falta
de cuidado com dispositivos pessoais ou outras situações caracterizadas como
culpa exclusiva do titular ou de terceiro, nos termos do art. 43, III, da
LGPD. As condições contratuais detalhadas sobre responsabilidade pelo uso da
conta constam nos Termos de Uso.

---

## 9. Por quanto tempo guardamos seus dados

| Categoria de dado | Prazo de retenção | Fundamento |
|-------------------|-------------------|------------|
| Dados de cadastro e conta | Durante a vigência do contrato + 5 anos após encerramento | Prazo prescricional do Código Civil |
| NF-e emitidas e XMLs | Mínimo de 5 anos após emissão | Obrigação fiscal |
| Dados de cobrança e pagamento | 5 anos após a transação | Código Tributário Nacional |
| Logs de acesso e auditoria | 6 meses a 2 anos | Marco Civil da Internet (art. 15) |
| Histórico de interação com suporte e IA | 2 anos | Legítimo interesse para qualidade do serviço |
| Certificado Digital A1 e senha | Não armazenados pela AssistantHub | Custódia é da Tecnospeed (seção 7) |

Após os prazos aplicáveis, os dados são eliminados ou anonimizados, exceto
quando a legislação exigir retenção adicional.

---

## 10. Seus direitos

Conforme o art. 18 da LGPD, você tem direito a:

- **Confirmar** a existência de tratamento dos seus dados
- **Acessar** os dados que temos sobre você
- **Corrigir** dados incompletos, inexatos ou desatualizados
- **Anonimizar, bloquear ou eliminar** dados desnecessários, excessivos ou
  tratados em desconformidade com a LGPD
- **Portar** seus dados a outro fornecedor
- **Eliminar** dados tratados com base em consentimento
- **Ser informado** sobre com quem compartilhamos seus dados
- **Ser informado** sobre a possibilidade de não fornecer consentimento e suas
  consequências
- **Revogar** consentimento, quando o tratamento for baseado nele

Para exercer qualquer destes direitos, envie solicitação ao email do Encarregado
(seção 2). Respondemos em até **15 dias**, conforme determina a ANPD.

Algumas solicitações podem não ser atendidas integralmente quando houver
obrigação legal de retenção (por exemplo, não podemos eliminar NF-e emitidas
dentro do prazo de obrigação fiscal), mas explicaremos o fundamento sempre que
isso ocorrer.

---

## 11. Cookies e tecnologias similares

Nosso site (`nf.agr.br`) e aplicação usam cookies e tecnologias similares para
funcionamento, autenticação, e análise de uso.

---

## 12. Crianças e adolescentes

O NF Agr é destinado a produtores rurais maiores de 18 anos e não coleta
intencionalmente dados de crianças ou adolescentes. Caso identifique tratamento
acidental de dados de menores, entre em contato com nosso Encarregado para
remoção imediata.

---

## 13. Alterações desta Política

Podemos atualizar esta política periodicamente. Alterações seguem processo
documentado em nosso repositório público de documentos legais, com as seguintes
garantias:

- **Alterações materiais** (novas finalidades, novos subprocessadores, mudanças
  em bases legais, mudanças em prazos de retenção) são comunicadas com **30 dias
  de antecedência** antes de entrarem em vigor, por email aos usuários ativos.
- **Alterações editoriais** (correções de redação, ajustes de formatação) são
  aplicadas imediatamente, sem notificação prévia.
- Todo o histórico de versões desta política é público e versionado em Git,
  acessível em [https://github.com/assistanthub-br/nf-agr-legal-public](https://github.com/assistanthub-br/nf-agr-legal-public).
- Cada versão é identificada por um hash único, permitindo que você saiba
  exatamente qual versão aceitou no momento do cadastro e qual está vigente.

Sua permanência no uso do serviço após a entrada em vigor de uma alteração
material implica aceite da nova versão. Se você não concordar com uma alteração,
poderá cancelar sua assinatura antes da data de vigência, sem custo adicional, e
nós preservaremos o acesso aos seus dados (incluindo XMLs de NF-e emitidas) pelo
prazo legal exigido.

---

## 14. Autoridade Nacional de Proteção de Dados

Você tem o direito de apresentar reclamação à ANPD sobre o tratamento dos seus
dados:

- Site: [gov.br/anpd](https://www.gov.br/anpd/pt-br)

Encorajamos você a entrar em contato primeiro com nosso Encarregado, para que
possamos resolver diretamente qualquer questão.

---

## 15. Legislação aplicável e foro
 
Esta Política de Privacidade é regida pela legislação brasileira, em especial
pela Lei Geral de Proteção de Dados (Lei 13.709/2018), pelo Marco Civil da
Internet (Lei 12.965/2014) e pelo Código de Defesa do Consumidor (Lei 8.078/1990),
quando aplicável.
 
Fica eleito o foro da Comarca de São Miguel Arcanjo, Estado de São Paulo, para
dirimir quaisquer questões oriundas desta política. Esta eleição não afasta o
direito do titular consumidor, pessoa física, de ajuizar demanda no foro do
seu próprio domicílio, conforme lhe assegura a legislação aplicável.

---

*Documento versionado em `nf-agr-legal-public`. Para o histórico completo de
alterações, consulte o log de commits do repositório.*
