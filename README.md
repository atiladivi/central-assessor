# Central do Assessor

Versão atual: **3.2.1** (21/10/2026) — lê os laudos do formulário até a Versão 75. Traz o Gerador de OS (0.6) no mesmo arquivo.

Abrir no navegador (Chrome ou Edge): https://atiladivi.github.io/central-assessor/

Arquivo único (`index.html`). A abertura leva a "Gerar uma OS", "Analisar um laudo" ou "Salvar o modelo". Os PDFs dos laudos são lidos no computador de quem usa; nada é enviado. As análises em andamento e o Registro de OS ficam guardados no navegador, separados por endereço: a Central aberta por este link não vê o que foi salvo abrindo o arquivo do computador, e vice-versa.

Conexões: a página só se conecta aos servidores do mapa das amostras (OpenFreeMap e Esri). A biblioteca do mapa (MapLibre 5.24.0) é carregada com a versão travada e o conteúdo conferido; qualquer outro envio é bloqueado pelo navegador.
