# <NOME_DO_PROJETO>

## 📌 Resumo

Este aplicativo tem como objetivo funcionar como um **guia turístico digital**, ajudando usuários a descobrir e explorar destinos.  
A plataforma fornecerá informações relevantes para viajantes, como:

- Pontos turísticos próximos
- Restaurantes e locais para comer
- Tempo estimado de deslocamento
- Informações úteis sobre cada local

O objetivo é **facilitar a exploração de cidades e melhorar a experiência de viagem**, oferecendo recomendações práticas e acessíveis diretamente no aplicativo.

---

## 👤 Personas

### Turista
Pessoa visitando uma cidade ou região que deseja descobrir lugares interessantes para visitar, comer ou explorar.

### Morador Local
Pessoa que vive na região e quer descobrir novos lugares próximos ou recomendações interessantes.

### Administrador do Sistema
Responsável por manter o sistema atualizado, adicionando ou gerenciando informações sobre locais turísticos e estabelecimentos.

---

## ⚠️ Principais Dores

- Dificuldade em encontrar **pontos turísticos relevantes próximos**
- Falta de informações organizadas sobre **lugares para comer ou visitar**
- Perda de tempo pesquisando em múltiplos aplicativos
- Falta de contexto sobre **tempo de deslocamento entre locais**
- Informações turísticas dispersas ou desatualizadas

---

## Requisitos Funcionais


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

## Requisitos Não Funcionais

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

## 1. ✅ Requisitos Funcionais (Detalhados)
### 🔥 Alta Prioridade

RF01 – Pesquisa de locais
O sistema deve permitir ao usuário pesquisar locais por nome, categoria ou localização atual, retornando resultados relevantes com base na consulta.

RF03 – Detalhes do local
O sistema deve exibir informações completas do local selecionado, incluindo descrição, imagens, horário de funcionamento e faixa de preço.

RF04 – Status do local
O sistema deve informar se o local está aberto ou fechado com base no horário atual.

RF05 – Filtro por preço
O sistema deve permitir filtrar locais por faixa de preço (gratuito, baixo, médio, alto).

RF08 – Geração de rotas personalizadas
O sistema deve gerar rotas automaticamente com base no tempo disponível, localização atual e preferências do usuário.

RF09 – Roteiros prontos
O sistema deve oferecer roteiros pré-definidos (ex: 1 dia, 2 dias, 3 dias) com sequência de locais organizada.

RF10 – Otimização de rotas
O sistema deve organizar a ordem dos locais na rota visando minimizar tempo de deslocamento e distância.

RF11 – Modal de transporte
O sistema deve permitir ao usuário selecionar o tipo de transporte (a pé, transporte público ou carro) e adaptar a rota.

RF12 – Visualização em mapa
O sistema deve exibir a rota gerada em mapa com tempo estimado de deslocamento.

RF13 – Custo-benefício
O sistema deve destacar locais com melhor relação entre qualidade e preço.

RF16 – Suporte a múltiplos idiomas
O sistema deve permitir que a interface seja exibida em diferentes idiomas.

RF17 – Tradução automática
O sistema deve traduzir automaticamente conteúdos relevantes para o idioma do usuário.

### ⚖️ Média Prioridade

RF02 – Listagem categorizada
O sistema deve organizar os locais em categorias como turismo, alimentação e experiências.

RF06 – Avaliações
O sistema deve exibir a média das avaliações e quantidade de avaliações de cada local.

RF07 – Comentários
O sistema deve permitir visualizar comentários feitos por outros usuários.

RF14 – Personalização por perfil
O sistema deve adaptar recomendações com base no perfil do usuário (econômico, prático, premium).

RF15 – Hidden gems
O sistema deve destacar locais menos conhecidos com base em baixa popularidade e boas avaliações.

RF18 – Informações práticas
O sistema deve exibir informações adicionais como segurança, contexto cultural e dicas locais.

RF19 – Favoritos
O sistema deve permitir salvar locais como favoritos para acesso posterior.

RF20 – Salvar roteiros
O sistema deve permitir salvar rotas geradas para reutilização futura.

RF22 – Rotas seguras
O sistema deve priorizar rotas consideradas seguras, especialmente para turistas estrangeiros.

### 🧊 Baixa Prioridade

RF21 – Atualização de localização
O sistema deve atualizar automaticamente a localização do usuário em tempo real, mediante consentimento.

RF23 – Curadoria premium
O sistema deve apresentar locais selecionados com base em curadoria especializada.

RF24 – Avaliações detalhadas
O sistema deve permitir diferenciação entre avaliações rápidas (nota) e avaliações detalhadas (comentários estruturados).

## 2. ⚙️ Requisitos Não Funcionais (Detalhados)
### 🔥 Alta Prioridade

RNF01 – Desempenho de busca
O sistema deve retornar resultados de busca em até 2 segundos após a solicitação do usuário.
(Categoria: Desempenho)

RNF02 – Desempenho de rotas
O sistema deve gerar rotas em até 3 segundos.
(Categoria: Desempenho)

RNF03 – Facilidade de uso
O usuário deve conseguir gerar um roteiro completo com no máximo 3 interações principais.
(Categoria: Usabilidade)

RNF05 – Disponibilidade
O sistema deve estar disponível pelo menos 99% do tempo.
(Categoria: Confiabilidade)

RNF07 – Internacionalização
O sistema deve permitir troca de idioma de forma dinâmica sem reiniciar a aplicação.
(Categoria: Usabilidade)

RNF08 – Segurança de dados
O sistema deve garantir criptografia de dados em trânsito utilizando HTTPS.
(Categoria: Segurança)

RNF11 – Compatibilidade
O sistema deve funcionar em dispositivos Android modernos.
(Categoria: Compatibilidade)

RNF13 – Usabilidade para estrangeiros
A interface deve ser clara e compreensível para usuários que não falam o idioma local.
(Categoria: Usabilidade)

RNF15 – Integração externa
O sistema deve integrar-se com APIs externas de mapas, localização e tradução.
(Categoria: Integração)

### ⚖️ Média Prioridade

RNF04 – Escalabilidade
O sistema deve suportar ao menos 10.000 usuários simultâneos sem degradação significativa.
(Categoria: Escalabilidade)

RNF06 – Funcionamento offline
O sistema deve permitir acesso a dados previamente salvos sem conexão com a internet.
(Categoria: Confiabilidade)

RNF09 – Tratamento de falhas
O sistema deve lidar com falhas de conexão e GPS exibindo mensagens claras ao usuário.
(Categoria: Confiabilidade)

RNF10 – Carregamento progressivo
O sistema deve carregar mapas e informações de forma incremental para melhorar a experiência.
(Categoria: Desempenho)

RNF12 – Consumo de bateria
O sistema deve otimizar o uso de GPS para reduzir consumo de bateria.
(Categoria: Desempenho)

RNF14 – Manutenibilidade
O sistema deve possuir arquitetura desacoplada para facilitar manutenção e evolução.
(Categoria: Manutenibilidade)

### 🧊 Baixa Prioridade

(Nenhum requisito crítico adicional nesta categoria)

---

## 🛠 Tecnologias

> *Lista inicial de tecnologias do projeto*

- <Tecnologia 1>
- <Tecnologia 2>
- <Tecnologia 3>
- <Framework / Biblioteca>
- <Banco de dados>

---

## 👥 Membros

| Nome | RA |
|------|------|
| Felipe Leite Conrado | 0030482511011 |
| Ricardo Akimoto | 0030482511031 | 
| André | 0030482421043 |
| Kevin | 0030482421034 |
