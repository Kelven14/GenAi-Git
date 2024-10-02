# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. O módulo 'setuptools' fornece recursos aprimorados e é a opção recomendada para a criação de pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 11)
- **Obsolescência detectada:** A descrição do pacote deve ser atualizada para refletir o uso do 'setuptools'.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** 'distutils' module is deprecated. Use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** The 'packages' argument in setup() requires a 'package_dir' argument to be set when using nested packages.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  package_dir={'': 'meu_modulo'}

