# Projeto de Áudio para Vercel

Este projeto serve apenas para hospedar o áudio de boas-vindas da SDR Scalee.

## Estrutura

- `public/scalee_ligacao_boas_vindas_final.mp3` – Áudio principal
- `vercel.json` – Configuração da Vercel

## Como subir:

1. Crie uma conta gratuita no GitHub: https://github.com
2. Crie um novo repositório chamado `scalee-audio`
3. Faça upload dos arquivos deste ZIP no repositório
4. Acesse https://vercel.com e crie uma conta com o GitHub
5. Importe o repositório na Vercel
6. O link final será algo como:
   ```
   https://scalee-audio.vercel.app/scalee_ligacao_boas_vindas_final.mp3
   ```

Este link funciona direto no Twilio com o seguinte código:

```xml
<Response>
  <Play>https://scalee-audio.vercel.app/scalee_ligacao_boas_vindas_final.mp3</Play>
</Response>
```
