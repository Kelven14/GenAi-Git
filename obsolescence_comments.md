# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** Para pacotes em subdiretórios, é necessário usar 'package_dir' para especificar a localização correta do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** Para encontrar automaticamente todos os pacotes, use 'find_packages()' em vez de listar os pacotes manualmente.
- **Código atual:** packages=['meu_modulo'],
- **Sugestão:** packages=find_packages(),

