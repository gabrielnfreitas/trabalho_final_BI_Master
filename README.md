# Modelo Integrado Petrofísico-Composicional (PCIM)

#### Aluno: [Gabriel Freitas](https://github.com/gabrielnfreitas)
#### Orientador: [Felipe Borges](https://github.com/FelipeBorgesC)

---

Trabalho apresentado ao curso [BI MASTER](https://ica.puc-rio.ai/bi-master) como pré-requisito para conclusão de curso e obtenção de crédito na disciplina "Projetos de Sistemas Inteligentes de Apoio à Decisão".

---

### Resumo

<!-- trocar o texto abaixo pelo resumo do trabalho, em português -->

Lorem ipsum dolor 

### 1. Introdução

A petrofísica é o ramo de estudo das propriedades físicas e químicas das rochas e dos fluidos nelas contidos, segundo a definição presente na PetroWiki. A petrofísica desempenha um papel fundamental na indústria do petróleo, fornecendo informações valiosas sobre propriedades dos diversos tipos de rochas (reservatório, selantes, geradoras, etc). É uma disciplina que combina conhecimentos de geologia, física e engenharia para analisar e interpretar dados obtidos de amostras de rochas e fluidos. Através da petrofísica, é possível determinar propriedades como porosidade, permeabilidade, saturação de fluidos e resistividade elétrica das rochas, o que é essencial para a identificação e avaliação de reservatórios de óleo e gás. Essas informações são cruciais para o planejamento e execução de atividades de exploração, produção e desenvolvimento de campos petrolíferos.

Além de dados laboratoriais de rocha e de fluido, o principal insumo da petrofísica na avaliação de poços são os chamados "perfis de poços" (ou ainda perfis elétricos ou geofísicos). Tratam-se de registros contínuos de propriedades físicas das rochas ao longo de um poço, como resistividade elétrica, porosidade, densidade, velocidade das ondas sísmicas, entre outras, feitas através de ferramentas específicas que são corridas no poço durante ou após a perfuração. Cada ferramenta de perfilagem adquire diversas medidas que são processadas e utilizadas de acordo com a necessidade.

Combinando-se os dados experimentais de rocha e fluido com os perfis de poços, é possível construir os chamados "modelos petrofísicos". Tais modelos permitem o cálculo das propriedades petrofísicas das rochas honrando, segundo ponderações definidas pelo intérprete, o conjunto de dados fornecido. O cálculo dessas propriedades em escala de poço sempre apresenta algum tipo de aproximação ou incerteza, devido a fatores como:

1. Incertezas nas medidas e no processamento de dados dos perfis
2. Diferenças de resolução vertical e profundidade de investigação dos perfis
3. Diferenças de escala entre amostras de rocha/fluido e volume lido pelos perfis
4. Limitação da quantidade de parâmetros que podem ser medidos em relação ao conjunto total de parâmetros que determinam as propriedades

O problema tratado nesse trabalho diz respeito à identificação e a caracterização da matéria orgânica (MO) em intervalos de rochas geradoras de hidrocarbonetos, que é essencial para o entendimento do sistema petrolífero, como subsídio para entender os processos de geração e de acumulação do petróleo. Do ponto de vista experimental, a caracterização do conteúdo orgânico é feito através de ensaios típicos da Geoquímica Orgânica, como a pirólise Rock-Eval. No entanto, a fim de obter estimativas em escala de poço é necessário lançar mão de modelos utilizando perfis.

Nesse sentido, há alguns modelos petrofísicos consagrados, de cunho empírico, para a estimativa do carbono orgânico total (COT), como o chamado ``método de Passey'' ou o ``Carbolog''. Mais recentemente, com o advento das ferramentas de espectroscopia de raios gama induzido por nêutrons, conhecidos como perfis geoquímicos ou ainda perfil litogeoquímico (LGQ), é possível obter estimativas de COT valendo-se da resposta do carbono no espectro inelástico. No entanto, há poucos trabalhos na literatura que se proponham a estimar diretamente alguma propriedade que indique o tipo de querogênio, potencial de geração de óleo (S2) e/ou o índice de hidrogênio (IH).

O presente trabalho, tem como objetivo implementar computacionalmente uma metodologia recentemente desenvolvida pelo autor para a estimativa de S2 (potencial de óleo) em escala de poço a partir de perfis elétricos, dentre eles a medida de H e Cl oriundas do perfil litogeoquímico. A combinação da curva de S2 obtida com a curva correspondente de COT obtidos de forma independente, por outros métodos, fornece a curva de IH. 

### 2. Modelagem

O modelo petrofísico se traduz matematicamente em um conjunto de equações, algumas lineares e outras não-lineares, que envolvem variáveis de entrada (sejam perfis medidos ou parâmetros determinados a partir de ensaios experimentais) e variáveis de saída que se quer determinar. Esse conjunto de equações é resolvido para cada passo de profundidade do poço, visto que as medidas dos perfis variam com a profundidade.

Após diversos testes e tentativas, optou-se por uma implementação que segue a seguinte filosofia:

### 3. Resultados

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

### 4. Conclusões

Lorem ipsum dolor sit amet, consectetur adipiscing elit. Proin pulvinar nisl vestibulum tortor fringilla, eget imperdiet neque condimentum. Proin vitae augue in nulla vehicula porttitor sit amet quis sapien. Nam rutrum mollis ligula, et semper justo maximus accumsan. Integer scelerisque egestas arcu, ac laoreet odio aliquet at. Sed sed bibendum dolor. Vestibulum commodo sodales erat, ut placerat nulla vulputate eu. In hac habitasse platea dictumst. Cras interdum bibendum sapien a vehicula.

Proin feugiat nulla sem. Phasellus consequat tellus a ex aliquet, quis convallis turpis blandit. Quisque auctor condimentum justo vitae pulvinar. Donec in dictum purus. Vivamus vitae aliquam ligula, at suscipit ipsum. Quisque in dolor auctor tortor facilisis maximus. Donec dapibus leo sed tincidunt aliquam.

---

Matrícula: 211.100.426

Pontifícia Universidade Católica do Rio de Janeiro

Curso de Pós Graduação *Business Intelligence Master*
