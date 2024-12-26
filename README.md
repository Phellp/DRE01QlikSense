![CapaGit](https://github.com/user-attachments/assets/a0b6e249-460d-4aa2-9a7d-17ef4dcef51b)


Esse é um projeto de Business Intelligence.

Os conjuntos de dados utilizados estão disponíveis no repositório "Bases".


# Entendimento do Negócio para Construção da DRE
Nome da Empresa Fictícia: Alpha Tech Solutions
Contexto Geral:
A Alpha Tech Solutions é uma empresa fictícia do setor de tecnologia, especializada no desenvolvimento e comercialização de software de gestão empresarial (ERP). Ela atende pequenas e médias empresas, oferecendo soluções que variam de licenças únicas a modelos SaaS (Software as a Service).

Com o crescimento da operação e a diversificação das receitas, a gestão financeira identificou a necessidade de uma Demonstração do Resultado do Exercício (DRE) detalhada, que atenda à estrutura abaixo, para aumentar a clareza sobre as operações financeiras e dar suporte à tomada de decisão estratégica.

Objetivos da DRE:
Consolidar todas as fontes de receitas e custos.
Garantir visibilidade das despesas fixas e variáveis para identificar oportunidades de otimização.
Obter informações claras sobre margens de contribuição e resultados operacionais.
Integrar dados de ativos e caixa para projetar saúde financeira.

### Estrutura da DRE Utilizada:
<br>
<H4> 🟩 RECEITA BRUTA </H4>

Receita com Serviços: Subscrições de SaaS e serviços de personalização.
Receita com Produtos: Venda de licenças e módulos adicionais.
Outras Receitas: Juros sobre aplicações financeiras ou receitas esporádicas.

<br>
<H4> 🟨 DEDUÇÕES DA RECEITA </H4>

Devoluções e Reembolsos: Cancelamentos e ajustes relacionados ao faturamento.
Impostos sobre Faturamento: ISS, PIS, COFINS e outros tributos aplicáveis.
Outras Deduções da Receita: Descontos comerciais e abatimentos concedidos.
RECEITA LÍQUIDA

<br>
<H4> 🟫 CUSTO DE PRODUTOS </H4>

Frete: Custos de transporte associados à entrega de produtos físicos.
Outros Custos de Produtos: Custos de insumos para desenvolvimento ou produção.
LUCRO BRUTO

<br>
<H4> 🟦 DESPESAS VARIÁVEIS </H4>

Anúncios e Propagandas: Investimentos em campanhas de marketing.
Tarifas Meios de Pagamento: Taxas cobradas por operadoras de pagamento online.
Comissões: Percentuais destinados a vendedores ou parceiros.
Outras Despesas Variáveis: Custos relacionados ao volume de vendas.
MARGEM DE CONTRIBUIÇÃO

<br>
<H4> 🟪 DESPESAS FIXAS </H4>

Pessoal: Salários, encargos e benefícios.
Ocupação: Aluguel, energia elétrica e água.
TI/SAAS: Custos com ferramentas tecnológicas e infraestrutura.
Serviços: Honorários de consultorias e suporte externo.
Outros Custos Operacionais: Gastos administrativos gerais.
RESULTADO OPERACIONAL

<br>
<H4> ⬛️ IMPOSTOS SOBRE LUCRO </H4>

IRPJ: Imposto de Renda Pessoa Jurídica.
CSLL: Contribuição Social sobre o Lucro Líquido.
DAS: Documento de Arrecadação do Simples Nacional (se aplicável).
LUCRO LÍQUIDO

<br>
<H4> 🔲 OUTROS ATIVOS </H4>

Máquinas e Equipamentos: Investimentos em hardware necessário para operação.
Móveis e Outras Mobílias: Bens móveis relacionados ao ambiente de trabalho.

<br>
<H4> 💲 CAIXA </H4>

Saldo disponível para investimentos, expansão e capital de giro.

# Modelagem dos Dados

Durante a limpeza e transformação dos dados, várias tarefas foram aplicadas utilizando o AQL. Além dessa etapa ser fundamental para tratar possíveis inconsistências nos dados, ela também nos permitiu criar uma modelagem eficiênte através do modelo Star Schema. 
![image](https://github.com/user-attachments/assets/fcb25867-0bf8-4bd6-9d12-41da3cd1e4fa)


Conclusão:
A estrutura apresentada permitirá à Alpha Tech Solutions monitorar detalhadamente a performance financeira em cada etapa do processo operacional. Com isso, será possível identificar gargalos financeiros, medir a eficiência operacional e fornecer relatórios financeiros claros e estratégicos para investidores e gestores.
