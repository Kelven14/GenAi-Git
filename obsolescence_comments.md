# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' em seu lugar.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 6)
- **Obsolescência detectada:** A sintaxe do Python 3.12 exige a presença de uma vírgula após o último argumento nomeado em uma chamada de função. A linha atual está faltando a vírgula após 'name='meu_pacote''.
- **Codigo atual:** name='meu_pacote'
- **Sugestão:** name='meu_pacote',


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para configurar pacotes.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** A sintaxe do argumento 'name' está incompleta. A vírgula é necessária para separá-lo dos outros argumentos.
- **Codigo atual:** name='meu_pacote'
- **Sugestão:** name='meu_pacote',

