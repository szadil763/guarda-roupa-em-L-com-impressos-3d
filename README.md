# Guarda-roupa em L com conectores impressos em 3D

Guarda-roupa aberto em canto, em L, para um quarto em Guarulhos-SP. Estrutura em tubo
galvanizado Ø25,6 mm + prateleiras de MDF 18 mm + conectores impressos em PETG
(Ender-3, perfil "Ender3 forte PETG v2").

Duas alas de 120 x 50 cm, canto livre (sem coluna no vértice), barras de cabide
suspensas em consoles e braços em balanço, diagonais de canto e berços abertos em U
para as barras.

## Conteúdo do repositório

- **`stl/`** — todas as peças impressas (conectores, tampas, ponteiras, presilhas e o
  gabarito de folga). Veja a lista e as quantidades no guia de impressão.
- **`docs/guia-de-impressao-pecas-3d.pdf`** — o que imprimir, quantidades, ferragens,
  orientação/suporte de cada peça, ordem de testes antes do lote e o que mudou no
  projeto ao longo das iterações.
- **`docs/plano-de-montagem-guarda-roupa-L.pdf`** — passo a passo completo: marcação
  do local, corpo de prova obrigatório, montagem andar por andar, espelhos/portas e
  lista de materiais e ferragens.
- **`docs/previa_pecas.png`** — prévia renderizada de todas as peças da pasta `stl/`.

## Peças impressas (resumo)

| Arquivo | Qtd | Onde vai |
|---|---|---|
| `conector_L_25-8mm_M5.stl` | 21 | Sob cada prateleira |
| `conector_TT90_poste-tubo.stl` | 8 | Travessas das pontas e diagonais de canto |
| `conector_console_poste-braco.stl` | 3 | Braços em balanço (substitui mãos-francesas) |
| `conector_TT_berco_lado.stl` + `tampa_berco_lado.stl` | 3 + 3 | Berço lateral da barra |
| `conector_TT_berco_ponta.stl` + `tampa_berco_ponta.stl` | 2 + 2 | Berço de ponta da barra |
| `ponteira_coluna.stl` | 6 | Topo das colunas |
| `presilha_anti-tombamento.stl` | 2 | Fixação na parede, a 1,80 m |
| `colar_de_trava_25-8mm_M5.stl` | 35 (opcional) | Trava contra deslizamento do anel |
| `gabarito_de_folga_25-6_a_26-2.stl` | 1 | Teste de folga antes de imprimir o lote |

Detalhes completos — ferragens, posição na mesa, suporte, ordem de teste e massa
estimada de filamento — estão no guia de impressão (`docs/guia-de-impressao-pecas-3d.pdf`).

## Status

As peças foram modeladas e conferidas por simulação digital (sólidos fechados,
furos no diâmetro certo, réplica completa do móvel sem colisões), mas ainda não
foram impressas. Antes do lote completo: imprimir o gabarito de folga, testar no
tubo já pintado e fazer o corpo de prova descrito na Fase 3 do plano de montagem.
