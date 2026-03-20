# Primeira_Aula
Este repositório contém um estudo prático sobre a geração, visualização e manipulação de sinais sonoros utilizando Python. O notebook está organizado de forma a guiar o professor através de experimentos com sinais sintéticos e reais.

📋 Conteúdo do Notebook
Geração de Sinais de Frequência Fixa: Exploração inicial de tons puros (500Hz a 10kHz).
Análise de Chirps (Varreduras de Frequência):
Geração de Chirps Lineares, Quadráticos e Logarítmicos.
Visualização no domínio do tempo e análise da percepção auditiva de cada método de varredura.
Manipulação de Áudio Real (Handel.wav):
Carregamento e plotagem de sinais complexos.
Experimentos com alteração da Taxa de Amostragem (Sampling Rate) e seus efeitos no tom e velocidade da música.
Acústica de Salas e Convolução:
Estudo teórico sobre Resposta Impulsional (RIR).
Processamento de uma RIR real (h_banheiro.wav) e um som de objeto (sinal_taca.wav).
Simulação de Ambiente: Uso da operação de convolução para aplicar a acústica de um banheiro à música de Handel e ao som da taça.
🛠 Tecnologias Utilizadas
NumPy: Manipulação matemática de vetores de sinais.
SciPy: Funções de geração de chirp e operação de convolução.
Librosa: Carregamento e processamento de arquivos de áudio.
Matplotlib: Visualização detalhada das formas de onda.
IPython.display: Reprodução de áudio interativa no notebook.
