# Passo 7 — Estrutura técnica e legal

**Objetivo:** deixar tudo pronto para receber dinheiro, entregar o produto e medir resultados — dentro da lei.
**Entregável:** produto cadastrado na plataforma, checkout testado, pixel instalado e checklist legal feito.
**Tempo:** 2 dias.

---

## 7.1 A estrutura mínima (o "encanamento")

```
Anúncio/Post → Página de vendas → Checkout → Pagamento aprovado → Área de membros + e-mail/WhatsApp de boas-vindas
                     ↑ Pixel/Analytics medindo cada etapa ↑
```

## 7.2 Escolha a plataforma de venda

As plataformas brasileiras fazem **checkout + área de membros + afiliados + repasse** num lugar só.

| Plataforma | Taxa por venda (referência nov/2026*) | Destaque |
|---|---|---|
| **Hotmart** | ~9,9% + R$ 2,49 | Maior mercado de afiliados, reconhecida pelo público, internacional |
| **Kiwify** | ~8,99% + R$ 2,49 | Interface simples, popular entre iniciantes, saque rápido |
| **Eduzz** | varia por plano | Boa para quem tem vários produtos |
| **Ticto, Greenn, Cakto, Lastlink** | variam | Alternativas competitivas — compare |

\* Valores coletados em fontes de mercado em 2026 e mudam com frequência (a Hotmart, por exemplo, alterou
a taxa fixa em set/2026). **Confira a tabela oficial de cada plataforma** antes de decidir.
Também compare: prazo de saque, custo de saque, taxa de parcelamento e antecipação.

**Recomendação para começar:** Hotmart **ou** Kiwify. Escolha uma e siga — a diferença de taxa é pequena perto da diferença que a execução faz.

> **Para mentoria/serviço vendido no 1 a 1**, você também pode usar link de pagamento
> (Mercado Pago, PagBank, InfinitePay, Stripe) ou Pix direto.

### Configuração na plataforma (passo a passo geral)
1. Crie a conta e complete o cadastro (dados pessoais/CNPJ, conta bancária).
2. Cadastre o produto (nome, descrição, categoria, imagem).
3. Defina preço, parcelamento, garantia (mínimo 7 dias).
4. Suba as aulas na área de membros.
5. Configure **order bump** (oferta extra barata no checkout — ex.: pacote de templates por R$ 27).
6. Personalize o checkout (logo, depoimentos, selo de garantia).
7. Configure e-mail de boas-vindas e acesso.
8. **Faça uma compra de teste** (ou use o modo teste) e confira se o acesso chega.

## 7.3 Medição: pixel, analytics e UTMs

| Ferramenta | Para quê |
|---|---|
| **Pixel da Meta + API de Conversões** | Medir visitas e vendas vindas de Instagram/Facebook e otimizar anúncios. Hotmart e Kiwify têm integração nativa: cole o ID do pixel e ative. |
| **Google Tag Manager + Google Analytics 4** | Ver de onde vêm os visitantes e o que fazem na página |
| **Microsoft Clarity** (grátis) | Gravações de sessão e mapas de calor — veja onde as pessoas desistem |
| **UTMs** | Etiquetas no link para saber qual post/anúncio trouxe a venda. Ex.: `?utm_source=instagram&utm_medium=bio&utm_campaign=lancamento1` |

> Sem medição, você não sabe o que funciona. Com medição, você para de "achar" e começa a saber.

## 7.4 Domínio e e-mail profissional (opcional, mas recomendado)

- **Domínio .com.br** no Registro.br (cerca de R$ 40/ano).
- **E-mail profissional** (Google Workspace, Zoho Mail — este tem plano grátis).
- **Ferramenta de e-mail marketing:** Brevo, MailerLite (planos grátis para começar), ActiveCampaign, Kajabi etc.

## 7.5 Checklist LEGAL (Brasil) ⚖️

> ⚠️ **Isto é orientação geral, não consultoria jurídica ou contábil.** Fale com um contador antes de
> faturar de forma recorrente — a consulta custa pouco perto de uma multa.

1. **Formalização (CNPJ):**
   - **MEI** é o mais barato, mas **nem toda atividade de ensino/infoproduto é permitida no MEI**. Confira a
     lista de ocupações permitidas e o limite anual de faturamento no Portal do Empreendedor.
   - Quando não cabe no MEI, o caminho comum é **ME no Simples Nacional**. Um contador escolhe o CNAE e o anexo certos (isso muda MUITO o imposto).
   - No começo, dá para vender como **pessoa física** (plataformas aceitam), declarando a renda no Carnê-Leão/IR. Com volume, o CNPJ fica mais vantajoso.
2. **Nota fiscal:** as plataformas costumam emitir nota da parte delas; a nota da sua parte (produtor) é sua
   responsabilidade quando você tem CNPJ. Pergunte ao contador sobre automação de emissão.
3. **Direito de arrependimento — CDC, art. 49:** 7 dias corridos para desistir de compras feitas fora de
   estabelecimento comercial (internet). Garanta isso sempre.
4. **Decreto 7.962/2013 (comércio eletrônico):** sua página precisa mostrar identificação do vendedor
   (nome/razão social, CPF/CNPJ), contato, informações claras sobre o produto, preço e condições.
5. **Publicidade honesta (CDC arts. 36–38):** nada de promessas falsas de ganho, depoimentos inventados
   ou escassez mentirosa. Em nichos de saúde e finanças, cuidado redobrado com promessas.
6. **LGPD (Lei 13.709/2018):** ao coletar e-mail/WhatsApp, diga para que vai usar, tenha **política de
   privacidade** na página e **consentimento** para mensagens de marketing. Dê opção de sair da lista.
7. **Termos de uso** do curso: acesso, prazo, proibição de compartilhar, política de reembolso.
8. **Direitos autorais:** não use músicas, imagens ou materiais de terceiros sem licença. Use bancos livres (Pexels, Unsplash, biblioteca do Canva, músicas livres do CapCut/YouTube).

Geradores de política de privacidade/termos existem online, mas **adapte ao seu caso**.

## ✅ Checklist do Passo 7

- [ ] Plataforma escolhida e conta verificada
- [ ] Produto cadastrado, área de membros com aulas
- [ ] Preço, parcelamento, garantia e order bump configurados
- [ ] Compra de teste feita — acesso chegou
- [ ] Pixel da Meta (e GA4/Clarity) instalados e testados
- [ ] Página com identificação do vendedor, política de privacidade e termos
- [ ] Conversei (ou agendei conversa) com um contador

## ❌ Erros comuns

- Começar a anunciar sem pixel (você perde os dados das primeiras vendas).
- Esquecer de testar o checkout — e descobrir que o acesso não chega.
- Ignorar a parte fiscal até receber uma notificação.

➡️ Próximo: [Passo 8 — Audiência orgânica e conteúdo](08-conteudo-e-audiencia.md)
