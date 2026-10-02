# SORRIMED — Versão Beige

Terceira variante da landing page da SORRIMED. O fundo principal da página é o **bege da fachada original** (`#E5D7C7`) — apenas a barra de navegação superior mantém o teal escuro (`#052E40`).

## Comparação de versões

| Versão | URL | Construída por |
|--------|-----|----------------|
| Principal | `/` | Perfil default |
| Dev | `/dev/` | Perfil frontend-dev |
| **Beige** | **`/beige/`** | **Perfil default** |

## Paleta

```css
:root {
  --teal-deep:  #052E40;   /* APENAS na nav */
  --teal-light: #6BB5BD;   /* destaques */
  --teal-pale:  #9CC9D0;   /* detalhes */
  --beige-dark: #D4C5A3;   /* footer / borders */
  --beige-main: #E5D7C7;   /* fundo principal — mesma cor da fachada */
  --beige-light:#F4ECE0;   /* seções alternadas */
  --cream:      #FAF4EA;   /* quase branco quente — cards, formulário */
  --gold:       #C9A876;   /* CTA */
  --text-dark:  #4A3F30;   /* texto escuro quente */
  --text-mid:   #6B5E4D;
  --text-soft:  #8B7E6B;
}
```

## Estrutura

- **Nav** — teal escuro (`#052E40`), `position: fixed !important`, `z-index: 9999 !important`, sem `backdrop-filter` (evita conflito iOS Safari), `padding-top: 84px` no body para não sobrepor o hero.
- **Hero** — fundo bege principal, headline em teal escuro, itálico "a nossa missão" em dourado, foto com moldura cream.
- **Serviços** — fundo bege claro (`#F4ECE0`), cards em cream com hover lift + barra dourada lateral.
- **Sobre** — fundo bege principal, foto da clínica com moldura cream e decoração dourada, stats com números em gold.
- **Contacto** — fundo bege claro, formulário cream com inputs bege claro.
- **Footer** — fundo bege escuro (`#D4C5A3`), socials cream com hover teal.

## Verificações visuais

| Dispositivo | Screenshot |
|-------------|-----------|
| Desktop — hero | `preview_desktop_hero.png` |
| Desktop — about | `preview_desktop_about.png` |
| Desktop — contact | `preview_desktop_contact.png` |
| Desktop — sticky nav (mid-scroll) | `preview_desktop_sticky_nav.png` |
| Mobile — top | `preview_mobile_top.png` |
| Mobile — services | `preview_mobile_services.png` |
| Mobile — sticky nav (mid-scroll) | `preview_mobile_sticky.png` |
| Mobile — contact | `preview_mobile_contact.png` |

## Garantias

- Nav tem `position: fixed !important` em todas as media queries (root + 960px + 640px).
- `backdrop-filter` removido da nav (causa bugs de stacking no iOS).
- `padding-top: 84px` no body compensa a altura da nav fixa.
- Imagens: `images/logo-official@2x.png`, `../images/hero-smile.jpg`, `../images/clinic-interior.jpg`.