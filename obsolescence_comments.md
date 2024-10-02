# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** 'distutils' module is deprecated in Python 3.12, use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** 'packages' parameter in 'setup' function requires 'package_dir' for correct package structure in Python 3.12.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' para gerenciar pacotes.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** O uso de 'packages=['meu_modulo']' é desaconselhado. Utilize 'packages=find_packages()' para encontrar pacotes automaticamente.
- **Código atual:**         packages=['meu_modulo'],
- **Sugestão:**         packages=find_packages(),

