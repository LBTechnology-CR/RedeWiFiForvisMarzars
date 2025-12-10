# Projeto de Infraestrutura de Rede – Forvis Mazars

## 1. Visão Geral do Projeto

Este projeto teve como objetivo a reestruturação e fortalecimento da infraestrutura de rede da **Forvis Mazars**, com foco em **segurança interna**, **controle de acessos**, **governança de usuários**, **filtragem de conteúdo** e **melhoria significativa no desempenho do Wi‑Fi corporativo**.

A iniciativa partiu da necessidade de maior visibilidade, controle e confiabilidade sobre o tráfego interno e externo, garantindo uma rede alinhada às boas práticas de segurança e preparada para crescimento.

---

## 2. Contexto Inicial (Problemas Identificados)

Antes da implementação, o ambiente apresentava desafios clássicos de redes corporativas em crescimento:

* Baixo controle sobre acessos internos e externos
* Falta de padronização nas liberações de rede
* Dificuldade na identificação e classificação de sites acessados
* Ausência de bloqueios efetivos de conteúdos inadequados (ex.: conteúdo adulto)
* Controle limitado de usuários por tipo de acesso
* Wi‑Fi com desempenho inconsistente e pouca segmentação
* Dependência excessiva de regras manuais e pouco rastreáveis

Resultado: ambiente funcional, porém vulnerável, pouco escalável e com risco operacional.

---

## 3. Objetivos do Projeto

Os principais objetivos definidos foram claros e mensuráveis:

* Elevar o nível de **segurança interna da rede**
* Criar **controle granular de acessos** (interno e externo)
* Organizar e padronizar **liberações de acesso**
* Melhorar o **controle e identificação de usuários**
* Implementar **leitura, classificação e bloqueio de sites**
* Bloquear **conteúdos inadequados**, com destaque para conteúdo adulto
* Otimizar o **desempenho e estabilidade do Wi‑Fi corporativo**
* Separar ambientes (corporativo, mobile e guest)

---

## 4. Arquitetura da Solução

A solução adotada foi baseada em segmentação lógica, controle centralizado e aplicação de políticas de segurança em camadas.

### Componentes Principais:

* Firewall FortiGate como ponto central de controle
* Switches gerenciáveis (Aruba / HP)
* VLANs bem definidas para isolamento de tráfego
* Rede Wi‑Fi segmentada por perfil de uso
* Políticas de firewall, web filtering e controle de aplicações
* Integração com controladora Wi‑Fi

### Segmentação de Rede (Resumo):

* **Rede Corporativa (Corp)** – usuários internos
* **Rede Mobile** – dispositivos móveis corporativos
* **Rede Guest** – visitantes com acesso restrito
* **Rede de Gerência** – administração de equipamentos

Essa abordagem reduziu drasticamente riscos de movimentação lateral e melhorou a performance geral da rede.

---

## 5. Etapas de Implementação

### 5.1 Levantamento Inicial

* Mapeamento da topologia existente
* Identificação de ativos de rede
* Análise do tráfego interno e externo
* Levantamento dos pontos críticos de segurança

### 5.2 Planejamento da Solução

* Definição da nova segmentação de rede
* Planejamento de VLANs
* Criação das políticas de acesso
* Definição de regras de firewall
* Estruturação das regras de navegação e filtragem de sites

### 5.3 Implementação Técnica

* Configuração do FortiGate
* Criação e aplicação das VLANs
* Implementação das políticas de firewall (inbound e outbound)
* Configuração de Web Filtering
* Bloqueio de categorias indesejadas (conteúdo adulto)
* Controle de acesso por tipo de usuário
* Ajustes finos para melhoria de performance do Wi‑Fi
* Testes de conectividade e navegação

### 5.4 Validação e Ajustes

* Testes de acesso interno
* Testes de navegação externa
* Validação das políticas de bloqueio
* Ajustes de desempenho no Wi‑Fi
* Monitoramento inicial pós‑implantação

---

## 6. Resultados Obtidos

Após a implementação, os ganhos foram claros e perceptíveis:

* Aumento significativo da **segurança interna**
* Maior controle e rastreabilidade dos acessos
* Liberações de rede mais organizadas e seguras
* Identificação clara dos sites acessados
* Bloqueio efetivo de conteúdos inadequados
* Melhor experiência dos usuários no Wi‑Fi
* Redução de incidentes relacionados à navegação
* Ambiente mais estável e previsível

---

## 7. Tecnologias Utilizadas (Keywords / SEO)

* FortiGate / Fortinet
* Firewall Corporativo
* VLANs
* Web Filtering
* Controle de Acesso
* Segurança de Rede
* Wi‑Fi Corporativo
* Segmentação de Rede
* Políticas de Firewall
* Controle de Conteúdo
* Governança de TI
* Boas Práticas de Segurança

---

## 8. Boas Práticas Aplicadas

* Princípio do menor privilégio
* Separação de ambientes críticos
* Centralização de políticas de segurança
* Padronização de acessos
* Documentação da topologia

---

## 9. Lições Aprendidas

* Segmentação bem planejada impacta diretamente desempenho e segurança
* Wi‑Fi corporativo exige políticas tão rígidas quanto a rede cabeada
* Governança de acessos reduz retrabalho e incidentes
* Segurança e usabilidade precisam caminhar juntas

---

## 10. Status do Projeto

✅ Projeto concluído e em operação

📈 Ambiente preparado para evoluções futuras, incluindo novas políticas, integrações e melhorias contínuas.

---

> Este projeto faz parte do portfólio de infraestrutura de redes e segurança, com foco em ambientes corporativos críticos e alta disponibilidade.
