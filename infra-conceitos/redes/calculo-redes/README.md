# Cálculo de Máscara de Redes

## Introdução
Neste documento, você encontrará informações detalhadas sobre como calcular máscaras de redes IP. O cálculo da máscara de rede é essencial para segmentar e designar endereços IP em redes de computadores.

## O que é uma Máscara de Rede?
Uma máscara de rede é um conjunto de bits que define quais partes de um endereço IP representam a parte da rede e quais representam a parte do host.

## Como Calcular uma Máscara de Rede
Para calcular uma máscara de rede, você precisa determinar o número de bits que serão usados para representar a parte da rede e a parte do host. Isso é feito convertendo a máscara de rede de notação decimal com pontos (por exemplo, 255.255.255.0) para notação de barra (/24).

### Exemplo:
Se tivermos um endereço IP 192.168.1.0 com uma máscara de 255.255.255.0, podemos calcular a máscara de rede da seguinte maneira:

1. Converter a máscara de 255.255.255.0 para notação de barra: 255.255.255.0 = /24.
2. Para calcular o número de hosts possíveis, subtraia o número de bits da máscara de 32 (tamanho de um endereço IP IPv4).

Portanto, para o exemplo acima:
- Número de bits da máscara de rede: 24
- Número de bits para hosts: 32 - 24 = 8
- Número de hosts possíveis: 2^8 - 2 (dois endereços reservados) = 254 hosts

## Conclusão
O cálculo de máscaras de rede é fundamental para a configuração correta de redes de computadores. Compreender como calcular e aplicar máscaras de rede é essencial para segmentar efetivamente uma rede e garantir sua funcionalidade e segurança.

Espero que este guia tenha sido útil para entender o cálculo de máscaras de redes.
