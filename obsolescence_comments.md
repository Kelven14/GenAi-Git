# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** A sintaxe de 'packages' mudou para uma lista. O código atual cria um erro de sintaxe. A correção adiciona uma vírgula após a lista de pacotes.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 12)
- **Obsolescência detectada:** O módulo 'distutils' está obsoleto e foi substituído por 'setuptools'. Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'

