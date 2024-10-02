# Comentários sobre Obsolescências

### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' em vez de 'distutils' para gerenciamento de pacotes em Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 9)
- **Obsolescência detectada:** O atributo 'packages' em 'setup' não inclui automaticamente as dependências do pacote. Utilize o atributo 'install_requires' para declarar as dependências do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['meu_modulo']

