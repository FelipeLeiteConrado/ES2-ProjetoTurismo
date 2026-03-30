# ⚙️ Requisitos Funcionais

## 📚 Índice

- [Tabela de Requisitos](#-tabela-de-requisitos)
- [Detalhamento](#-detalhamento)
  - [Alta Prioridade](#alta-prioridade)
  - [Média Prioridade](#média-prioridade)
  - [Baixa Prioridade](#baixa-prioridade)

---

## 📊 Tabela de Requisitos

| ID   | Descrição                                                                 | Categoria              | Prioridade |
|------|---------------------------------------------------------------------------|------------------------|------------|
| RF01 | Permitir pesquisar locais por nome, categoria ou localização atual        | Busca                  | Alta       |
| RF02 | Exibir locais categorizados (turismo, alimentação, experiências)          | Exibição               | Média      |
| RF03 | Exibir detalhes do local (descrição, imagens, horário, preço)             | Exibição               | Alta       |
| RF04 | Indicar se o local está aberto ou fechado                                 | Informação             | Alta       |
| RF05 | Filtrar locais por faixa de preço                                         | Filtro                 | Alta       |
| RF06 | Exibir avaliação média e número de avaliações                             | Avaliação              | Média      |
| RF07 | Permitir visualizar comentários de outros usuários                        | Avaliação              | Média      |
| RF08 | Gerar rotas personalizadas com base em tempo e preferências               | Roteirização           | Alta       |
| RF09 | Gerar roteiros prontos (1, 2, 3 dias)                                     | Roteirização           | Alta       |
| RF10 | Otimizar rotas considerando distância e tempo                             | Roteirização           | Alta       |
| RF11 | Permitir seleção de modal de transporte                                   | Navegação              | Alta       |
| RF12 | Exibir rota em mapa com tempo estimado                                    | Navegação              | Alta       |
| RF13 | Sugerir locais com melhor custo-benefício                                 | Recomendação           | Alta       |
| RF14 | Sugerir locais com base no perfil do usuário                              | Recomendação           | Média      |
| RF15 | Destacar “hidden gems”                                                    | Recomendação           | Média      |
| RF16 | Suportar múltiplos idiomas                                                | Internacionalização    | Alta       |
| RF17 | Traduzir automaticamente conteúdos                                        | Internacionalização    | Alta       |
| RF18 | Exibir informações práticas (segurança, cultura, dicas)                   | Informação             | Média      |
| RF19 | Permitir salvar locais favoritos                                          | Personalização         | Média      |
| RF20 | Permitir salvar roteiros                                                  | Personalização         | Média      |
| RF21 | Atualizar localização do usuário (com consentimento)                      | Localização            | Baixa      |
| RF22 | Priorizar rotas seguras                                                   | Segurança              | Média      |
| RF23 | Apresentar experiências premium (curadoria)                               | Recomendação           | Baixa      |
| RF24 | Diferenciar avaliações rápidas e detalhadas                               | Avaliação              | Baixa      |

---

## 🧩 Detalhamento

### Alta Prioridade

**RF01 – Pesquisa de locais**  
O sistema deve permitir ao usuário pesquisar locais por nome, categoria ou localização atual, retornando resultados relevantes com base na consulta.

**RF03 – Detalhes do local**  
O sistema deve exibir informações completas do local selecionado, incluindo descrição, imagens, horário de funcionamento e faixa de preço.

**RF04 – Status do local**  
O sistema deve informar se o local está aberto ou fechado com base no horário atual.

**RF05 – Filtro por preço**  
O sistema deve permitir filtrar locais por faixa de preço (gratuito, baixo, médio, alto).

**RF08 – Geração de rotas personalizadas**  
O sistema deve gerar rotas automaticamente com base no tempo disponível, localização atual e preferências do usuário.

**RF09 – Roteiros prontos**  
O sistema deve oferecer roteiros pré-definidos (ex: 1 dia, 2 dias, 3 dias) com sequência de locais organizada.

**RF10 – Otimização de rotas**  
O sistema deve organizar a ordem dos locais na rota visando minimizar tempo de deslocamento e distância.

**RF11 – Modal de transporte**  
O sistema deve permitir ao usuário selecionar o tipo de transporte (a pé, transporte público ou carro) e adaptar a rota.

**RF12 – Visualização em mapa**  
O sistema deve exibir a rota gerada em mapa com tempo estimado de deslocamento.

**RF13 – Custo-benefício**  
O sistema deve destacar locais com melhor relação entre qualidade e preço.

**RF16 – Suporte a múltiplos idiomas**  
O sistema deve permitir que a interface seja exibida em diferentes idiomas.

**RF17 – Tradução automática**  
O sistema deve traduzir automaticamente conteúdos relevantes para o idioma do usuário.

---

### Média Prioridade

**RF02 – Listagem categorizada**  
O sistema deve organizar os locais em categorias como turismo, alimentação e experiências.

**RF06 – Avaliações**  
O sistema deve exibir a média das avaliações e quantidade de avaliações de cada local.

**RF07 – Comentários**  
O sistema deve permitir visualizar comentários feitos por outros usuários.

**RF14 – Personalização por perfil**  
O sistema deve adaptar recomendações com base no perfil do usuário (econômico, prático, premium).

**RF15 – Hidden gems**  
O sistema deve destacar locais menos conhecidos com base em baixa popularidade e boas avaliações.

**RF18 – Informações práticas**  
O sistema deve exibir informações adicionais como segurança, contexto cultural e dicas locais.

**RF19 – Favoritos**  
O sistema deve permitir salvar locais como favoritos para acesso posterior.

**RF20 – Salvar roteiros**  
O sistema deve permitir salvar rotas geradas para reutilização futura.

**RF22 – Rotas seguras**  
O sistema deve priorizar rotas consideradas seguras, especialmente para turistas estrangeiros.

---

### Baixa Prioridade

**RF21 – Atualização de localização**  
O sistema deve atualizar automaticamente a localização do usuário em tempo real, mediante consentimento.

**RF23 – Curadoria premium**  
O sistema deve apresentar locais selecionados com base em curadoria especializada.

**RF24 – Avaliações detalhadas**  
O sistema deve permitir diferenciação entre avaliações rápidas (nota) e avaliações detalhadas (comentários estruturados).
