# Tapioca e a Chuva de Trufas
Neste projeto resolvo um problema computacional do site https://www.urionlinejudge.com.br/

O link do problema é [https://www.urionlinejudge.com.br/judge/pt/problems/view/1927](https://www.urionlinejudge.com.br/judge/pt/problems/view/1927).

# Descrição do problema
Tapioca sonhou que estava chovendo trufas na cidade onde ele mora, Lagoa de Roça (Lá já choveu granizo, mas isso é papo pra outro problema). Trufas de todos os sabores, pena que ele não pode comer todas, porque as que caem no chão se espatifam completamente. Mas ele pode tentar comer a maior quantidade possível, basta pegá-las antes que elas caiam no chão. Felizmente, nesse sonho Tapioca é capaz de prever o futuro e é por isso que ele sabe o instante e a posição em que cada uma das trufas irá cair. No entanto ele não tem o poder de fazer duas coisas ao mesmo tempo e é por isso que sua ajuda é necessária. Escreva um programa que com as premonições de Tapioca, informe a quantidade máxima de trufas que ele pode comer.

Considere Lagoa de Roça como sendo um plano e que Tapioca se encontra no instante 0 na posição (6, 6). Além disso ele só pode se mover para posições ortogonais, ou seja, Norte, Sul, Leste e Oeste. Para se movimentar ele leva 1 segundo. E ele só é capaz de pegar uma trufa se estiver na mesma posição e no momento em que ela irá cair.

## Entrada
A primeira linha de entrada contém um inteiro 1 ≤ n ≤ 2000, que representa a quantidade de trufas que irão cair do céu. Cada um das próximas n linhas irá conter três inteiros, 0 ≤ xi, yi ≤ 20 e 0 ≤ ti ≤ 1000, representando as coordenadas do local da queda e o momento da queda da trufa i.

## Saída
Imprima a quantidade máxima de trufas que Tapioca é capaz de comer.
