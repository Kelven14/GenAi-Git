# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em seu lugar.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** O uso de 'packages' com uma lista de pacotes é obsoleto. Use 'find_packages()' para encontrar automaticamente os pacotes.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=find_packages()

