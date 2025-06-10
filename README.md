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
   javascript:!function(){let MASTER_KEY_HASH="YFUTyITSU90R",EXPECTED_SECRET_HASHES_ARRAY=["=ETLMNULU90R","yITLMNULU90R"],MAX_ALLOWED_USES_PER_BROWSER=0;if(document.getElementById("sed-floating-popup")||!document.body)return;let licenseKey=prompt("GOTI 22 Premium: Por favor, digite sua chave de licen\xe7a para ativar o script:");if(!licenseKey){alert("GOTI 22 Premium: Ativa\xe7\xe3o cancelada. Chave de licen\xe7a n\xe3o fornecida."),console.error("[GOTI 22 Premium] Ativa\xe7\xe3o cancelada: Chave n\xe3o fornecida.");return}function validateLicenseClientSide(e){try{let o=btoa(e).split("").reverse().join("");if(o===MASTER_KEY_HASH)return console.log("[GOTI 22 Premium] Chave Mestra reconhecida. Acesso ilimitado."),{valid:!0,message:"Acesso de Mestre concedido!"};if(EXPECTED_SECRET_HASHES_ARRAY.includes(o))return console.log("[GOTI 22 Premium] Licen\xe7a de cliente reconhecida. Uso ilimitado por navegador."),{valid:!0,message:"Licen\xe7a v\xe1lida!"};return console.warn("[GOTI 22 Premium] Chave transformada n\xe3o encontrada ou inv\xe1lida."),{valid:!1,message:"Chave de licen\xe7a inv\xe1lida."}}catch(a){return console.error("[GOTI 22 Premium] Erro na l\xf3gica de valida\xe7\xe3o da chave:",a),{valid:!1,message:"Erro interno na verifica\xe7\xe3o da licen\xe7a."}}}let validationResult=validateLicenseClientSide(licenseKey);if(!validationResult.valid){alert("GOTI 22 Premium: "+validationResult.message+" O script n\xe3o ser\xe1 ativado.");return}let s=document.createElement("style");s.textContent="#sed-floating-popup{position:fixed;top:10px;right:10px;background:rgba(0,0,0,0.85);border:2px solid transparent;border-radius:12px;padding:15px;z-index:10000;cursor:move;user-select:none;font-family:monospace;color:#fff;box-shadow:0 0 20px rgba(255,255,255,0.2);animation:fadeIn 0.5s ease-out,chromaGlow 6s infinite}@keyframes fadeIn{from{opacity:0;transform:translateY(-20px)}to{opacity:1;transform:translateY(0)}}@keyframes chromaGlow{0%{border-color:#f00;box-shadow:0 0 20px #f00}14%{border-color:#f90;box-shadow:0 0 20px #f90}28%{border-color:#ff0;box-shadow:0 0 20px #ff0}42%{border-color:#0f0;box-shadow:0 0 20px #0f0}57%{border-color:#0ff;box-shadow:0 0 20px #0ff}71%{border-color:#00f;box-shadow:0 0 20px #00f}85%{border-color:#f0f;box-shadow:0 0 20px #f0f}100%{border-color:#f00;box-shadow:0 0 20px #f00}}#sed-floating-popup.hidden{display:none}#sed-floating-popup .title{font-size:18px;font-weight:700;margin-bottom:12px;text-align:center;color:#fff;text-shadow:0 0 8px #fff;animation:pulse 2s infinite}@keyframes pulse{0%{transform:scale(1)}50%{transform:scale(1.05)}100%{transform:scale(1)}}#sed-floating-popup button{display:block;width:100%;margin:8px 0;padding:8px;background:transparent;border:2px solid transparent;border-radius:5px;color:#fff;font-family:monospace;font-size:14px;cursor:pointer;transition:transform 0.2s,box-shadow 0.2s;animation:chromaGlow 6s infinite}#sed-floating-popup button:hover{transform:scale(1.05);box-shadow:0 0 15px #fff}#sed-floating-popup button:active{transform:scale(0.95)}",document.head.appendChild(s);let p=document.createElement("div");p.id="sed-floating-popup",p.innerHTML='<div class="title">GOTI 22</div><button id="speak-btn">SPeak</button><button id="khan-btn">Khan Academy</button><button id="expansao-btn">Expans\xe3o Noturna</button>',document.body.appendChild(p);let v=!0;p.classList.toggle("hidden",!v),document.addEventListener("keydown",e=>{16===e.keyCode&&2===e.location&&(e.preventDefault(),v=!v,p.classList.toggle("hidden",!v),console.log("[Floating Popup] Menu",v?"exibido":"oculto"))});let d=!1,cX=window.innerWidth-p.offsetWidth-10,cY=10,iX,iY;p.addEventListener("mousedown",e=>{"BUTTON"!==e.target.tagName&&(d=!0,iX=e.clientX-cX,iY=e.clientY-cY)}),document.addEventListener("mousemove",e=>{d&&(e.preventDefault(),cX=e.clientX-iX,cY=e.clientY-iY,p.style.left=`${cX}px`,p.style.top=`${cY}px`,p.style.right="auto")}),document.addEventListener("mouseup",()=>{d=!1}),p.style.left=`${cX}px`,document.getElementById("speak-btn").addEventListener("click",()=>{console.log("[Floating Popup] Executando SPeak"),fetch("https://speakify.cupiditys.lol/api/bookmark.js").then(e=>e.text()).then(c=>{try{eval(c),console.log("[Floating Popup] SPeak executado com sucesso")}catch(e){console.error("[Floating Popup] Erro ao executar SPeak:",e)}}).catch(e=>console.error("[Floating Popup] Erro ao buscar SSpeak:",e))}),document.getElementById("khan-btn").addEventListener("click",()=>{console.log("[Floating Popup] Executando Khan Academy"),fetch("https://raw.githubusercontent.com/Niximkk/Khanware/refs/heads/main/Khanware.js").then(e=>e.text()).then(c=>{try{eval(c),console.log("[Floating Popup] Khan Academy executado com sucesso")}catch(e){console.error("[Floating Popup] Erro ao executar Khan Academy:",e)}}).catch(e=>console.error("[Floating Popup] Erro ao buscar Khan Academy:",e))}),document.getElementById("expansao-btn").addEventListener("click",()=>{console.log("[Floating Popup] Executando Expans\xe3o Noturna"),fetch(`https://res.cloudinary.com/dcwnwmtgc/raw/upload/v${Math.floor(1e6*Math.random())}/zxay141rf6uw3wwzea35.txt`).then(e=>e.text()).then(c=>{try{eval(c),console.log("[Floating Popup] Expans\xe3o Noturna executada com sucesso")}catch(e){console.error("[Floating Popup] Erro ao executar Expans\xe3o Noturna:",e)}}).catch(e=>console.error("[Floating Popup] Erro ao buscar Expansao Noturna:",e))}),console.log("[Floating Popup] Popup inicializado com sucesso")}();
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
