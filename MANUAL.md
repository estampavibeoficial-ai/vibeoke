# 🎤 VibeOkê — Manual de Instruções

> Sistema profissional de karaokê para Windows com download do YouTube, legendas sincronizadas e sistema de pontuação.

---

## Índice

1. [Requisitos do Sistema](#requisitos-do-sistema)
2. [Instalação](#instalação)
3. [Ativação da Licença](#ativação-da-licença)
4. [Configurando sua Pasta de Músicas](#configurando-sua-pasta-de-músicas)
5. [Como Adicionar Músicas](#como-adicionar-músicas)
6. [Baixando Músicas do YouTube](#baixando-músicas-do-youtube)
7. [Adicionando Legendas](#adicionando-legendas)
8. [Usando o Karaokê](#usando-o-karaokê)
9. [Fila de Músicas](#fila-de-músicas)
10. [Pontuação e Resultados](#pontuação-e-resultados)
11. [Personalização](#personalização)
12. [Suporte](#suporte)

---

## Requisitos do Sistema

| Item | Mínimo | Recomendado |
|------|--------|-------------|
| Sistema | Windows 10 64-bit | Windows 11 64-bit |
| Processador | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| Memória RAM | 4 GB | 8 GB |
| Armazenamento | 500 MB (app) + espaço para vídeos | SSD com 10 GB+ |
| Internet | Necessária para download de músicas | Banda larga |

---

## Instalação

1. Baixe o arquivo **`VibeOke Setup 1.0.0.exe`** na página de [Releases](https://github.com/estampavibeoficial-ai/vibeoke/releases/latest)
2. Execute o instalador como **Administrador** (clique com botão direito → *Executar como administrador*)
3. Escolha a pasta de instalação e clique em **Instalar**
4. Aguarde — o instalador irá configurar automaticamente todas as ferramentas necessárias
5. Ao finalizar, o VibeOkê estará disponível na **Área de Trabalho** e no **Menu Iniciar**

> ⚠️ **Importante:** Durante a instalação é necessário conexão com a internet para baixar as ferramentas de download (yt-dlp e ffmpeg).

---

## Ativação da Licença

Na primeira vez que abrir o VibeOkê, você verá a tela de ativação.

### Período de Avaliação (Trial)

Clique em **"Iniciar Trial de 7 dias"** para usar o app gratuitamente por 7 dias com todas as funcionalidades disponíveis.

### Ativando com Licença Completa

1. Na tela de ativação, localize seu **ID do Computador**
2. Copie o ID clicando em **📋 Copiar ID**
3. Entre em contato com o vendedor informando:
   - Seu **nome completo**
   - **Comprovante** de compra
   - O **ID do Computador** copiado
4. Você receberá uma chave no formato: `VIBE-XXXX-XXXX-XXXX-XXXX`
5. Digite a chave no campo indicado e clique em **🔐 ATIVAR LICENÇA**

> 💡 **Onde comprar:** Acesse nossa loja no [Mercado Livre](https://mercadolivre.com.br)

---

## Configurando sua Pasta de Músicas

Ao abrir o app pela primeira vez, uma pasta **Musicas** é criada automaticamente na pasta de instalação.

Para usar uma pasta diferente:

1. No menu principal, clique em **📂 Pasta** no cabeçalho
2. Navegue até a pasta desejada e clique em **Selecionar Pasta**
3. O repertório será carregado automaticamente

---

## Como Adicionar Músicas

Coloque seus arquivos de vídeo diretamente na pasta de músicas configurada.

### Formatos de Vídeo Suportados

| Formato | Extensão |
|---------|----------|
| MP4 | `.mp4` |
| Matroska | `.mkv` |
| AVI | `.avi` |
| WebM | `.webm` |
| QuickTime | `.mov` |

### Nomenclatura dos Arquivos

Para organização automática no repertório, nomeie seus arquivos assim:

```
001 - Artista - Nome da Música.mp4
002 - Roberto Carlos - Emoções.mp4
003 - Bon Jovi - It's My Life.mp4
```

| Parte | Descrição |
|-------|-----------|
| `001` | Código numérico para busca rápida |
| `Artista` | Nome do artista ou banda |
| `Nome da Música` | Título da música |

> ✅ O app aceita qualquer nome de arquivo, mas o formato acima permite busca por código numérico no numpad.

---

## Baixando Músicas do YouTube

O VibeOkê permite baixar vídeos de karaokê diretamente do YouTube.

1. No menu principal, clique em **⬇ YouTube** no cabeçalho
2. Digite o nome do artista ou música na barra de busca
   - Ex: `Queen`, `Bon Jovi`, `Roberto Carlos`
3. O sistema buscará automaticamente por vídeos de **karaokê**
4. Nos resultados, clique em **⬇ MP4** no vídeo desejado
5. Acompanhe o progresso do download:
   - 📥 Baixando vídeo...
   - 📥 Baixando áudio...
   - 🔄 Juntando áudio e vídeo...
   - ✅ Concluído!
6. O arquivo MP4 completo é salvo automaticamente na sua pasta de músicas
7. Clique em **↻ Atualizar** no menu para ver a nova música no repertório

> ⚠️ O download respeita os termos de uso do YouTube. Use apenas para fins pessoais.

---

## Adicionando Legendas

As legendas sincronizam automaticamente com o vídeo durante o karaokê.

### Legenda Automática

Se o arquivo de legenda tiver o **mesmo nome** do vídeo, é detectado automaticamente:

```
Pasta de Músicas/
├── 001 - Queen - Bohemian Rhapsody.mp4
└── 001 - Queen - Bohemian Rhapsody.srt   ← detectada automaticamente!
```

### Formatos Suportados

| Formato | Extensão | Descrição |
|---------|----------|-----------|
| SubRip | `.srt` | Mais comum e compatível |
| WebVTT | `.vtt` | Padrão web |

### Adicionando Legenda Durante a Música

No player, clique nos botões na barra inferior:

- **📂 Importar** — abre um arquivo `.srt` ou `.vtt` do seu computador
- **✏️ Criar** — abre o editor para digitar a legenda manualmente

### Formato SRT (exemplo)

```
1
00:00:05,000 --> 00:00:08,500
Primeira linha da música

2
00:00:09,000 --> 00:00:12,000
Segunda linha da música
```

### Ativar/Desativar Legenda

No player, clique em **LEG: ✓** para ativar ou desativar a exibição.

---

## Usando o Karaokê

### Selecionando uma Música

**Por código numérico:**
1. Digite o código da música no **numpad** da esquerda (ex: `001`)
2. O preview aparece abaixo do display
3. Clique em **▶ OK** ou pressione **Enter**

**Por busca:**
1. Digite na caixa de busca o nome do artista ou título
2. Clique na música desejada para selecioná-la
3. Dê um **duplo clique** para iniciar direto, ou selecione e clique **▶ OK**

**Pelo teclado físico:**
- Teclas `0–9` — digitar o código
- `Backspace` — apagar último dígito
- `Enter` — confirmar seleção

### Controles do Player

| Botão | Ação |
|-------|------|
| ▶ Play / ⏸ Pausar | Iniciar ou pausar a música |
| ↩ Reiniciar | Volta para o início |
| ← Menu | Volta para o repertório |
| ✓ Finalizar | Encerra e vai para o resultado |
| `F11` | Alternar tela cheia |

### Barra de Progresso

Clique em qualquer ponto da barra no topo para pular para aquele momento da música.

---

## Fila de Músicas

Adicione músicas na fila enquanto uma está tocando — perfeito para festas!

1. Durante uma música, clique em **⏭ Fila** na barra de controles
2. No mini-menu que aparece, digite o código da próxima música
3. Confirme com **✓**
4. A música entra na fila exibida no rodapé do player
5. Ao terminar a música atual, a próxima da fila inicia **automaticamente**

> 💡 Você pode adicionar várias músicas na fila sem interromper a que está tocando.

---

## Pontuação e Resultados

Ao finalizar uma música, a tela de resultados exibe:

### Placar

O contador sobe animado do zero até sua pontuação final **(0 a 100 pontos)**.

### Classificação por Estrelas

| Estrelas | Pontuação | Mensagem |
|----------|-----------|----------|
| ⭐⭐⭐⭐⭐ | 92–100 | 🏆 LENDÁRIO! |
| ⭐⭐⭐⭐ | 80–91 | 🔥 INCRÍVEL! |
| ⭐⭐⭐ | 68–79 | 🎤 MUITO BOM! |
| ⭐⭐ | 50–67 | 👏 BOA PERFORMANCE! |
| ⭐ | 30–49 | 🎵 BOM COMEÇO! |
| ⭐ | 0–29 | 💪 CONTINUE! |

### Estatísticas

- **Timing** — precisão no ritmo
- **Afinação** — qualidade vocal
- **Estilo** — performance geral

### Ranking da Sessão

Todas as músicas cantadas na sessão ficam no ranking, ordenadas pela pontuação.

### Ações

- **🎵 Nova Música** — volta ao repertório
- **↩ Repetir** — canta a mesma música de novo

---

## Personalização

### Tema Claro / Escuro

Clique no toggle **🌙/☀️** na barra de título para alternar entre os temas. A preferência é salva automaticamente.

### Fundo de Vídeo Animado

Na tela do repertório, o fundo exibe trechos dos seus vídeos de karaokê em loop.

- **🎬 Fundo On** — clique para desativar
- **⬛ Fundo Off** — clique para ativar

A preferência é salva automaticamente.

### Tela Cheia

- Pressione **F11** para alternar tela cheia
- O app inicia sempre em tela cheia por padrão

---

## Suporte

Está com algum problema ou dúvida? Entre em contato:

| Canal | Contato |
|-------|---------|
| 💬 WhatsApp | (11) 99999-9999 |
| ✉️ E-mail | contato@vibeoke.com.br |
| 🛒 Mercado Livre | [Acessar loja](https://mercadolivre.com.br) |

**Horário de atendimento:** Segunda a Sexta, 9h às 18h

---

### Perguntas Frequentes

**O app não abre após a instalação.**
> Tente executar como Administrador. Clique com botão direito no ícone → *Executar como administrador*.

**O download do YouTube não tem áudio.**
> Verifique se o ffmpeg foi instalado corretamente. Desinstale e reinstale o VibeOkê.

**A legenda não aparece.**
> Confirme que o arquivo de legenda tem exatamente o mesmo nome do vídeo, apenas com extensão `.srt` ou `.vtt`.

**A chave de ativação não funciona.**
> A chave é vinculada ao seu computador. Verifique se está usando no mesmo PC onde gerou o ID. Entre em contato com o suporte se precisar transferir a licença.

**O vídeo fica preto durante a música.**
> O formato do vídeo pode não ser suportado. Converta para MP4 usando um conversor online e tente novamente.

---

*VibeOkê © 2025 — Todos os direitos reservados*
