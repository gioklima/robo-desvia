# 🤖 Robô Desviador de Obstáculos com Chaves Fim de Curso

## 📌 Descrição
Este projeto consiste em um robô móvel simples capaz de **detectar obstáculos** e **mudar sua direção** utilizando **sensores do tipo chave fim de curso**.  
Quando uma das chaves é acionada ao tocar em um objeto, o robô altera o movimento do motor correspondente, fazendo uma manobra de desvio.

## ⚙️ Componentes Utilizados
- 1x Chassi 
- 2x Motores com caixa de redução (com rodas)
- 2x Chaves fim de curso 
- 1x Roda castor
- 2x Suporte de pilhas (4x AA)
- Fios de conexão
- Interruptor geral (liga/desliga)
- Fita dupla face

## 🛠️ Funcionamento
1. O robô segue em linha reta enquanto nenhuma chave está acionada.  
2. Ao colidir com um obstáculo do lado esquerdo:
   - A chave esquerda é pressionada.
   - O motor direito continua girando enquanto o motor esquerdo inverte, fazendo o robô virar para a direita.  
3. Ao colidir com um obstáculo do lado direito:
   - A chave direita é pressionada.
   - O motor esquerdo continua girando enquanto o motor direito inverte, fazendo o robô virar para a esquerda.  
4. Após a manobra, o robô volta a seguir em frente.


## 🚀 Possíveis Melhorias  
- Implementar microcontrolador (Arduino, ESP32, etc.) para lógicas mais complexas.  
- Adicionar LEDs indicadores de direção.  
- Melhorar a estrutura mecânica.


## 👩‍💻 Autores
Projeto desenvolvido por Giovanna Lima, Fernanda Oliveira, Eduardo Dias e Gabriel Alves. Como estudo de eletrônica e robótica básica.

---
✅ Projeto simples e de baixo custo para iniciantes em robótica!
