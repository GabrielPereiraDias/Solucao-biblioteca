# 📚 Ler é Crescer - Proposta de Solução

## Sobre o Projeto

Este projeto foi desenvolvido como proposta de solução para o desafio apresentado pelo SENAI ao curso Técnico em Desenvolvimento de Sistemas.

O objetivo é modernizar a gestão da Rede Municipal de Bibliotecas Comunitárias **"Ler é Crescer"**, composta por três unidades físicas, substituindo processos manuais por uma solução tecnológica integrada.

---

# Contexto

Atualmente, a rede realiza o controle de empréstimos, devoluções e do acervo por meio de cadernos e planilhas, ocasionando:

- perda de livros;
- atrasos não identificados;
- dificuldade em localizar exemplares entre as unidades;
- ausência de sincronização das informações;
- deterioração de livros antigos devido à umidade e às variações de temperatura.

Além disso, a solução deveria respeitar um orçamento máximo de **R$ 18.000,00**.

---

# Objetivos

Nossa proposta busca:

- centralizar o gerenciamento do acervo;
- permitir empréstimos sincronizados entre as três unidades;
- preservar livros antigos por meio de monitoramento ambiental;
- atender aos requisitos da LGPD;
- apresentar uma solução financeiramente viável e escalável.

---

# Como chegamos à solução

Após analisar o cenário apresentado, identificamos dois grandes problemas:

## Gestão do acervo

O controle manual impossibilita a atualização em tempo real das informações, dificultando a localização dos livros e aumentando a ocorrência de erros.

Para resolver esse problema, optamos por um **banco de dados centralizado na nuvem**, permitindo que todas as unidades compartilhem as mesmas informações instantaneamente.

---

## Preservação do patrimônio

Os livros antigos sofrem deterioração devido à alta umidade, especialmente na unidade instalada em um porão.

Após pesquisar alternativas de baixo custo, optamos pelo uso de sensores IoT capazes de monitorar continuamente temperatura e umidade.

Quando a umidade atingir um nível crítico, tomadas inteligentes acionam automaticamente os desumidificadores, preservando o acervo sem necessidade de intervenção humana.

---

# Tecnologias Utilizadas

## Software

- Banco de Dados em Nuvem
- Sistema Web para gerenciamento do acervo
- Controle de usuários e permissões
- Backup de dados
- Adequação à LGPD

## Hardware

- ESP32
- Sensor DHT22
- Tomadas Inteligentes Wi-Fi
- Desumidificadores de Ar
- Infraestrutura de rede

---

# Arquitetura da Solução

A proposta conecta as três bibliotecas a um banco de dados central hospedado na nuvem.

Cada unidade possui um kit IoT formado por um ESP32 e um sensor DHT22 responsável pelo monitoramento ambiental.

Quando a umidade ultrapassa os limites definidos, o sistema aciona automaticamente os desumidificadores através das tomadas inteligentes, protegendo os livros.

Ao mesmo tempo, todos os empréstimos e devoluções são registrados em tempo real, mantendo o acervo sincronizado entre as unidades.

---

# Investimento

| Item | Valor |
|-------|-------:|
| Hardware e infraestrutura | **R$ 13.560,00** |
| Reserva técnica | **R$ 4.440,00** |
| **Orçamento total disponível** | **R$ 18.000,00** |

A proposta permanece dentro do orçamento disponibilizado pela diretoria.

---

# Benefícios Esperados

- Controle centralizado do acervo;
- Atualização em tempo real dos empréstimos;
- Redução de perdas de livros;
- Maior segurança das informações;
- Preservação preventiva dos livros antigos;
- Conformidade com a LGPD;
- Solução preparada para expansão futura.

---

# Conclusão

A solução proposta integra tecnologia da informação e Internet das Coisas (IoT) para resolver os principais desafios enfrentados pela Rede Municipal de Bibliotecas Comunitárias "Ler é Crescer".

Com um investimento compatível com o orçamento disponível, a proposta oferece uma infraestrutura moderna, automatizada e escalável, melhorando a gestão do acervo, garantindo a sincronização entre as unidades e preservando o patrimônio bibliográfico por meio do controle inteligente da umidade.
