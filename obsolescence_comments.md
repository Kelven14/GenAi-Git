# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12 e deve ser substituído por 'setuptools'.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 12)
- **Obsolescência detectada:** A função 'print' continua funcionando, mas a forma de usar aspas duplas para strings é recomendada para melhor legibilidade e compatibilidade com diferentes versões do Python.
- **Código atual:** print("Pacote configurado com sucesso!")
- **Sugestão:** print("Pacote configurado com sucesso!")


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' não reconhece a estrutura de pacotes de forma completa. Utilize 'setuptools' para corrigir.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  py_modules=['meu_modulo.__init__']

