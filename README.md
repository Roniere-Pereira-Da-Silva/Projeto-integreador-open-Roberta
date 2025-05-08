# Projeto Integrador Open Roberta - 1º Trimestre


# PRIMEIRO "DESAFIO"

![1](https://github.com/user-attachments/assets/f1e9d160-c485-4739-a57a-6171d00f5152)


Programe seu robô para completar uma missão especial, que se desenvolve em um circuito com desafios a superar. Entre eles, você terá que buscar padrões de cores, detectar obstáculos e desviar deles para chegar à linha de chegada.

- Antes de começar:

- Baixe o mundo (aqui) para o seu computador e depois carregue-o no Open Roberta usando a opção apropriada.

- Arraste o Quadro Azul (objeto) que aparece no canto inferior direito do mundo e coloque-o dentro do cubo.

- Coloque seu robô sobre as letras INÍCIO do mundo.

Confirme em Configuração do Robô que o sensor 3 = “sensor de cor” e o sensor 4 = “sensor de ultrassom”.

- O robô é colocado manualmente sobre a palavra INÍCIO.

- O roO robô é colocado manualmente sobre a palavra INÍCIO.

- O robô deve avançar de forma ilimitada até detectar a cor vermelha, momento em que deverá parar.

- Espera 1 segundo.

- Agora, o robô avança até detectar, com seu sensor ultrassônico, um objeto à sua frente. Ele deve parar a 10 cm do objeto.

- Deve desviar do objeto utilizando apenas os blocos girar e avançar.

- Após desviar do objeto, o robô continua avançando e, antes de bater na parede do cenário, deve girar 90 graus para se posicionar na direção da linha amarela.

- Agora o robô avançará até detectar a linha amarela e deverá parar.

- Esperar 1 segundo.

- deve avançar de forma ilimitada até detectar a cor vermelha, momento em que deverá parar.

- Espera 1 segundo.

- Agora, o robô avança até detectar, com seu sensor ultrassônico, um objeto à sua frente. Ele deve parar a 10 cm do objeto.

- Deve desviar do objeto utilizando apenas os blocos girar e avançar.

- Após desviar do objeto, o robô continua avançando e, antes de bater na parede do cenário, deve girar 90 graus para se posicionar na direção da linha amarela.

- Agora o robô avançará até detectar a linha amarela e deverá parar.

- Esperar 1 segundo.

- O robô avança novamente e, antes de bater na parede, gira 90 graus na direção da linha azul.

- Agora o robô avança de forma ilimitada e, quando detectar a linha azul, ele para.

- Espera 1 segundo.

- Avança até chegar à palavra FIM, onde encerrará seu percurso.

# Projeto 2 Labirinto
![3](https://github.com/user-attachments/assets/e46d7f6e-c4fd-46db-adea-7a9c18afb8d6)

INÍCIO
    Posicionar o robô manualmente sobre a palavra INÍCIO

    // Etapa 1: Avançar até detectar cor vermelha
    ENQUANTO sensor_cor ≠ VERMELHO FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR
    ESPERAR 1 segundo

    // Etapa 2: Avançar até ficar a 10 cm do obstáculo
    ENQUANTO sensor_ultrassonico > 10 FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR

    // Etapa 3: Desviar do obstáculo
    GIRAR_ESQUERDA (90 graus)
    AVANÇAR
    GIRAR_DIREITA (90 graus)
    AVANÇAR

    // Etapa 4: Antes de bater na parede, girar 90° em direção à linha amarela
    ENQUANTO sensor_ultrassonico > 10 FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR
    GIRAR (90 graus na direção da linha amarela)

    // Etapa 5: Avançar até detectar linha amarela
    ENQUANTO sensor_cor ≠ AMARELO FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR
    ESPERAR 1 segundo

    // Etapa 6: Avançar e girar em direção à linha azul
    ENQUANTO sensor_ultrassonico > 10 FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR
    GIRAR (90 graus na direção da linha azul)

    // Etapa 7: Avançar até detectar linha azul
    ENQUANTO sensor_cor ≠ AZUL FAÇA
        AVANÇAR
    FIM_ENQUANTO
    PARAR
    ESPERAR 1 segundo

    // Etapa 8: Avançar até a palavra FIM
    AVANÇAR por tempo/destino até alcançar palavra FIM
    PARAR

FIM

# Projeto 3 Sumo
![4](https://github.com/user-attachments/assets/6784f782-9491-4b6f-ad5d-9f80b56ae677)

## 🧠 Algoritmo básico para o funcionamento de um sumôbot
O robô deve iniciar a partida aguardando por 5 segundos.

Em seguida, ele deve começar a procurar o adversário, movimentando seus motores para frente ou girando.

Assim que o sensor de presença (pode ser um sensor ultrassônico, infravermelho ou similar) identificar o oponente, o robô deve ativar seus motores e avançar para empurrá-lo.

Se o robô seguir em linha reta e não encontrar o adversário, o sensor de cor vai detectar a faixa branca no chão — indicando o limite da arena — e, nesse caso, o robô deve recuar para não sair do dojo.

Esse processo deve se repetir até que o oponente seja retirado completamente da arena.

## ⚙️ Componentes usados para programar o sumôbot:
- 1 sensor de distância (ultrassônico)

- 2 motores (um para cada roda)

- 1 sensor de cor




## 📋 Descrição do Projeto
Projeto simples focado em lógica e gestão de dados, utilizando componentes modulares. **Não envolve HTML, CSS ou JavaScript**.  
Funcionalidades principais:  
- Processamento de dados e geração de logs.  
- Pré-avaliação de layouts (apenas lógica, sem implementação visual).  
- Integração entre módulos de estrutura, lógica e dados.

---

## 🧩 Componentes Principais

### 1. Módulo ESTRUTURA (5 unidades)
- Define a organização base do sistema.  
- Exemplo: Como os dados são armazenados ou categorizados.

### 2. Módulo LÓGICA (9 unidades)
- Responsável por regras de processamento e cálculos.  
- Exemplo: Validação de dados ou geração de relatórios.

### 3. Módulo DADOS (8 unidades)
- Gerencia fluxos de informações e logs.  
- Exemplo: Armazenamento temporário de entradas/saídas.

### 4. Módulo PRÉ-AVALIAÇÃO (7 unidades)
- Simula ajustes de layout antes da implementação.  
- Exemplo: Verificação de compatibilidade entre componentes.

---

## 📌 Regras Básicas
1. **Simplicidade**:  
   - Nenhum código complexo (como HTML/CSS/JS) é necessário.  
   - Foco em diagramas ou fluxos descritivos (ex: imagens 1.png a 4.png).

2. **Componentes**:  
   - Cada módulo (ESTRUTURA, LÓGICA, DADOS, PRÉ-AVALIAÇÃO) deve ser documentado separadamente.  
   - Use números de versão conforme as imagens (ex: "5" para ESTRUTURA).

3. **Integração**:  
   - A "pressão de layout" (mencionada em 4.png) refere-se à validação de compatibilidade entre módulos.  
   - Logs devem ser gerados em formato simples (ex: `.txt`).

---

## 🚀 Como Participar
1. **Documentação**:  
   - Descreva cada módulo seguindo os exemplos das imagens.  
   - Exemplo para o módulo LÓGICA:  
     ```plaintext
     # LÓGICA  
     9  
     Processamento de regras  
     Geração de relatórios
     ```

2. **Testes**:  
   - Verifique se os números de unidades (ex: 5, 9, 8) estão consistentes entre os módulos.  
   - Valide a comunicação entre DADOS e PRÉ-AVALIAÇÃO.

---

## 📄 Licença
Este projeto é para fins educacionais. Sinta-se à vontade para adaptá-lo conforme suas necessidades.
