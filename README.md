# Simulador de Redes de Petri

O software RdP é uma ferramenta educacional de simulação de Redes de Petri para apoiar as aulas de Sistemas a Eventos Discretos (SED). 

O objetivo principal é permitir que você modele, simule e valide o comportamento dinâmico de Redes de Petri de maneira visual e prática, consolidando os conceitos teóricos vistos em sala de aula.

---

## Funcionalidades

* **Modelagem de Sistemas:** Permite estruturar graficamente ou via matrizes os elementos fundamentais da rede: Lugares (P), Transições (T) e Arcos.
* **Simulação Dinâmica:** Você pode definir uma marcação inicial (distribuição de fichas/tokens) e simular o disparo de transições passo a passo para observar a evolução dos estados.
* **Análise Estrutural:** O simulador possui um motor matemático interno capaz de calcular automaticamente a Matriz de Incidência e extrair os P-Invariantes Mínimos Não-Negativos (Invariantes de Lugar) reduzidos pelo Máximo Divisor Comum (MDC).
* **Mapeamento para CLP (Futuras versões):** Utilizado para projetar a lógica de controle de Redes de Petri Interpretadas e entender como transpor os módulos de *Inicialização*, *Jogador* e *Ações/Saídas* diretamente para a linguagem Ladder utilizada em Controladores Lógicos Programáveis.

---

## Como usar

1. Baixe o arquivo executável disponível na seção de [Releases] do projeto.
2. O programa é portable (não necessita de instalação), basta dar um duplo clique no `.exe` para iniciar.
3. Desenhe a sua rede utilizando a interface de botões de criação de lugares, transições e arcos para começar as simulações e análises.

---

## Uso Acadêmico

Este simulador foi desenvolvido pelo **Prof. Eduardo José Lima II** (ejlima2@gmail.com) da Universidade Federal de Minas Gerais para uso exclusivo em atividades acadêmicas, sendo outras instituições também convidadas a utilizar o programa, sendo solicitado o envio de um e-mail para conhecermos o alcance do software.
