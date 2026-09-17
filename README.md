# aquario-digital-core
# Missão Aquário Digital

## Protocolo de Versionamento e Gestão de Ecossistema

Este projeto foi desenvolvido para a atividade de Garantia da Qualidade de Software.

O objetivo é desenvolver um módulo responsável pelo monitoramento da qualidade da água de um aquário, verificando os níveis de pH e temperatura.

## Fluxo de Desenvolvimento

O projeto utiliza três ambientes principais:

### Develop

Branch destinada ao desenvolvimento das funcionalidades do sistema.

As novas funcionalidades são implementadas e testadas inicialmente neste ambiente.

### Stage

Branch destinada ao ambiente de testes e homologação.

Após a implementação e revisão na branch develop, as alterações são promovidas para stage para validação antes da publicação.

### Main

Branch destinada ao ambiente de produção.

Somente alterações que passaram pela homologação na branch stage são promovidas para a main.

## Módulo de Controle da Qualidade da Água

O módulo `ControleQualidadeAgua.java` realiza o monitoramento de:

- Nível de pH;
- Temperatura da água.

Os parâmetros considerados ideais são:

- pH entre 6.8 e 7.6;
- Temperatura entre 22.0°C e 28.0°C.

Caso algum parâmetro esteja fora dos limites, o sistema apresenta um alerta de qualidade.

## Biólogos/Desenvolvedores Responsáveis

- Cauã Parreiras Vieira — Desenvolvedor responsável pelo projeto.

## Branches

```text
main
 └── stage
      └── develop
           └── feature/controle-qualidade
