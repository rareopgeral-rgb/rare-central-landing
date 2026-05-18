# Rare Central — Manual de Instalação (Windows)

> **VERSÃO BETA — USO INTERNO RARE**
> Este software é exclusivo para a equipe Rare Company.
> **Não poste prints ou vídeos nos stories.**
> Envie feedback de uso no grupo do WhatsApp da equipe.

---

## O que é o Rare Central

Rare Central é a ferramenta interna da Rare para produção de vídeos em escala.
Com ela você concatena hooks, bodies e CTAs, corta silêncios automaticamente,
aplica velocidade e gera legendas com IA — tudo em minutos.

---

## Requisitos

- Windows 10 ou superior (64-bit)
- Conexão com internet (para legendas via AssemblyAI)
- Conta com acesso liberado pela administração Rare

---

## Instalação

### Opção A — Executável direto (recomendado)

1. Baixe o arquivo `RareCentral-Windows.exe` pelo link fornecido pelo time
2. Dê dois cliques para abrir
3. Se o Windows Defender exibir um aviso azul *"O Windows protegeu seu PC"*:
   - Clique em **Mais informações**
   - Clique em **Executar assim mesmo**
4. O app abre direto no navegador padrão

### Opção B — Pasta completa (.zip)

1. Baixe o arquivo `RareCentral-Windows.zip`
2. Clique com botão direito → **Extrair tudo**
3. Abra a pasta extraída e execute `RareCentral.exe`

> **Dica:** Fixe o executável na barra de tarefas para acesso rápido.

---

## Configurar API Key (legendas)

Para usar a função de legendas automáticas:

1. Acesse **assemblyai.com** e crie uma conta gratuita
2. No dashboard, vá em **API Keys** e copie sua chave
3. No Rare Central, clique em **Configurações** na barra lateral
4. Cole a chave no campo **AssemblyAI API Key** e salve

> O plano gratuito da AssemblyAI oferece 100 horas/mês — mais que suficiente.

---

## Como usar

### Passo 1 — Selecionar modo
- **FF:** Hook + Body + CTA (3 arquivos por vídeo)
- **HeyGen:** Hook + Body (2 arquivos, para vídeos com avatar)

### Passo 2 — Subir os arquivos
Arraste ou clique nas áreas de upload para cada categoria.
O app combina 1 hook + 1 body + 1 CTA por vez (na ordem dos nomes).

### Passo 3 — Escolher opções
| Opção | O que faz |
|---|---|
| **Legendas** | Transcreve e queima legendas no vídeo (requer API key) |
| **Remover Metadados** | Nome do arquivo vira UUID (anonimiza origem) |
| **Velocidade** | Acelera o vídeo (1.15x recomendado) |
| **Corte Final** | Remove os últimos milissegundos de cada clipe |
| **Cortar Silêncio** | Remove pausas e silêncios automaticamente |

### Passo 4 — Iniciar e baixar
Clique em **Iniciar** e acompanhe o log em tempo real.
Quando aparecer **"Pronto!"**, clique em **Baixar vídeos (.zip)**.

---

## Problemas comuns

**Windows bloqueou o app**
→ Clique em "Mais informações" → "Executar assim mesmo"

**O app não abre / antivírus bloqueou**
→ Adicione o executável como exceção no antivírus

**Legenda falhou**
→ Verifique se a API key está configurada em Configurações

---

## Feedback

Manda o feedback de uso no grupo:
**https://chat.whatsapp.com/FQPpcUtqlq23P79yybB81Y**

Qualquer bug, sugestão ou resultado inesperado — manda lá.
Estamos ajustando com pente fino com base no uso real.
