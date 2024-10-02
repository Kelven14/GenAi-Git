# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** Para definir o diretório base do pacote, use 'package_dir' em vez de 'packages'. Isso evita conflito com o caminho do módulo.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 11)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'

