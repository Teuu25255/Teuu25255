<!--
COMO USAR
1. Crie um repositório PÚBLICO chamado Teuu25255 (igual ao seu usuário) com "Add a README file".
2. Dentro dele crie a pasta "assets" e suba a foto como assets/foto-perfil.png
3. Cole este conteúdo no README.md e troque tudo que estiver entre [colchetes].
4. Apague estes comentários antes de salvar.
-->

<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:1F4E79,100:2E86C1&height=170&section=header&text=Matheus%20Santana&fontSize=42&fontColor=ffffff&animation=fadeIn&fontAlignY=38&desc=Desenvolvedor%20J%C3%BAnior&descAlignY=58&descSize=18" alt="Cabeçalho" />


<br/>

<a href="https://github.com/Teuu25255">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&pause=1200&color=2E86C1&center=true&vCenter=true&width=560&lines=Desenvolvedor+J%C3%BAnior+em+Java+%26+Spring+Boot;Estudante+de+Ci%C3%AAncia+da+Computa%C3%A7%C3%A3o;Criador+do+plugin+Bigorna+para+Minecraft;Sempre+aprendendo+e+construindo+projetos" alt="Digitando..." />
</a>

📍 Sete Lagoas, MG &nbsp;•&nbsp; 🎓 UNA Sete Lagoas &nbsp;•&nbsp; 💼 Aberto a oportunidades

</div>

---

## 👨‍💻 Resumo

Sou estudante de **Ciência da Computação** (UNA Sete Lagoas) e **Técnico em Informática**, e estou em busca de oportunidade como **Desenvolvedor Júnior** (Back-end, Front-end ou Full Stack).

Aprendo construindo: desenvolvo projetos próprios, como e-commerces, um jogo 2D e plugins para servidores de Minecraft, e publico tudo aqui. Minha experiência anterior me deu **disciplina, responsabilidade e trabalho em equipe**, e hoje levo isso para o código.

---

## Competências

<div align="center">

**Conhecimento em:**

<img src="https://skillicons.dev/icons?i=java,spring,js,ts,react,nodejs,php,html,css,tailwind,mysql,postgres,git,github,idea,vscode,postman,maven,gradle" alt="Tecnologias principais" />

**Estudando / em evolução**

<img src="https://skillicons.dev/icons?i=angular,python,docker,aws,azure,mongodb" alt="Em evolução" />

</div>

---

## Projetos

### 🔨 Bigorna — plugin para Minecraft (Java)

<div align="center">
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Banner_Bigorna.png" alt="Banner do plugin Bigorna" width="85%" />
</div>

<br/>

Plugin que **personaliza a bigorna tradicional do Minecraft** com novas funções para diversificar servidores. Publicado no Modrinth, com **54 downloads** e compatível com **Paper, Spigot e Bukkit** (Minecraft 1.20.x e 1.21.x).

**Principais recursos**
- 🖱️ Menu totalmente configurável por YAML
- ✏️ Renomear itens e editar descrição pelo chat
- ✨ Menu de encantamentos (compra, adição e remoção)
- ⚡ Upgrade automático usando os livros do inventário
- ⚒️ Forja com a mesma função da bigorna tradicional
- 🔐 Permissões separadas por função e suporte opcional a Vault (economia)
- 🎨 Suporte a MiniMessage e códigos `&`

**Tecnologias:** Java 21 · Paper API · YAML · Maven/Gradle · Vault

<div align="center">
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem3.png" alt="Menu principal" width="32%" />
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem2.png" alt="Menu de encantar" width="32%" />
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem8.png" alt="Forja" width="32%" />
</div>

<details>
<summary><b>📸 Ver mais imagens do plugin</b></summary>
<br/>
<div align="center">
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem1.png" alt="Renomear" width="32%" />
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem6.png" alt="Auto Upgrade" width="32%" />
  <img src="https://raw.githubusercontent.com/Teuu25255/AnvilInfinity/main/imagensREADME/Imagem9.png" alt="Comandos" width="32%" />
</div>
</details>

<div align="center">

[![Modrinth](https://img.shields.io/badge/Modrinth-Baixar-1bd96a?style=for-the-badge&logo=modrinth&logoColor=white)](https://modrinth.com/plugin/bigorna)
[![Código-fonte](https://img.shields.io/badge/GitHub-C%C3%B3digo--fonte-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Teuu25255/Bigorna)

</div>

---

### ⚔️ SmiteDungeon — plugin de dungeons para Minecraft (Java)

Plugin de dungeons com **progressão de encantamentos**, menus interativos e economia integrada. O jogador entra na dungeon, derrota mobs, desbloqueia encantamentos e os evolui com dinheiro e itens.

**O que o plugin faz**
- 🧙 **5 encantamentos**, cada um com nível, chance de ativação e efeito próprio
- 🔓 **Requisitos de desbloqueio**: quantidade de kills na dungeon e nível mínimo de varinha
- 💰 **Evolução paga** com dinheiro (via **Vault**) e/ou itens, com compra de +1, +5, +10 ou até o nível máximo
- 🖱️ **Menus interativos** que mostram em verde ou vermelho o que o jogador consegue pagar
- 👥 **Instâncias por jogador**: cada jogador vê apenas os próprios mobs na mesma área, usando **PacketEvents**
- 🛠️ Painel administrativo, modo desempenho por jogador e dados salvos em banco SQL

| Encantamento | O que faz |
|---|---|
| **Tóxico** | Dano em área com chance de ativação; raio e dano crescem por nível |
| **Wither** | Atinge vários alvos por ativação; a quantidade cresce por nível |
| **Caixa** | Sorteia um ganho (%) e entrega recompensas por comando |
| **Tsunami** | Elimina todos os mobs da região de uma vez |
| **Custom** | Sem fórmula fixa: cada nível é uma lista de comandos definida pelo admin |

**Destaques técnicos**
- Menus, mensagens e encantamentos configuráveis em **YAML**, recarregados sem reiniciar o servidor
- Ao atualizar o plugin, chaves novas entram nos arquivos do admin sem apagar o que ele já alterou
- Fórmulas de progressão parametrizadas, com limite máximo e precisão de 4 casas decimais
- O raio dos efeitos nunca ultrapassa o tamanho real da área da dungeon
- Sem Vault ou PacketEvents o plugin avisa e continua funcionando; se o banco falhar, ele se desativa com segurança

**Tecnologias:** Java · Paper/Bukkit API · PacketEvents · Vault · YAML · SQL (JDBC)

#### 💻 Trechos de código

**Fórmula de chance de ativação** (usada por vários encantamentos, valores vindos do `encantamentos.yml`)

```java
public double calcularChanceGenerica(String prefixo, int nivel) {
    if (nivel <= 0) return 0.0;

    double base = getDouble(prefixo + ".chance-base", 0.0);
    double porNivel = getDouble(prefixo + ".chance-por-nivel", 0.0);
    double maxima = getDouble(prefixo + ".chance-maxima", 100.0);

    double chance = base + (porNivel * (nivel - 1));
    chance = Math.max(0.0, Math.min(100.0, Math.min(chance, maxima)));
    return arredondar4Casas(chance);
}
```

**Atualização de configuração sem perder o que o admin editou**

```java
for (String chave : configPadrao.getKeys(true)) {
    if (!config.contains(chave) && !configPadrao.isConfigurationSection(chave)) {
        config.set(chave, configPadrao.get(chave));
        alterado = true;
    }
}
if (alterado) {
    salvar();
}
```

<details>
<summary><b>Ver mais trechos</b></summary>

**Encantamento Tsunami** (trecho resumido)

```java
public static int aplicar(MensagensManager mensagens, Area area, Player player, String regionName) {
    List<LivingEntity> mobs = area.getMobsInRegion(regionName);
    int eliminados = 0;

    for (LivingEntity mob : mobs) {
        // Folga grande sobre a vida atual para garantir a morte
        area.applyEnchantDamage(mob, mob.getHealth() + 9999.0, player);
        eliminados++;
    }

    if (eliminados > 0) {
        player.getWorld().playSound(player.getLocation(), Sound.ENTITY_GENERIC_EXPLODE, 1.0f, 0.6f);
        player.sendMessage(mensagens.get("encantamentos.tsunami-ativado", "quantidade", eliminados));
    }
    return eliminados;
}
```

**Limite de alcance pelo tamanho da dungeon**

```java
public double clampAlcanceAreaMaxima(double alcanceDesejado, DatabaseManager.RegionBounds bounds) {
    if (bounds == null) {
        return alcanceDesejado;
    }

    double largura = Math.abs(bounds.getMaxX() - bounds.getMinX());
    double altura = Math.abs(bounds.getMaxY() - bounds.getMinY());
    double comprimento = Math.abs(bounds.getMaxZ() - bounds.getMinZ());
    double maiorDimensao = Math.max(largura, Math.max(altura, comprimento));

    double limiteAbsoluto = maiorDimensao * (getAlcanceLimitePercentual() / 100.0);
    return Math.min(alcanceDesejado, limiteAbsoluto);
}
```

</details>

[![Código-fonte](https://img.shields.io/badge/GitHub-C%C3%B3digo--fonte-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Teuu25255/[nome-do-repo])

---

### 💎 DonaFlor — e-commerce de semijoias (React + TypeScript)

Loja virtual de semijoias com visual de boutique, feita do zero, com **fluxo completo de compra e área do cliente**.

- 🛍️ Mostruário com **filtro por categoria** e botão de adicionar à sacola com notificação instantânea
- 🛒 Carrinho gerenciado por hook próprio (`useCart`) e página de checkout
- 👤 **Área do cliente:** login, cadastro e página **Meus pedidos**
- 📦 Cada pedido mostra status, produtos, total, forma de pagamento (Pix, cartão ou boleto), endereço de entrega e rastreio
- 💬 **Mensagens entre cliente e loja** dentro de cada pedido
- 🎨 Design system próprio (paleta champagne/cacau, Cormorant Garamond + Inter) e layout responsivo
- 🧭 Rotas baseadas em arquivos com **TanStack Router**

> ℹ️ Projeto de portfólio: pedidos e usuários são dados simulados guardados no navegador, e não há pagamento real.

**Tecnologias:** React · TypeScript · TanStack Router · Tailwind CSS · Sonner · Lucide

#### 💻 Trechos de código

**Filtro por categoria e adição à sacola**

```tsx
const [activeCategory, setActiveCategory] = useState<Category>("Todos");
const { add } = useCart();
const visibleProducts =
  activeCategory === "Todos"
    ? products
    : products.filter((p) => p.category === activeCategory);

// ...
<button
  onClick={() => {
    add(p.id);
    toast.success(`${p.name} adicionada à sacola`);
  }}
>
  + Adicionar à sacola
</button>
```

<details>
<summary><b>Ver mais trechos</b></summary>

**Status de pedidos com tipagem forte** (trecho resumido)

```tsx
const STATUS_LABEL: Record<OrderStatus, { label: string; cls: string }> = {
  pago: { label: "Pago", cls: "bg-emerald-100 text-emerald-700" },
  preparacao: { label: "Em preparação", cls: "bg-indigo-100 text-indigo-700" },
  enviado: { label: "Enviado", cls: "bg-sky-100 text-sky-700" },
  entregue: { label: "Entregue", cls: "bg-emerald-100 text-emerald-700" },
  // ...
};

function StatusPill({ status }: { status: OrderStatus }) {
  const s = STATUS_LABEL[status];
  return (
    <span className={`text-[10px] uppercase tracking-wider px-2 py-0.5 rounded-full ${s.cls}`}>
      {s.label}
    </span>
  );
}
```

**Rota "Meus pedidos" com TanStack Router**

```tsx
export const Route = createFileRoute("/meus-pedidos")({
  head: () => ({ meta: [{ title: "Meus Pedidos — Dona Flor Semi Joias" }] }),
  component: MeusPedidosPage,
});
```

</details>

[![Código-fonte](https://img.shields.io/badge/GitHub-C%C3%B3digo--fonte-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Teuu25255/[nome-do-repo])

---

### 🛒 LapisCraft — loja para servidor de Minecraft (PHP)

E-commerce de games para um servidor de Minecraft, do front-end ao back-end.

- 🏪 Páginas de loja, carrinho (com contador em tempo real), suporte e perfil
- 🔐 Login com sessão e **painel administrativo** restrito por perfil (admin)
- 📡 Indicador de jogadores online e informações do servidor na página inicial
- 💳 Rodapé com formas de pagamento e contatos
- 🎨 Interface temática de Minecraft, com identidade visual própria

**Tecnologias:** PHP · HTML5 · CSS3 · JavaScript · Font Awesome

#### 💻 Trechos de código

**Contador do carrinho em tempo real** (JavaScript)

```js
function atualizarContadorCarrinho() {
  let carrinho = JSON.parse(localStorage.getItem('carrinho')) || [];
  let total = carrinho.reduce((soma, item) => soma + (item.qtd || 1), 0);
  document.getElementById('carrinho-contador').textContent = total;
}

document.addEventListener('DOMContentLoaded', atualizarContadorCarrinho);
```

<details>
<summary><b>Ver mais trechos</b></summary>

**Menu que muda conforme o perfil do usuário** (PHP, trecho simplificado)

```php
<?php if (isset($_SESSION["logado"]) && $_SESSION["logado"] === true): ?>
  <li><a href="frontend/paginas/MeuPerfil.html">Meu Perfil</a></li>
<?php endif; ?>

<?php if (isset($_SESSION["logado"]) && $_SESSION["logado"] === true
          && $_SESSION["usuario_role"] === "admin"): ?>
  <li><a href="...">Admin</a></li>
<?php endif; ?>
```

</details>

[![Código-fonte](https://img.shields.io/badge/GitHub-C%C3%B3digo--fonte-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Teuu25255/[nome-do-repo])

---

### 🐱 CatRun2D — jogo 2D em Java

Jogo 2D feito para praticar lógica de programação e orientação a objetos. **Tecnologias:** Java · [preencher]

[![Código-fonte](https://img.shields.io/badge/GitHub-C%C3%B3digo--fonte-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Teuu25255/[nome-do-repo])



---

## 🎓 Formação e cursos

- 🎓 Bacharelado em Ciência da Computação, UNA Sete Lagoas (previsão: Dez/2028)
- 💻 Técnico em Informática, E. E. Doutor Arthur Bernardes (2023)
- 🛡️ Defesa Cibernética, Cisco (2025)
- 🎮 Game Designer e Desenvolvedor Unreal, EBAC (2026)

---

## 📫 Vamos conversar?

<div align="center">

[![Gmail](https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white)](mailto:matheussantana25255@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/matheus-tadeu-0b2a48275/)
[![WhatsApp](https://img.shields.io/badge/WhatsApp-25D366?style=for-the-badge&logo=whatsapp&logoColor=white)](https://wa.me/5531973033581)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2E86C1,100:1F4E79&height=100&section=footer" alt="Rodapé" />

</div>
