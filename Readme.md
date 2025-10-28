# Análise de Comunidades de Abelhas do Cerrado 🐝
# Composição/diversidade de comunidades de abelhas em função da estrutura da paisagem (proporção de habitat natural x heterogeneidade)
## 📋 Sobre o Projeto

*Pergunta: Como a composição e a diversidade de abelhas respondem à estrutura da paisagem, considerando a proporção de habitat natural e a heterogeneidade de usos e coberturas do solo?*

**H1:** A diversidade e a composição de abelhas estão mais fortemente associadas à proporção de habitat natural, de modo que áreas com maior cobertura natural apresentam maior diversidade de espécies.

**H2:** Mosaicos de diferentes classes de uso e cobertura do solo oferecem recursos complementares que sustentam maior diversidade e mantêm comunidades distintas, tornando a heterogeneidade da paisagem um preditor mais importante.

**H0:** Não há associação significativa entre a proporção de habitat natural e a heterogeneidade da paisagem e os padrões de diversidade e composição de abelhas neste estudo. As diferenças observadas podem ser atribuídas ao acaso ou a fatores não identificados na presente abordagem.

**Delineamento:**
- 6 locais (3 bordas urbanas + 3 zonas rurais)
- 9 pontos por local
- Total: 54 pontos amostrais

## 📊 Ver Resultados

**[🔗 Clique aqui para ver o relatório completo](Outputs/analise_abelhas.html)**

## 📂 Estrutura do Repositório
```
abelhas-cerrado/
├── dados/           # Dados brutos (Cap2.xlsx)
├── analise/         # Script R Markdown
├── outputs/         # Relatório HTML e figuras
└── README.md        # Este arquivo
```

## 🔧 Reproduzir as Análises

### Requisitos
- R (≥ 4.0.0)
- RStudio
- Pacotes: tidyverse, vegan, lme4, MuMIn, ggplot2

### Passos
1. Clone ou baixe este repositório
2. Abra `analise/analise_abelhas.Rmd` no RStudio
3. Instale os pacotes necessários (se ainda não tiver)
4. Clique no botão "Knit"
5. O relatório será gerado em `outputs/`

## 📈 Principais Análises

- **GLMM**: Efeito de habitat natural e heterogeneidade na riqueza (n=54 pontos, controle de pseudorreplicação)
- **NMDS**: Ordenação da composição de espécies
- **PERMANOVA**: Teste de efeito de variáveis ambientais
- **ANOSIM**: Diferenças entre bordas urbanas e zonas rurais
- **IndVal e SIMPER**: Espécies indicadoras

## 👤 Autor

**Seu Nome**  
Programa de Pós-Graduação em [Sua área]  
Universidade [Nome]

## 📧 Contato

Email: seuemail@exemplo.com

---

*Última atualização: Outubro 2025*
```

**⚠️ IMPORTANTE:** Troque:
- `Seu Nome` → seu nome real
- `[Sua área]` → sua área (ex: Ecologia)
- `[Nome]` → nome da universidade
- `seuemail@exemplo.com` → seu email

---

### **3. Salvar**
1. No Bloco de Notas: **Arquivo** → **Salvar como...**
2. **Onde salvar:** Dentro da pasta `abelhas-cerrado/` (na **raiz**, não nas subpastas!)
3. **Nome do arquivo:** `README.md` (exatamente assim)
4. **Tipo:** Mude de "Documentos de texto (*.txt)" para **"Todos os arquivos (*.*)"** ← **CRUCIAL!**
5. Clique **Salvar**

---

## **✅ VERIFICAR**

Sua pasta deve estar assim:
```
📁 abelhas-cerrado/
   ├── 📄 README.md              ← NOVO!
   ├── 📁 dados/
   │   └── Cap2.xlsx
   ├── 📁 analise/
   │   └── analise_abelhas.Rmd
   └── 📁 outputs/

       └── analise_abelhas.html
