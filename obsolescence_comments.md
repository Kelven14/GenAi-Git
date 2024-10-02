# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** A biblioteca 'distutils' está obsoleta. Use 'setuptools' em seu lugar.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 11)
- **Obsolescência detectada:** A biblioteca 'distutils' está obsoleta. Use 'setuptools' em seu lugar.
- **Codigo atual:** description='Um exemplo de pacote usando distutils',
- **Sugestão:** description='Um exemplo de pacote usando setuptools',


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools' no Python 3.12.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** O atributo 'name' ainda é válido no Python 3.12, mas a documentação do setuptools recomenda o uso de 'package_name' para maior clareza.
- **Codigo atual:**         name='meu_pacote',
- **Sugestão:**         name='meu_pacote',

