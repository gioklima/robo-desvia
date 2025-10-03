# 🤖 Robô Desviador de Obstáculos com Chaves Fim de Curso

## 📌 Descrição
Este projeto consiste em um robô móvel simples capaz de **detectar obstáculos** e **mudar sua direção** utilizando **sensores do tipo chave fim de curso**.  
Quando uma das chaves é acionada ao tocar em um objeto, o robô altera o movimento do motor correspondente, fazendo uma manobra de desvio.

## ⚙️ Componentes Utilizados
- 1x Chassi com rodas e suporte para motores
- 2x Motores DC com caixa de redução
- 2x Chaves fim de curso (limit switch)
- 1x Ponte H (L298N ou equivalente)
- 1x Suporte de pilhas (4x AA ou 9V, conforme projeto)
- Fios de conexão
- Interruptor geral (liga/desliga)

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

## 📷 Demonstração
*(Adicione aqui uma foto ou vídeo do protótipo em funcionamento quando disponível)*

## 👩‍💻 Autores
Projeto desenvolvido por [Giovanna Lima], [Eduardo Dias], [Fernanda Oliveira] e [Gabriel Alves]. Como estudo de eletrônica e robótica básica.

---
✅ Projeto simples e de baixo custo para iniciantes em robótica!
