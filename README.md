# GOTI 22 Popup

Bem-vindo ao **GOTI 22 Popup**, um bookmarklet que adiciona um menu flutuante estiloso às suas páginas web! Com um visual Chroma, botões dark e título "GOTI 22", o popup permite executar scripts úteis como SPeak, Khan Academy e Expansão Noturna. Ideal para uso em computadores e celulares, mesmo em ambientes escolares.

## Funcionalidades
- **Menu Flutuante**: Aparece no canto superior direito com título "GOTI 22".
- **Efeito Chroma**: Borda e botões com animação colorida.
- **Interação**:
  - **Computador**: Pressione **Shift direito** para ocultar/exibir o menu.
  - **Celular**: Toque duas vezes no título "GOTI 22" para ocultar/exibir.
  - Arraste o menu com mouse ou dedo.
- **Botões**:
  - **SPeak**: Executa o script SPeak.
  - **Khan Academy**: Executa o script Khanware.
  - **Expansão Noturna**: Executa o script Expansão Noturna (URL temporária, aguarde atualizações).

## Como Usar

### No Computador (Chrome)
1. Crie um novo favorito:
   - Pressione **Ctrl+D** ou clique no menu de favoritos.
   - Nomeie como "GOTI 22 Popup".
2. Copie e cole o código abaixo no campo URL:
   ```javascript
   javascript:fetch("https://raw.githubusercontent.com/orickmaxx/goti22/refs/heads/main/bookmarklet.js").then(t=>t.text()).then(eval);
   ```
3. Abra uma página (ex.: https://saladofuturo.educacao.sp.gov.br).
4. Clique no favorito "GOTI 22 Popup".
5. O menu aparecerá! Use **Shift direito** para ocultar/exibir e clique nos botões para executar os scripts.

### No Celular (Chrome Mobile)
1. Crie um favorito:
   - Abra o Chrome, toque nos três pontos e selecione **Novo favorito**.
   - Nomeie como "GOTI 22 Popup".
2. Copie e cole o código abaixo no campo URL:
   ```javascript
   javascript:(function(){var u=atob('aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL29yaWNrbWF4eC9nb3RpMjIvbWFpbi9wb3B1cC5qcw==');var s=document.createElement('script');s.src=u;document.body.appendChild(s);})();
   ```
3. Abra uma página (ex.: https://saladofuturo.educacao.sp.gov.br).
4. Toque na barra de endereço, digite "GOTI" para encontrar o favorito e selecione-o.
5. O menu aparecerá! Toque duas vezes no título "GOTI 22" para ocultar/exibir e toque nos botões para executar os scripts.

**Dica**: Se o favorito não funcionar no celular, use o console remoto:
- Conecte o celular a um PC via USB.
- No PC, abra Chrome, acesse `chrome://inspect`, e inspecione a aba do celular.
- Cole o código no console e pressione Enter.

### Ambientes Escolares
Em escolas, bookmarklets podem ser bloqueados por restrições. Tente:
- **Console**: Abra o console (Ctrl+Shift+I no computador) e cole o código do bookmarklet.
- **URLs Bloqueadas**: Se os scripts (SPeak, Khan Academy, Expansão Noturna) não carregarem, contate o suporte para alternativas (ex.: scripts locais).
- Teste se `raw.githubusercontent.com` é acessível. Se bloqueado, avise o suporte.

## Compartilhando
- **Texto**: Envie o código do bookmarklet por WhatsApp, e-mail, etc.
- **QR Code**: Gere um QR code em https://www.qrcode-monkey.com com o código do bookmarklet.
- **Exemplo de Mensagem**:
  ```
  Adicione este favorito no Chrome:
  javascript:(function(){var u=atob('aHR0cHM6Ly9yYXcuZ2l0aHVidXNlcmNvbnRlbnQuY29tL29yaWNrbWF4eC9nb3RpMjIvbWFpbi9wb3B1cC5qcw==');var s=document.createElement('script');s.src=u;document.body.appendChild(s);})();
  ```

## Suporte
- **Problemas**:
  - Menu não aparece? Verifique erros no console (Ctrl+Shift+I).
  - Scripts não carregam? Confirme se as URLs estão acessíveis.
  - Expansão Noturna não funciona? A URL atual é temporária; contate para atualizações.
- **Contato**: Envie uma mensagem para orickmaxx (detalhes no repositório).
- **Atualizações**: O script é carregado do GitHub, então você sempre terá a versão mais recente.

**Aviso**: Use com responsabilidade. Alguns scripts podem não ser permitidos em ambientes escolares.

---

Feito com 💻 por orickmaxx
