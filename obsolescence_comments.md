# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor do 'setuptools'. Para garantir a compatibilidade com versões mais recentes do Python, utilize 'setuptools' para gerenciar pacotes.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 6)
- **Obsolescência detectada:** O formato '0.1dev' para a versão do pacote é considerado obsoleto. Utilize o formato '0.1.0' para seguir as convenções de versionamento de pacotes Python.
- **Codigo atual:**         version='0.1dev'
- **Sugestão:**         version='0.1.0'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para criar pacotes.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** A convenção de versionamento de pacotes Python recomenda o uso de três partes separadas por pontos (major.minor.patch). A versão '0.1dev' é considerada uma versão de desenvolvimento e pode ser interpretada de forma ambígua.
- **Codigo atual:**         version='0.1dev'
- **Sugestão:**         version='0.1.dev'

