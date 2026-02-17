# 🌿 Site Abranghe

Site institucional da **Abranghe – Associação Brasileira de Angioedema Hereditário**.

🔗 Produção: [https://abranghe.org.br](https://abranghe.org.br)
🚀 Deploy automático via Vercel
💻 Edição local via VSCode + GitHub

---

## 📌 Sobre o Projeto

Este é um site **estático em HTML**, com:

* TailwindCSS via CDN
* Lucide Icons
* Google Fonts (Plus Jakarta Sans)
* Deploy automático via **Vercel**

Fluxo de publicação:

```
VSCode → commit → GitHub → Vercel (auto deploy)
```

---

## 🗂 Estrutura do Projeto

### Páginas principais

| Arquivo                       | Função                        |
| ----------------------------- | ----------------------------- |
| `index.html`                  | Página inicial                |
| `sobre.html`                  | Sobre a Abranghe              |
| `doenca.html`                 | Hub "Sobre a Doença"          |
| `o-que-e-aeh.html`            | Definição e prevalência       |
| `evolucao-cientifica.html`    | Linha do tempo científica     |
| `sinais-sintomas.html`        | Manifestações clínicas        |
| `diagnostico-tratamento.html` | Diagnóstico, CID e tratamento |
| `paciente.html`               | Área do paciente              |
| `mapas.html`                  | Mapas informativos            |
| `referencias.html`            | Diretrizes e documentos       |
| `contato.html`                | Canais oficiais e formulário  |

### Pasta de imagens

```
/img
```

Exemplos:

* `logo.png`
* `cartao.png`
* `manual.png`

---

## 🎨 Padrão Visual

Todas as páginas seguem a mesma estrutura:

```
Header (nav)
Hero
Blocos em cards
CTAs
Footer
```

### Cores principais

* `abranghe-green` → #99BC35
* `abranghe-gray` → #4A5568
* `haei-purple` → #6d338a
* `light-gray` → #F7FAFC

---

## ⚙️ Como editar

1. Abrir o projeto no VSCode
2. Alterar o HTML desejado
3. Commit:

   ```
   git add .
   git commit -m "Descrição da alteração"
   git push
   ```
4. O Vercel atualizará automaticamente o site

---

## 🧾 Checklist antes de commitar

### Conteúdo

* [ ] Texto revisado (ortografia e clareza)
* [ ] Informação clínica atualizada
* [ ] Não há orientação médica prescritiva
* [ ] Aviso de que não substitui avaliação médica quando necessário

### Visual

* [ ] Header e Footer iguais nas páginas
* [ ] Ícones funcionando (`lucide.createIcons();`)
* [ ] Links internos funcionando
* [ ] Botões com estilo consistente
* [ ] Não há quebra de layout mobile

### Imagens

* [ ] Imagens otimizadas (PNG ou JPG leve)
* [ ] Estão na pasta `/img`
* [ ] Nome do arquivo correto no HTML

---

## 📚 Atualizações clínicas importantes

Sempre que houver atualização:

* PCDT / Portarias do Ministério da Saúde
* Incorporação de medicamentos no SUS
* Atualizações ANVISA / ANS
* Mudanças no CID

Revisar:

* `diagnostico-tratamento.html`
* `referencias.html`

---

## 📬 Formulário

O formulário está embutido via Google Forms.

Para alterar:

1. Atualizar o link do iframe em `contato.html`
2. Conferir permissões de notificação no Google Forms

---

## 🔐 Responsabilidade

Este site tem caráter **informativo e institucional**.
Não substitui avaliação médica.

---

## 📈 Próximas melhorias possíveis

* Otimização de SEO (meta description personalizada)
* Sitemap.xml
* OpenGraph (para melhor compartilhamento)
* Compressão de imagens
* Versão em inglês
* Área restrita para associados
* Analytics (Google Analytics ou Plausible)

---

## 👩🏻‍💻 Manutenção

Site desenvolvido e mantido internamente.
Alterações estruturais devem manter consistência visual e institucional.


