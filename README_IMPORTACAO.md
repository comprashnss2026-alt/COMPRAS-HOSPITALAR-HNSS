# Dados de estoque e consumo do HNSS

Arquivos incluídos:

- `rptprodutobalancocentrocusto(3).chr`: saldo atual por produto da Farmácia.
- `rptconsumoanalitico(3).chr`: consumo analítico de 23/06/2026 a 21/09/2026.
- `estoque_farmacia_importacao.csv`: versão normalizada para importar produtos e saldo.
- `consumo_analitico_importacao.csv`: versão normalizada para histórico e Curva ABC.

O projeto não grava esses dados automaticamente no Supabase. A importação deve ser feita após liberar as permissões de INSERT/UPDATE necessárias.
