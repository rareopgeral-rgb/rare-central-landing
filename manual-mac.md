# Rare Central — Manual de Instalação (macOS)

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

- macOS 12 (Monterey) ou superior
- Conexão com internet (para legendas via AssemblyAI)
- Conta com acesso liberado pela administração Rare

---

## Instalação

### 1. Baixar o arquivo

Acesse o link de download fornecido pelo time e baixe o arquivo `RareCentral-Mac.dmg`.

### 2. Abrir o instalador

Dê dois cliques no arquivo `.dmg`. Uma janela vai abrir com o ícone do app.

### 3. Arrastar para Applications

Arraste o ícone **RareCentral** para a pasta **Applications**.

### 4. Primeira abertura (importante)

O macOS pode bloquear o app na primeira vez com a mensagem
*"não pode ser aberto porque é de um desenvolvedor não identificado"*.

Para resolver:
1. Clique com o **botão direito** no ícone do app
2. Selecione **Abrir**
3. Na caixa que aparecer, clique em **Abrir** novamente

Após isso, o app abre normalmente sempre.

### 5. Login

Acesse com o email e senha fornecidos pela administração.

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

**App não abre no Mac**
→ Clique com botão direito → Abrir → confirmar

**Legenda falhou**
→ Verifique se a API key está configurada em Configurações

**Vídeos ficaram fora de sincronia**
→ Envie o log para o grupo de WhatsApp para análise

---

## Feedback

Manda o feedback de uso no grupo:
**https://chat.whatsapp.com/FQPpcUtqlq23P79yybB81Y**

Qualquer bug, sugestão ou resultado inesperado — manda lá.
Estamos ajustando com pente fino com base no uso real.
