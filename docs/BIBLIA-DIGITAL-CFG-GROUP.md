# BÍBLIA DIGITAL — CFG GROUP

**Documento mestre de governança da infraestrutura digital do CFG Group**  
Última atualização inicial: 28/09/2026

> REGRA DE OURO: nenhum site, campanha ou novo ativo digital do CFG Group é considerado concluído apenas porque está publicado. Antes do encerramento, deve passar pelo checklist técnico, de mensuração, indexação, segurança, acessos e operação abaixo.

## 1. Arquitetura central

A estrutura deve ser pensada para escala. Sempre que possível, contas-mãe do CFG Group centralizam propriedades separadas de cada empresa, sem misturar dados operacionais.

### Empresas / marcas atuais
- CFG Group
- Eletrofit Wear
- Interbusiness Oportunidades
- Interbusiness Locações
- Beauty Connection Brazil
- PEBRAS / Portal EMS Brasil

## 2. Matriz mestre de ativos

Legenda: **CONFIRMADO** = verificado; **PENDENTE** = precisa implantar; **VERIFICAR** = não presumir.

| Item | CFG Group | Eletrofit Wear | Interbusiness Oportunidades | Interbusiness Locações | Beauty Connection Brazil | PEBRAS |
|---|---|---|---|---|---|---|
| Site | CONFIRMADO | CONFIRMADO | VERIFICAR | CONFIRMADO | VERIFICAR | CONFIRMADO |
| Domínio/DNS | CONFIRMADO | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | CONFIRMADO |
| GA4 | PENDENTE | CONFIRMADO — conta já existente; revisar | PENDENTE | PENDENTE | VERIFICAR | PENDENTE |
| Google Tag Manager | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Search Console | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Sitemap / robots / indexação | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| SEO técnico básico | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Meta Pixel / CAPI | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Google Ads / conversões | AVALIAR | AVALIAR | AVALIAR | AVALIAR | AVALIAR | AVALIAR |
| Instagram / Meta | VERIFICAR | VERIFICAR | VERIFICAR | CONFIRMADO | VERIFICAR | VERIFICAR |
| WhatsApp / destino comercial | N/A/AVALIAR | VERIFICAR | VERIFICAR | CONFIRMADO | VERIFICAR | N/A/AVALIAR |
| LGPD / consentimento / cookies | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| HTTPS / segurança | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Backup / recuperação | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |
| Responsáveis / acessos | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR | VERIFICAR |

## 3. Checklist obrigatório para lançamento de site

Antes de declarar um site **PRONTO**:

- [ ] Domínio correto e DNS verificado
- [ ] HTTPS funcionando
- [ ] Responsividade desktop/mobile testada
- [ ] Links, formulários, WhatsApp, telefones e e-mails testados
- [ ] Favicon configurado
- [ ] Title e meta description revisados
- [ ] Open Graph / compartilhamento social revisado
- [ ] robots.txt revisado
- [ ] sitemap disponível e válido
- [ ] Google Search Console configurado e propriedade verificada
- [ ] sitemap enviado ao Search Console
- [ ] GA4 configurado na propriedade correta
- [ ] fluxo Web criado e Measurement ID documentado
- [ ] GA4 instalado no site e tráfego em tempo real testado
- [ ] Google Tag Manager avaliado/configurado quando aplicável
- [ ] eventos e conversões definidos conforme objetivo do negócio
- [ ] Meta Pixel/CAPI avaliado quando houver tráfego ou conversão Meta no site
- [ ] Google Ads/conversões avaliado quando houver campanha Google
- [ ] política de privacidade/LGPD e consentimento avaliados
- [ ] acessos administrativos e proprietários documentados
- [ ] estratégia de backup/recuperação definida
- [ ] versão final validada antes de encerrar implantação

## 4. Checklist obrigatório para campanhas digitais

Antes de publicar:
- objetivo comercial definido;
- origem e destino do lead confirmados;
- conta, Página/Instagram e WhatsApp corretos;
- público/geografia documentados;
- orçamento e período confirmados;
- mensuração compatível com o objetivo;
- parâmetros UTM quando houver destino Web;
- Pixel/GA4/eventos conferidos quando houver site;
- criativo final aprovado sem alterações automáticas indesejadas;
- forma de pagamento e saldo/cobrança conferidos;
- prévia e destino testados.

Depois de publicar:
- status de análise/ativo confirmado;
- gasto e entrega acompanhados;
- custo por resultado acompanhado;
- qualidade comercial do lead avaliada, não apenas clique;
- aprendizados registrados antes de duplicar ou alterar campanha.

## 5. Arquitetura GA4 pretendida

Criar/usar uma **conta Google Analytics central do CFG Group**, com propriedades independentes por negócio/site, em vez de novas contas isoladas para cada empresa.

Estrutura inicial pretendida:
- Conta: CFG Group
  - Propriedade: CFG Group
  - Propriedade: Interbusiness Locações
  - Propriedade: Interbusiness Oportunidades
  - Propriedade: Beauty Connection Brazil, quando aplicável
  - Propriedade: PEBRAS
  - futuras propriedades

**Eletrofit Wear:** GA4 já existe separadamente. Não alterar até inventariar a estrutura atual e decidir conscientemente se deve permanecer independente ou ser reorganizada.

## 6. Pendências prioritárias — 28/09/2026

1. Criar a conta central Google Analytics **CFG Group**.
2. Criar a propriedade GA4 **CFG Group** e o fluxo Web do site.
3. Instalar o Measurement ID no site `cfggroup.com.br` e testar em tempo real.
4. Verificar/criar Search Console do CFG Group.
5. Verificar sitemap, robots e indexação do site CFG Group.
6. Inventariar GA4 existente da Eletrofit Wear sem alterar sua operação.
7. Criar propriedades GA4 das demais empresas/sites conforme inventário.
8. Inventariar Tag Manager, Pixels, conversões, acessos e LGPD de todos os ativos.

## 7. Regra de trabalho

Quando surgir uma nova empresa, site, landing page, campanha ou canal, este documento deve ser consultado **antes** da implantação e atualizado **depois** dela.

Nunca marcar um item como confirmado por memória, aparência ou suposição. Quando não houver verificação objetiva, usar **VERIFICAR**.

Nunca registrar neste arquivo senhas, tokens, chaves privadas, códigos de recuperação ou outros segredos.

---
Este documento é a referência operacional central da infraestrutura digital do CFG Group e deve evoluir junto com o grupo.
