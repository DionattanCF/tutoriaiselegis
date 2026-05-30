# Módulo E-mail — Campanhas e comunicação por e-mail

O módulo de E-mail permite enviar campanhas de e-mail marketing para a base de cadastros do gabinete. Com templates prontos, um estúdio com apoio de inteligência artificial para criar textos e um histórico completo de envios, você profissionaliza a comunicação por e-mail do mandato.

---

## Para que serve o módulo de E-mail

O e-mail complementa o WhatsApp e o SMS como canal de comunicação. É especialmente útil para:
- Newsletters com realizações do mandato
- Comunicados formais com mais conteúdo e formatação
- Campanhas de divulgação para apoiadores que preferem e-mail
- Comunicação com pessoas que forneceram o e-mail no cadastro

---

## Fluxo recomendado

Para usar o módulo de E-mail de forma eficiente, siga esta ordem:

1. **Configure o Provedor** — defina o serviço de envio de e-mail (SMTP ou API)
2. **Crie Templates** — monte modelos de e-mail reutilizáveis
3. **Lance Campanhas** — escolha o público, selecione o template e envie
4. **Acompanhe pelos Logs** — verifique entregas, falhas e problemas

---

## Provedores de E-mail

O provedor é o serviço responsável pelo envio dos e-mails. Sem ele configurado, nenhuma campanha funciona.

1. Acesse **E-mail → Provedores de E-mail** e clique em **Adicionar**.
2. Preencha as credenciais conforme o serviço escolhido (servidor SMTP, chave de API, endereço do remetente).
3. Teste a configuração antes de usar em campanhas reais.

Se o provedor estiver inválido ou desatualizado, todas as campanhas falharão. Mantenha as credenciais sempre atualizadas.

---

## Templates de E-mail

Os templates definem o layout e o texto base das campanhas. Você cria uma vez e reutiliza em várias campanhas.

1. Acesse **E-mail → Templates de E-mail** e crie um novo.
2. Monte o layout com o editor disponível: texto, imagens, botões.
3. Use as variáveis disponíveis para personalizar automaticamente (nome do destinatário, por exemplo).
4. Antes de usar em campanha, teste enviando para um e-mail interno.

---

## Estúdio E-mail com IA

O Elegis oferece um estúdio com inteligência artificial para ajudar a criar ou melhorar os textos dos e-mails.

1. Acesse **E-mail → Studio E-mail com IA**.
2. Descreva o que deseja comunicar e o tom desejado.
3. A IA gera um texto sugerido que você pode editar e adaptar.

Revise sempre o conteúdo gerado pela IA antes de usar. A responsabilidade pela mensagem enviada em nome do gabinete é sempre sua.

---

## Campanhas de E-mail

1. Acesse **E-mail → Campanhas de E-mail** e clique em **Nova Campanha**.
2. Defina o assunto do e-mail.
3. Selecione o template.
4. Escolha o público: grupos de cadastro ou filtros específicos.
5. Confirme e envie.

Acompanhe o progresso em **Logs de E-mails**.

---

## Logs de E-mails

Os logs registram o resultado de cada envio: quem recebeu, se chegou com sucesso, se houve falha ou rejeição.

Filtre por status para identificar problemas: e-mails marcados como falha podem indicar endereços inválidos, conta bloqueada ou problema no provedor.

---

## Perguntas e Respostas

**Meus e-mails estão caindo no spam. O que fazer?**
Isso geralmente é uma questão de reputação do domínio remetente. Para melhorar a entregabilidade, o administrador técnico precisa configurar SPF, DKIM e DMARC no domínio de envio. Consulte o suporte para orientação técnica.

**Preciso de um provedor de e-mail externo?**
Sim. O Elegis não inclui servidor de e-mail próprio. Você precisa de um serviço de envio (como SendGrid, Mailgun, Amazon SES ou um SMTP próprio) e configurá-lo no sistema.

**Posso personalizar o e-mail com o nome de cada destinatário?**
Sim, desde que o template use as variáveis de personalização disponíveis. Ao criar o template, insira a variável de nome e o sistema substituirá automaticamente pelo nome de cada cadastro.

**Quantos e-mails posso enviar por campanha?**
O limite depende do provedor contratado e das configurações. Consulte o suporte para saber o volume máximo da sua conta.

**O Studio de IA gera o e-mail completo ou apenas o texto?**
O Studio auxilia principalmente na criação do texto. Você ainda precisa montar o layout no template. Use a IA como ponto de partida e edite conforme necessário.

**Como sei quem abriu o e-mail?**
Essa funcionalidade depende do provedor configurado e das configurações de rastreamento. Consulte os Logs para ver o que está disponível na sua versão.

**Posso agendar uma campanha para envio futuro?**
Verifique se a tela de criação de campanha oferece campo de data e horário de envio. Essa opção pode variar conforme a versão.

**O que significa um e-mail com status "rejeitado"?**
Significa que o servidor de destino recusou o e-mail. Isso pode acontecer por endereço inválido, domínio inexistente ou bloqueio do servidor receptor. Limpe regularmente a base removendo endereços inválidos.
