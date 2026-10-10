# Meu Espaço: guia de uso

## 1. O que é

O Meu Espaço é um aplicativo pessoal para o celular, que funciona no navegador e pode ser instalado na tela inicial. Ele reúne:

- **Meu Caderno:** notas com pastas, favoritos e pesquisa.
- **Minhas Músicas:** composições em andamento e músicas concluídas, com data de conclusão.
- **Meu Espaço com Jeová:** diário de orações, "Tudo de bom que Jeová me deu" (gratidão do dia) e reflexões espirituais.
- **Meu Diário Emocional:** registro de humor e desabafos livres.
- **Meu Baú de Versículos:** versículos que você digita e organiza por situação.
- **Meu Assistente Criativo:** vocabulário, rimas, imagens poéticas e organização de pensamentos.
- **Gravador de áudio:** ideias musicais gravadas direto no app.
- **Ajustes:** modo escuro, instalação, exportar e importar backup.

## 2. Onde seus dados ficam

Seus registros ficam **somente no navegador do seu celular**, no armazenamento interno do app. Nenhuma conta é necessária e nada é enviado para nuvem ou para servidores.

**Atenção:** esses dados podem ser perdidos se você:
- limpar os dados do navegador para o site do app;
- desinstalar o app;
- trocar de celular ou perder o aparelho;
- o sistema apagar dados por falta de espaço (o app pede armazenamento protegido, mas o sistema pode recusar).

Por isso, **faça um backup regularmente** (veja a seção 5).

## 3. Como abrir e instalar

**Endereço:** https://neondkmusic-max.github.io/meu-espaco/

**Instalar na tela inicial:**
- **Android (Chrome):** toque nos três pontos e escolha **Instalar app**. Ou vá em **Ajustes > Instalar** dentro do app.
- **iPhone (Safari):** toque em **Compartilhar** e depois em **Adicionar à Tela de Início**.

Depois de instalado, o app abre pelo ícone, sem a barra do navegador.

**Usar sem internet:** abra o app uma vez com internet. Depois, ele funciona sem conexão. Para atualizações, quando houver internet, o app busca a versão nova.

## 4. Uso rápido

- **Início:** atalhos para nova nota, oração, gratidão, humor, gravação e música.
- **Barra inferior:** Início, Caderno, Músicas, Diário e Ajustes.
- **Salvamento:** notas, desabafos e orações são salvos enquanto você escreve. Os outros registros são salvos ao tocar em **Salvar** ou ao sair da tela.
- **Excluir:** sempre pede confirmação.
- **Favoritos:** toque na estrela nos cartões ou dentro do registro.

### Gravador de áudio
- Toque em **Gravar áudio** na tela inicial.
- **Iniciar gravação** pede permissão do microfone. A permissão só é pedida nesse momento.
- **Pausar** e **Continuar** funcionam quando o navegador permite.
- **Finalizar** salva o áudio no aparelho. Você pode dar um título e associar a uma música ou nota.
- Se você sair da tela enquanto grava, o app finaliza e salva a gravação.
- Cada minuto ocupa cerca de 0,5 a 1 MB.

### Assistente criativo
- **Vocabulário, Rimas, Imagens e Organizar** funcionam sem internet.
- **IA externa (opcional):** só é usada se você tocar em "Reescrever com IA externa" ou "Criar versos com IA externa". O app mostra o texto completo, pede sua autorização a cada uso e copia o texto para você colar no serviço escolhido. Nada é enviado automaticamente.

## 5. Backup (muito importante)

**Exportar:** em **Ajustes > Exportar backup**. O arquivo é salvo em **Downloads**. Se houver gravações, o arquivo é um ZIP com os áudios. Se não houver, é um JSON.

**Onde guardar:** envie para o Google Drive, para o seu e-mail ou para o computador. Não deixe só no celular.

**Quando fazer:** pelo menos uma vez por mês, e sempre antes de trocar de celular, limpar o navegador ou atualizar o app.

**Importar:** em **Ajustes > Importar backup**, escolha o arquivo. O app mostra o que tem no backup antes de qualquer mudança.
- **OK** (mesclar): adiciona os registros aos atuais.
- **Cancelar** e depois **OK** na segunda pergunta: substitui todos os dados atuais. Use só se tiver certeza.

## 6. Permissões

- **Microfone:** pedido somente ao tocar em "Iniciar gravação".
- **Armazenamento protegido:** o app pede ao navegador que mantenha seus dados. O navegador decide se aceita.
- **Nenhuma outra permissão** é usada.

## 7. Custos

| Item | Custo |
|---|---|
| Aplicativo e hospedagem no GitHub Pages | R$ 0,00 |
| Instalação na tela inicial | R$ 0,00 |
| Armazenamento no aparelho | R$ 0,00 |
| Backup (arquivo no seu Drive ou computador) | R$ 0,00, se usar um serviço gratuito |
| IA externa (Gemini, ChatGPT, Copilot), opcional | R$ 0,00 nos planos gratuitos, que podem ter limites e mudar |

Nenhuma assinatura ou API paga é necessária.

## 8. O que ainda não está incluído

- **Gráfico de humor:** não implementado. A lista em linha do tempo funciona.
- **Histórico da evolução de uma música:** não implementado.
- **Filtro por data no portfólio:** a busca por título e gênero funciona, mas não há filtro de data.
- **Reescrita automática de texto e criação de versos:** só com IA externa, de forma manual e opcional.
- **Vocabulário e rimas:** são limitados. As rimas são aproximadas em alguns casos. Ferramentas mais completas exigem um serviço externo.
- **Gravações ao vivo em caso de fechamento do navegador:** se o navegador fechar no meio de uma gravação, o áudio pode se perder. Finalize antes de sair.
- **Textos bíblicos:** o app não traz textos da Bíblia. Você digita os versículos, e eles não são criados automaticamente.

## 9. Atualizar o aplicativo

Quando houver uma nova versão, substitua no GitHub os arquivos indicados (geralmente `index.html`, e `sw.js` se for avisado). Feche o app por completo e abra de novo. Seus dados são mantidos, mas faça um backup antes de qualquer atualização.

## 10. Roteiro de testes (Etapa 8)

Marque cada item e me conte o resultado. Se algo falhar, diga o passo e a mensagem que apareceu.

**Instalação e uso**
- [ ] O app abre pelo endereço do GitHub.
- [ ] Foi instalado e abre pelo ícone, sem barra do navegador.
- [ ] A navegação pela barra inferior funciona.
- [ ] O modo escuro muda o visual e permanece após fechar o app.

**Dados**
- [ ] Criar nota, fechar o app completamente, reabrir e confirmar que a nota continua.
- [ ] Editar e excluir uma nota de teste (com confirmação).
- [ ] Gratidão, oração, versículo e registro de humor salvos após reabrir.

**Offline**
- [ ] Ativar o modo avião e abrir o app pelo ícone.
- [ ] Consultar e criar registros sem internet.

**Gravador**
- [ ] Gravar 20 segundos, pausar, continuar e finalizar.
- [ ] Dar título e associar a uma música.
- [ ] Ouvir a gravação depois de reabrir o app.
- [ ] Excluir uma gravação de teste.

**Backup**
- [ ] Exportar backup e encontrar o arquivo em Downloads.
- [ ] Importar o mesmo arquivo com a opção **mesclar** e confirmar que nada foi perdido.

**Assistente**
- [ ] Vocabulário, Rimas e Imagens retornam resultados.
- [ ] Os botões de Organizar funcionam.
- [ ] A IA externa mostra o texto completo e só envia após a autorização.

Quando todos estiverem marcados, o app está pronto para uso diário. Se algum item não funcionar, a lista acima ajuda a localizar o problema.
