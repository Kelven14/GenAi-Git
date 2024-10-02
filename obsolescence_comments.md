# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. Em Python 3.12, 'distutils' é considerado obsoleto e pode ser removido em versões futuras.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils' foi depreciado em favor de 'setuptools'. Em Python 3.12, 'distutils' é considerado obsoleto e pode ser removido em versões futuras.
- **Codigo atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para gerenciar pacotes.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** Em Python 3.12, é necessário definir as dependências do pacote usando 'install_requires'. 
- **Codigo atual:** packages=['meu_modulo'],
- **Sugestão:** packages=['meu_modulo'],
    install_requires=[],

