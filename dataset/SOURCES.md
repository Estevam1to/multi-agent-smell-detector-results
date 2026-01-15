# 📁 Dataset Sources

Este diretório contém os **20 arquivos Python** usados como dataset para análise de code smells no TCC.

## 🔗 Repositórios Originais

### codespell
- **Repositório:** [codespell-project/codespell](https://github.com/codespell-project/codespell)
- **Descrição:** Ferramenta para verificar erros de ortografia em código-fonte
- **Arquivos incluídos:** 4 arquivos

| Arquivo | Caminho |
|---------|---------|
| `_codespell.py` | `codespell_lib/_codespell.py` |
| `_spellchecker.py` | `codespell_lib/_spellchecker.py` |
| `test_basic.py` | `codespell_lib/tests/test_basic.py` |
| `test_dictionary.py` | `codespell_lib/tests/test_dictionary.py` |

### maltrail
- **Repositório:** [stamparm/maltrail](https://github.com/stamparm/maltrail)
- **Descrição:** Sistema de detecção de tráfego malicioso
- **Arquivos incluídos:** 10 arquivos

| Arquivo | Caminho |
|---------|---------|
| `addr.py` | `core/addr.py` |
| `colorized.py` | `core/colorized.py` |
| `common.py` | `core/common.py` |
| `log.py` | `core/log.py` |
| `settings.py` | `core/settings.py` |
| `update.py` | `core/update.py` |
| `alienvault.py` | `trails/feeds/alienvault.py` |
| `badips.py` | `trails/feeds/badips.py` |
| `dataplane.py` | `trails/feeds/dataplane.py` |
| `torproject.py` | `trails/feeds/torproject.py` |

### mava
- **Repositório:** [instadeepai/mava](https://github.com/instadeepai/mava)
- **Descrição:** Framework para Multi-Agent Reinforcement Learning em JAX
- **Arquivos incluídos:** 6 arquivos

| Arquivo | Caminho |
|---------|---------|
| `ff_ippo.py` | `mava/systems/ppo/anakin/ff_ippo.py` |
| `ff_mappo.py` | `mava/systems/ppo/anakin/ff_mappo.py` |
| `rec_ippo.py` | `mava/systems/ppo/anakin/rec_ippo.py` |
| `ff_isac.py` | `mava/systems/sac/anakin/ff_isac.py` |
| `ff_ippo_store_experience.py` | `mava/advanced_usage/ff_ippo_store_experience.py` |
| `checkpointing.py` | `mava/utils/checkpointing.py` |

## 📊 Resumo do Dataset

| Projeto | Arquivos | Descrição |
|---------|----------|-----------|
| codespell | 4 | Spell checker para código |
| maltrail | 10 | Detecção de tráfego malicioso |
| mava | 6 | Multi-Agent RL Framework |
| **Total** | **20** | - |

## 🏷️ Commits de Referência

### Projeto multi-agent-smell-detector (API)
- **Repositório:** [Estevam1to/multi-agent-smell-detector](https://github.com/Estevam1to/multi-agent-smell-detector)
- **Commit de referência:** `e5e488f` - *feat: adiciona comparação entre LLMs (Claude, GPT, DeepSeek) e análise de eficiência*

### Histórico de commits relevantes:
```
e5e488f feat: adiciona comparação entre LLMs (Claude, GPT, DeepSeek) e análise de eficiência
a86d491 docs: atualizar README com resultados e nova estrutura
55bd805 refactor: substituir gráficos por figuras acadêmicas
1d65230 feat: adiciona script run_simple_only.py para comparação justa
fea0793 feat: análise completa das Research Questions para TCC
3bf3976 feat: remove dataset
```

## 📋 Ground Truth

O ground truth foi gerado manualmente com validação de **411 code smells** identificados nos 20 arquivos Python. O arquivo filtrado está disponível em:
- `../ground_truth/implementation_smells_manual_filtered.csv`

---

*Dataset coletado em Janeiro/2025 para o TCC de Engenharia de Software - UFC*
