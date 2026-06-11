# DWMBlurGlass Custom Config

![License](https://img.shields.io/badge/License-MIT-blue.svg)

Minha configuração personalizada para a ferramenta **DWMBlurGlass** — que adiciona efeitos de vidro, blur e acentuação nas barras de título do Windows 10 e Windows 11.

## 🖼️ Efeitos incluídos

- Blur com intensidade personalizada
- Cor de destaque (accent color) aplicada nas bordas
- Transparência e vidro (glass) nas janelas ativas e inativas
- Suporte a temas claros e escuros (cores distintas para cada modo)

## ⚙️ Principais configurações

| Parâmetro | Valor | Efeito |
|-----------|-------|--------|
| `effectType` | 1 | Efeito vidro/glass |
| `blurMethod` | 0 | Método de desfoque padrão |
| `blurAmount` | 20.0 | Intensidade do blur |
| `glassIntensity` | 0.69 | Intensidade do efeito de vidro |
| `useAccentColor` | true | Usa a cor de destaque do Windows |
| `overrideAccent` | true | Sobrescreve a cor padrão |

## 📁 Como usar

1. Baixe o [DWMBlurGlass](https://github.com/Maplespe/DWMBlurGlass) (se ainda não tiver)
2. Importe o arquivo `dwm.ini` pelo DWMBlurGlass

## 🌗 Comportamento claro/escuro

O arquivo define cores separadas para modo claro e escuro:

- **Texto ativo:** branco (ambos os modos)
- **Texto inativo:** cinza claro
- **Blend color ativo vs inativo:** diferenciado para destacar a janela atual

## 📝 Observações

- Recomendo fazer backup das suas configurações (se houver) original antes de substituir
- O efeito pode variar conforme a versão do Windows 10/11 e aceleração gráfica

## 🔗 Links úteis

- [DWMBlurGlass no GitHub](https://github.com/Maplespe/DWMBlurGlass)

---

*Configuração pessoal — sinta-se livre para adaptar para seu uso.*

Este projeto está licenciado sob a MIT License - veja o arquivo [LICENSE](LICENSE) para detalhes.

