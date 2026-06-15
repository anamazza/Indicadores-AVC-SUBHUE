# Indicadores AVC — SUBHUE

Painel de qualidade clínica do AVC da rede municipal de saúde do Rio de Janeiro (SMS-RJ / SUBHUE).

A página inicial permite escolher entre duas unidades:

- **CER Leblon** — reperfusão e tempos de cuidado, série histórica 2023 a 2026 (dados RES-Q).
- **Hospital Municipal Pedro II** — reperfusão, tempo, processo e desfecho no 3º e 4º trimestres de 2025 (dados ANGELS, anonimizados).

## Como visualizar

Abra `index.html` em qualquer navegador. Não há dependências locais: os gráficos usam Chart.js via CDN.

Para publicar online, ative o GitHub Pages nas configurações do repositório (branch `main`, pasta raiz). O painel ficará acessível pela URL gerada.

## Indicadores

- Trombólise endovenosa (% dos isquêmicos)
- Porta-agulha (mediana) e proporção abaixo de 45 e 60 minutos
- Porta-imagem (mediana)
- Rastreio de disfagia (Pedro II)
- Modo de chegada e destino na alta
- Prevenção secundária na alta
- Óbito hospitalar
- Comparativo entre os anos (CER Leblon)

## Dados

Os dados são agregados e desidentificados. Nenhuma informação que identifique pacientes está incluída.

## Tecnologia

HTML, CSS e JavaScript em arquivo único, com Chart.js para os gráficos.
