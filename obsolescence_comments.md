# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** 'distutils' is deprecated in Python 3.12, use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** 'distutils' does not support nested packages, use 'setuptools' instead.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** 'distutils' is deprecated, use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 13)
- **Obsolescência detectada:** Use English in code for better collaboration and understanding.
- **Código atual:** print("Pacote configurado com sucesso!")
- **Sugestão:** print("Package configured successfully!")

