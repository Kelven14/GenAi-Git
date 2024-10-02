# Comentários sobre Obsolescências

### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para criar pacotes Python.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** A instalação de pacotes deve ser declarada explicitamente utilizando 'install_requires' no setup.
- **Codigo atual:** packages=['meu_modulo'],
- **Sugestão:** packages=['meu_modulo'],
    install_requires=['meu_pacote'],

