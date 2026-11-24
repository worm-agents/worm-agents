# Worm Agents

Código de [worm-agents.com](https://worm-agents.com), la landing de Worm Agents: una familia de agentes de IA open source que corren en tu computadora y no mandan nada en tu nombre sin tu OK.

| Agente | Para qué | Estado |
| --- | --- | --- |
| [WorkWorm](https://github.com/worm-agents/workworm) | Busca ofertas de trabajo en Argentina, las ordena según tu perfil, adapta tu CV y sigue a los reclutadores por Gmail. | Disponible |
| [LoveWorm](https://github.com/worm-agents/loveworm) | Ordena tus matches de Tinder por interés y escribe borradores de mensajes que vos aprobás. | Disponible |
| [InvestWorm](https://github.com/worm-agents/investworm) | Investiga las empresas que seguís y explica su razonamiento. | En desarrollo |
| [MediaWorm](https://github.com/worm-agents/mediaworm) | Planifica tu contenido y escribe posteos y respuestas para tus redes. | En desarrollo |

Por ahora los agentes están pensados para Argentina y necesitan Windows y [Claude Code](https://claude.com/claude-code) con tu cuenta de Claude. LoveWorm también funciona con cualquier API compatible con OpenAI.

## Desarrollo

Es un sitio estático (`index.html`, `favicon.svg` e `icons/`), sin build. Para verlo, abrí `index.html` en el navegador. Cada push a `main` se publica solo en worm-agents.com.
