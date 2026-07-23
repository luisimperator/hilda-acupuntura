# Hilda Acupuntura — Moema

Landing page de **Hilda de Oliveira · Acupuntura Clínica** (Moema, São Paulo, SP).

Página única, 100% estática, sem build e sem dependências — todo o site vive em [`index.html`](index.html).

## Conceito da página

- **Hero "Quanto dói, de 0 a 10?"** com escala de dor interativa: o número que a visitante marca entra automaticamente na mensagem de WhatsApp de todos os CTAs.
- **Oferta de entrada:** Primeira Sessão Completa — 90 min · R$ 450, avaliação + tratamento no mesmo dia, com plano por escrito. Valor vira crédito integral se fechar um programa em até 7 dias.
- **Compromisso:** reavaliação medida na 5ª sessão — evolução mensurável na escala de dor ou devolução do valor das sessões restantes.
- **CTA único:** WhatsApp (11) 97202-2143, em todos os pontos da página (topbar, hero, oferta, final, bolha flutuante e barra fixa no mobile).

## Rodar localmente

Abra `index.html` no navegador. Pronto.

## Publicação

Qualquer host estático serve (Vercel, GitHub Pages, Netlify). Não há passo de build.

## Pendências antes de ir ao ar

- [x] Fotos do espaço na seção "experiência" (sala de atendimento, agulhas ilustrativa, recepção)
- [ ] Retrato real da Hilda (seção "sobre") — aguardando ensaio fotográfico
- [ ] Depoimentos reais — os 3 cards estão com placeholder de propósito, para não publicar avaliação inventada
- [ ] Domínio próprio + tag `canonical` e `og:url`
- [ ] Imagem Open Graph 1200×630 (compartilhamento no WhatsApp fica muito melhor)
- [ ] Google Business Profile apontando para o site
- [ ] Tag do Google (gtag) + evento de conversão de clique nos links `wa.me` — necessário antes de subir campanha de tráfego pago
