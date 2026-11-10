# Smoothr · plugin para Premiere Pro

Dá curva aos keyframes do Premiere com um gráfico de velocidade, como no After Effects: 8 prontos editáveis, suas curvas e keyframe a cada 1, 2 ou 3 frames.

Funciona no Mac e no Windows, com o Premiere em qualquer idioma.

## Instalar: escolha um jeito

### Jeito 1: pelo Claude (sem baixar nada)
Copie o link desta página e cole no Claude Code com a frase **"instala esse plugin para mim"**:

```
https://github.com/Edueditor/smoothr-updates
```

O Claude segue as instruções da seção *Para o Claude* abaixo.

### Jeito 2: pelo zip
1. Baixe o **[Smoothr_completo.zip](https://github.com/Edueditor/smoothr-updates/releases/latest/download/Smoothr_completo.zip)**. Ele traz o plugin, o guia em PDF e o atalho para o ZXP Installer.
2. Se ainda não tem o ZXP Installer, abra `Baixar_ZXP_Installer.html`.
3. Feche o Premiere, arraste o `Smoothr.zxp` para o ZXP Installer e abra o Premiere.
4. No Premiere, vá em **Window → Extensions → Smoothr**.

Arquivos soltos: [Smoothr.zxp](https://github.com/Edueditor/smoothr-updates/releases/latest/download/Smoothr.zxp) · [Guia em PDF](https://github.com/Edueditor/smoothr-updates/releases/latest/download/Como_instalar_o_Smoothr.pdf) · [Baixar ZXP Installer](https://github.com/Edueditor/smoothr-updates/releases/latest/download/Baixar_ZXP_Installer.html)

Atualizações: o próprio plugin avisa quando sai uma versão nova.

---

## Para o Claude (instalação automática)
O usuário colou este link e quer o Smoothr instalado. Siga estes passos:
1. Baixe `https://github.com/Edueditor/smoothr-updates/releases/latest/download/Smoothr.zxp`. É um zip assinado.
2. Peça para o usuário fechar o Premiere Pro e espere ele confirmar.
3. Se já existir uma pasta antiga, apague-a. Depois extraia o conteúdo do `.zxp` sem alterar nenhum arquivo (a assinatura depende disso) em:
   - Mac: `~/Library/Application Support/Adobe/CEP/extensions/com.smoothr.premiere`
   - Windows: `%APPDATA%\Adobe\CEP\extensions\com.smoothr.premiere`
4. Não mexa na pasta de dados do plugin (Mac: `~/Library/Application Support/Smoothr`, Windows: `%APPDATA%\Smoothr`). Ali ficam os presets do usuário.
5. Confira se `CSXS/manifest.xml` existe na pasta nova e diga qual versão ele mostra.
6. Avise o usuário para abrir o Premiere e ir em Window → Extensions → Smoothr.
