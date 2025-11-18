<svg xmlns="http://www.w3.org/2000/svg" width="1200" height="260" viewBox="0 0 1200 260">
  <defs>
    <linearGradient id="g" x1="0" x2="1">
      <stop offset="0" stop-color="#00FF99"/>
      <stop offset="1" stop-color="#0BB572"/>
    </linearGradient>
    <filter id="glow" x="-50%" y="-50%" width="200%" height="200%">
      <feGaussianBlur stdDeviation="12" result="b"/>
      <feMerge><feMergeNode in="b"/><feMergeNode in="SourceGraphic"/></feMerge>
    </filter>
  </defs>

  <!-- Fundo preto -->
  <rect width="1200" height="260" fill="#0B0F10"/>

  <!-- Glow/Barra -->
  <g filter="url(#glow)">
    <rect x="30" y="30" rx="16" width="1140" height="200" fill="url(#g)" opacity="0.12"/>
  </g>

  <!-- Texto principal -->
  <g transform="translate(60,60)">
    <text x="0" y="36" font-family="Inter, Arial, sans-serif" font-size="34" fill="#FFFFFF" font-weight="700">Olá, eu sou [SEU_NOME]</text>
    <text x="0" y="78" font-family="Inter, Arial, sans-serif" font-size="20" fill="#66FFB3">[SUA_TAGLINE] — Desenvolvedor Web • Pesquisador de Segurança</text>

    <rect x="0" y="110" rx="10" width="420" height="42" fill="#0B0F10" stroke="#00FF99" stroke-width="1.6"/>
    <text x="18" y="138" font-family="Inter, Arial, sans-serif" font-size="15" fill="#00FF99">🔭 Trabalhando com: Web • Recon • Bug Bounty • Automação</text>
  </g>

  <!-- Ícones laterais (simples) -->
  <g transform="translate(980,58)">
    <rect x="0" y="0" width="160" height="160" rx="18" fill="#0B0F10" stroke="#00FF99" stroke-opacity="0.14"/>
    <text x="20" y="40" font-family="Inter, Arial, sans-serif" font-size="18" fill="#FFFFFF">⚙️ Tech</text>
    <text x="20" y="70" font-family="Inter, Arial, sans-serif" font-size="14" fill="#66FFB3">Go • Python • JS</text>
    <text x="20" y="96" font-family="Inter, Arial, sans-serif" font-size="14" fill="#66FFB3">Burp • Docker • Git</text>
  </g>
</svg>


# 👋 Olá, eu sou **SEU_NOME**
**Desenvolvedor Web • Pesquisador de Segurança**

> Hacking is an art — Security is a lifestyle.

---

## 🔭 Sobre mim
```go
package main
type devsec struct {
  Name           string // "SEU_NOME"
  Role           string // "Web Dev & Security Researcher"
  Location       string // opcional
  Portfolio      string // "https://SEU_PORTFOLIO"
  LanguagesSpoken []string // ["pt_BR","en_US"]
}
