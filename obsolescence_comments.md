# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** 'distutils' is deprecated, use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 11)
- **Obsolescência detectada:** 'distutils' is deprecated, use 'setuptools' instead.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** A opção 'packages' em 'setup' exige que o diretório do pacote seja definido para funcionar corretamente.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  package_dir={'': 'meu_modulo'}

