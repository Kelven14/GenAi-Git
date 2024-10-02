# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** 'distutils' is deprecated, use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 7)
- **Obsolescência detectada:** Add 'install_requires' to your setup function to specify project dependencies.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['your_dependencies']


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** A sintaxe para definir pacotes em 'setup' mudou. Use 'packages=['meu_modulo'],'
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],

