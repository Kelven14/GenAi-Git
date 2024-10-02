# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e deve ser substituído por 'setuptools'
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 7)
- **Obsolescência detectada:** O argumento 'packages' em 'setup()' precisa de um mapeamento para o diretório do pacote para funcionar corretamente com 'setuptools'.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 11)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'

