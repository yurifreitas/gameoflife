# Jogo da Vida - Simulação

Este é um código de simulação do "Jogo da Vida", uma simulação de autômatos celulares em JavaScript.

## Configurações e Parâmetros

### Variáveis Principais

- `maxRadius`: Raio máximo dos átomos.
- `maxClusters`: Número máximo de aglomerados.
- `minClusterSize`: Tamanho mínimo do aglomerado.
- `predefinedColors`: Cores predefinidas para os átomos.

### Configurações Gerais

O objeto `settings` contém várias configurações para a simulação:

- `seed`: Semente para o gerador de números pseudoaleatórios.
- `fps`: Quadros por segundo (FPS) da simulação.
- `atoms`: Configurações dos átomos, incluindo o número de átomos por cor e o raio dos átomos.
- `drawings`: Opções de desenho que afetam o desempenho, como a exibição de linhas entre átomos e o desenho de átomos como círculos.
- `export`: Funções para exportar imagens e vídeos da simulação.
- `explore`: Ativa ou desativa a exploração aleatória.
- `explorePeriod`: Período de exploração aleatória.
- `rules`: Regras da simulação.
- `radii`: Raios dos átomos.
- `colors`: Cores dos átomos.
- `numColors`: Número de cores.
- `time_scale`: Escala de tempo da simulação.
- `viscosity`: Amortecimento de velocidade (pode ser maior que 1).
- `gravity`: Gravidade (força de puxar para baixo).
- `pulseDuration`: Duração do pulso ao clicar.
- `wallRepel`: Repulsão das paredes.
- Funções como `reset`, `randomRules`, `symmetricRules` e `gui` para controle e configuração da simulação.


## Uso

Para executar a simulação, abra o arquivo HTML em um navegador compatível com JavaScript. Use o teclado e o mouse para interagir com a simulação.

## Interface Gráfica do Usuário (GUI)

O código inclui uma GUI interativa para ajustar configurações em tempo real.

## Exportação

Você pode exportar imagens e vídeos da simulação usando as opções fornecidas no código.

## Contribuições

Sinta-se à vontade para contribuir para este projeto ou enviar sugestões de melhorias.

