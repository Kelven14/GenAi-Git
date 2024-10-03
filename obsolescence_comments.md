# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12 e deve ser substituído por 'setuptools'
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 8)
- **Obsolescência detectada:** A partir do Python 3.12, o atributo 'packages' requer o atributo 'package_dir' para indicar a localização dos pacotes.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** O atributo 'packages' pode ser ambíguo quando você define um diretório de pacotes. Adicione o atributo 'package_dir' para garantir que o caminho do pacote seja definido corretamente.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],
    package_dir={'': 'meu_modulo'}

