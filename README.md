<h1>📊 iFood Case Técnico – Data Analytics</h1>

<p>Este repositório contém a solução desenvolvida para o <strong>Case Técnico de Data Analytics do iFood</strong>, com foco na análise de uma campanha de cupons via teste A/B. O objetivo do projeto foi avaliar o impacto da ação na retenção de usuários, explorar segmentações relevantes e propor melhorias com base em dados.</p>

<hr>

<h2>📁 Estrutura do Repositório</h2>

<pre>
📦 case_teste_AB_cupons
├── notebooks/
│   ├── etl_process.ipynb                                    # Notebook de ingestão e transformação dos dados
│   ├── Case_pergunta_1.ipynb                                # Análise do impacto do teste A/B
│   ├── Case_pergunta_2.ipynb                                # Segmentações e análises por perfil
│   ├── ddd_estados.csv                                      # Base de dados com os DDDs e seus estados
├── apresentacao/
│   └── Relatório de análise da Campanha de Cupons.pdf       # Relatório final com insights e recomendações
│   └── Apresentação de análise da Campanha de Cupons.ppt    # Apresentação final com insights e recomendações
└── Case_Técnico_Data_Analytics_-_iFood                      # Case Técnico com instruções solicitadas 
└── README.md                                                # Este documento
</pre>

<hr>

<h2>🧪 Descrição do Case</h2>

<p>O projeto simula um cenário real no qual o time de dados do iFood analisa os resultados de um teste A/B sobre uma campanha de cupons. Os objetivos principais foram:</p>
<ul>
  <li>Analisar a <strong>efetividade do cupom</strong> na <strong>retenção de usuários</strong>.</li>
  <li>Realizar <strong>análise financeira</strong> da campanha.</li>
  <li>Desenvolver <strong>segmentações de usuários</strong> para personalização futura.</li>
  <li>Propor <strong>melhorias estratégicas</strong> com base em dados e hipóteses validadas.</li>
</ul>

<hr>

<h2>✅ Requisitos para Execução</h2>

<ul>
  <li>Ambiente: Databricks Free Edition</li>
  <li>Linguagem: Python 3.11+</li>
  <li>Bibliotecas: <code>pyspark</code>, <code>pandas</code>, <code>matplotlib</code>, <code>seaborn</code></li>
</ul>

<hr>

<h2>📌 Como Executar</h2>

<ol>
  <li>Clone o repositório:
    <pre><code>git clone https://github.com/seu-usuario/case_teste_AB_cupons.git
cd case_teste_AB_cupons</code></pre>
  </li>
  <li>Acesse os notebooks na pasta <code>/notebooks</code>.</li>
  <li>Garanta que os datasets originais estejam disponíveis no ambiente:
    <ul>
      <li><code>order.json.gz</code></li>
      <li><code>consumer.csv.gz</code></li>
      <li><code>restaurant.csv.gz</code></li>
      <li><code>ab_test_ref.csv</code></li>
      <li><code>ddd_estados.csv</code> disponibilizado na pasta notebooks fonte <a href="https://dados.gov.br/dados/conjuntos-dados/codigos-nacionais-cn" target="_blank">site dados.gov</a>.</li>
    </ul>
  </li>
</ol>

<hr>

<h2>📬 Contato</h2>
<p>Em caso de dúvidas ou sugestões, fique à vontade para entrar em contato via <a href="https://www.linkedin.com/in/emanoele-graniel-urias/" target="_blank">LinkedIn</a>.</p>
