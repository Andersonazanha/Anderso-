# Passo 7 — Kiwify: produto, checkout e pixel

📅 **Dias 15 e 16** · ⏱️ 1h30 por dia (+ 🔁 rotina diária) · 💰 R$ 0
**Objetivo:** deixar o "caixa" pronto — o cliente paga, recebe o e-book automaticamente, e você **mede** cada venda.

> 🖼️ A Kiwify atualiza o painel com frequência. Os caminhos abaixo são os de referência; se algum botão estiver
> com outro nome, **me mande um print** — ou consulte **help.kiwify.com**.

```
Cliente clica em "Comprar" → Checkout Kiwify (Pix/cartão/boleto) → Pagamento aprovado
   → E-mail automático com acesso → Área de membros com o PDF
   → Pixel avisa a Meta: "houve uma COMPRA" (isso treina seus anúncios no Passo 10)
```

---

## ✅ Tarefa 7.1 — Confirme que sua conta está aprovada
1. Entre em **dashboard.kiwify.com.br** (ou kiwify.com.br → **Entrar**)
2. Confira em **Minha conta / Configurações** se dados pessoais, documentos e **dados bancários** estão **aprovados**
3. Se algo estiver pendente, resolva agora (ou me mande print)

✔️ **Pronto quando:** conta aprovada para vender e sacar.

## ✅ Tarefa 7.2 — Cadastre o produto
1. Menu lateral → **Produtos** → botão **Criar produto** (canto superior direito)
2. Tipo: escolha o formato de **produto digital / e-book** (se pedir, escolha entrega via **Área de membros**)
3. Preencha:
   - **Nome:** nome do e-book
   - **Descrição:** 2–3 frases com a promessa (o cliente vê isso)
   - **Categoria:** a mais próxima do tema
   - **Imagem:** o **mockup** da tarefa 6.6
   - **Preço:** o preço normal (ex.: R$ 37)
4. Clique em **Criar produto** / **Salvar**

✔️ **Pronto quando:** o produto aparece na sua lista de Produtos.

## ✅ Tarefa 7.3 — Configure a entrega do PDF
1. Abra o produto → procure a seção **Área de membros** / **Conteúdo**
2. Crie um **módulo** (ex.: "Seu guia") → dentro dele, uma **aula/conteúdo** (ex.: "Baixe seu e-book aqui")
3. Na aula, **anexe o PDF** (botão de anexo/arquivo/material complementar) e escreva um recado curto de boas-vindas
4. Se preferir entrega simples por arquivo/link, use a opção de **entrega por arquivo** ou **link externo** (Google Drive com permissão "qualquer pessoa com o link") — mas a área de membros é mais profissional e protege melhor o arquivo
5. Confira o **e-mail de boas-vindas/acesso** que o cliente recebe

✔️ **Pronto quando:** o PDF está anexado e a área de membros está publicada.

## ✅ Tarefa 7.4 — Pagamento, parcelamento e garantia
Dentro do produto, nas abas de **Configurações** / **Pagamento**:
1. Formas de pagamento: **Pix** ✅, **Cartão** ✅, **Boleto** ✅ (Pix é o mais usado em low ticket)
2. Parcelamento: permita até 12x (em R$ 37, ajuda pouco, mas não atrapalha)
3. **Garantia:** 7 dias
4. **Página de obrigado / redirecionamento** (se houver): pode deixar a padrão por enquanto
5. **Suporte:** coloque seu e-mail e/ou WhatsApp do negócio
6. **Salvar**

✔️ **Pronto quando:** tudo salvo.

## ✅ Tarefa 7.5 — Personalize o checkout
1. No produto, abra a aba **Checkout** → **Editar** / **Personalizar** (abre o editor visual)
2. Adicione:
   - **Banner/imagem no topo** com o mockup e a promessa (crie no Canva: **Criar design** → **Tamanho personalizado** 1200 x 400 px)
   - **Depoimentos** dos leitores beta (só reais e autorizados)
   - **Selo de garantia de 7 dias**
3. Deixe o checkout **limpo** — menos distração = mais vendas
4. ❌ **Não use cronômetro falso** (contagem que reinicia). Só use urgência se for verdadeira
5. **Salvar** e abra o link do checkout no celular para ver como ficou

✔️ **Pronto quando:** o checkout está bonito e claro no celular.

---

### 🏁 Fim do Dia 15 — mande para mim:
> "Dia 15 concluído" + **o link do seu checkout** (eu vou olhar como cliente e te dar sugestões).

---

## ✅ Tarefa 7.6 — Cadastre e ative o ORDER BUMP
1. **Primeiro**, cadastre o order bump como um **produto separado** (repita a tarefa 7.2–7.3 com o arquivo do bump e o preço, ex.: R$ 19)
2. Volte ao **produto principal** → **Configurações** → seção **Order bump** → **Adicionar**
3. Selecione o produto do bump e escreva a chamada:
   > ✅ **SIM! Quero adicionar as [40 listas de compras prontas] por apenas R$ 19** — economize horas no mercado.
4. **Salvar** → abra o checkout e veja o bump aparecendo

✔️ **Pronto quando:** o bump aparece no checkout do e-book.

## ✅ Tarefa 7.7 — Crie o Pixel da Meta
**O que é:** um "espião do bem" que avisa a Meta quando alguém compra. Sem ele, os anúncios do Passo 10 ficam às cegas.

1. Acesse **business.facebook.com** → **Gerenciador de Eventos** (menu ☰ → **Gerenciador de Eventos**, ou **business.facebook.com/events_manager**)
2. Clique em **Conectar fontes de dados** (botão verde **+**) → **Web** → **Conectar**
3. Nome: `Pixel [sua marca]` → **Criar** (se perguntar sobre site, pode pular/"Configurar manualmente depois")
4. Copie o **ID do conjunto de dados / ID do pixel** (um número de ~15–16 dígitos) — guarde em `05 Métricas`
5. (Recomendado) **Token da API de Conversões:** no pixel → **Configurações** → **API de Conversões** → **Gerar token de acesso** → copie e guarde

✔️ **Pronto quando:** você tem o ID do pixel (e o token) guardados.

## ✅ Tarefa 7.8 — Instale o pixel na Kiwify
1. Kiwify → seu **produto principal** → **Configurações** → role até **Pixels de conversão**
2. Escolha **Facebook / Meta** → **Adicionar pixel**
3. Cole o **ID do pixel** (e o **token da API de Conversões**, se houver o campo)
4. Marque para disparar compra também no **Pix** e no **boleto** quando aprovados (se a opção existir)
5. **Salvar**

> Os pixels na Kiwify são **por produto**. Repita no produto do order bump se quiser medir ele separado.

✔️ **Pronto quando:** o pixel aparece cadastrado no produto.

## ✅ Tarefa 7.9 — Crie o cupom de fundador (Lista VIP)
1. No produto → aba **Cupons** (ou **Cupons de desconto**) → **Criar cupom**
2. Código: `VIP` (ou `FUNDADOR`) · desconto para chegar no preço prometido (ex.: de R$ 37 para R$ 27 → R$ 10 de desconto)
3. Validade: até o fim do Dia 22 (48h após a abertura) · **Salvar**

> Dica: muitas plataformas permitem link com cupom já aplicado (ex.: `...?coupon=VIP`). Teste.

✔️ **Pronto quando:** o cupom funciona no checkout.

## ✅ Tarefa 7.10 — Faça uma compra de TESTE (obrigatório!)
1. Crie um cupom temporário `TESTE` com desconto grande (deixe o valor mínimo que a plataforma aceitar)
2. Abra o checkout **no celular, em aba anônima** → aplique `TESTE` → marque o order bump → pague com **Pix**
3. Confira: ✅ e-mail de acesso chegou · ✅ entrou na área de membros · ✅ PDF abre · ✅ bump chegou
4. Confira o pixel: **Gerenciador de Eventos** → seu pixel → **Visão geral** → deve aparecer o evento **Purchase/Compra** (pode levar alguns minutos). Use também **Testar eventos**
5. Faça o **reembolso** da compra teste em **Vendas** → abra a venda → **Reembolsar**
6. **Apague o cupom TESTE**

✔️ **Pronto quando:** tudo chegou e o evento Compra apareceu na Meta.

---

### 🏁 Fim do Dia 16 — mande para mim:
> "Dia 16 concluído" + confirme: **acesso chegou? PDF abriu? evento de Compra apareceu no pixel?**
> Se algo falhou, mande print — vamos resolver antes de seguir.

➡️ Próximo: [Passo 8 — Página de vendas e automações](08-pagina-de-vendas-e-automacoes.md)
