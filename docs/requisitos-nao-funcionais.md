# 🧪 Requisitos Não Funcionais

## 📚 Índice

- [Tabela de Requisitos](#-tabela-de-requisitos)
- [Detalhamento](#-detalhamento)
  - [Alta Prioridade](#alta-prioridade)
  - [Média Prioridade](#média-prioridade)
  - [Baixa Prioridade](#baixa-prioridade)

---

## 📊 Tabela de Requisitos

| ID    | Descrição                                                                 | Categoria        | Prioridade |
|-------|---------------------------------------------------------------------------|------------------|------------|
| RNF01 | Tempo de resposta das buscas ≤ 2 segundos                                 | Desempenho       | Alta       |
| RNF02 | Geração de rotas ≤ 3 segundos                                             | Desempenho       | Alta       |
| RNF03 | Gerar roteiro com até 3 interações principais                             | Usabilidade      | Alta       |
| RNF04 | Suportar pelo menos 10.000 usuários simultâneos                           | Escalabilidade   | Média      |
| RNF05 | Disponibilidade mínima de 99%                                             | Confiabilidade   | Alta       |
| RNF06 | Funcionar offline parcialmente (dados salvos)                             | Confiabilidade   | Média      |
| RNF07 | Suportar múltiplos idiomas com troca dinâmica                             | Usabilidade      | Alta       |
| RNF08 | Criptografar dados em trânsito (HTTPS)                                    | Segurança        | Alta       |
| RNF09 | Tratar falhas de conexão e GPS                                            | Confiabilidade   | Média      |
| RNF10 | Carregar mapa e dados de forma progressiva                                | Desempenho       | Média      |
| RNF11 | Compatível com Android moderno                                            | Compatibilidade  | Alta       |
| RNF12 | Minimizar consumo de bateria (uso de GPS)                                 | Desempenho       | Média      |
| RNF13 | Interface clara para usuários estrangeiros                                | Usabilidade      | Alta       |
| RNF14 | Arquitetura desacoplada e de fácil manutenção                             | Manutenibilidade | Média      |
| RNF15 | Integração com APIs externas (mapas, tradução, localização)               | Integração       | Alta       |

---

## 🧩 Detalhamento

### Alta Prioridade

**RNF01 – Desempenho de busca**  
O sistema deve retornar resultados de busca em até 2 segundos após a solicitação do usuário.  
(Categoria: Desempenho)

**RNF02 – Desempenho de rotas**  
O sistema deve gerar rotas em até 3 segundos.  
(Categoria: Desempenho)

**RNF03 – Facilidade de uso**  
O usuário deve conseguir gerar um roteiro completo com no máximo 3 interações principais.  
(Categoria: Usabilidade)

**RNF05 – Disponibilidade**  
O sistema deve estar disponível pelo menos 99% do tempo.  
(Categoria: Confiabilidade)

**RNF07 – Internacionalização**  
O sistema deve permitir troca de idioma de forma dinâmica sem reiniciar a aplicação.  
(Categoria: Usabilidade)

**RNF08 – Segurança de dados**  
O sistema deve garantir criptografia de dados em trânsito utilizando HTTPS.  
(Categoria: Segurança)

**RNF11 – Compatibilidade**  
O sistema deve funcionar em dispositivos Android modernos.  
(Categoria: Compatibilidade)

**RNF13 – Usabilidade para estrangeiros**  
A interface deve ser clara e compreensível para usuários que não falam o idioma local.  
(Categoria: Usabilidade)

**RNF15 – Integração externa**  
O sistema deve integrar-se com APIs externas de mapas, localização e tradução.  
(Categoria: Integração)

---

### Média Prioridade

**RNF04 – Escalabilidade**  
O sistema deve suportar ao menos 10.000 usuários simultâneos sem degradação significativa.  
(Categoria: Escalabilidade)

**RNF06 – Funcionamento offline**  
O sistema deve permitir acesso a dados previamente salvos sem conexão com a internet.  
(Categoria: Confiabilidade)

**RNF09 – Tratamento de falhas**  
O sistema deve lidar com falhas de conexão e GPS exibindo mensagens claras ao usuário.  
(Categoria: Confiabilidade)

**RNF10 – Carregamento progressivo**  
O sistema deve carregar mapas e informações de forma incremental para melhorar a experiência.  
(Categoria: Desempenho)

**RNF12 – Consumo de bateria**  
O sistema deve otimizar o uso de GPS para reduzir consumo de bateria.  
(Categoria: Desempenho)

**RNF14 – Manutenibilidade**  
O sistema deve possuir arquitetura desacoplada para facilitar manutenção e evolução.  
(Categoria: Manutenibilidade)

---

### Baixa Prioridade

(Nenhum requisito crítico adicional nesta categoria)
