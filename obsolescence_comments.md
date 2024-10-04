# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e deve ser substituído por 'setuptools'. A biblioteca 'setuptools' oferece mais recursos e é a recomendada para a criação de pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e deve ser substituído por 'setuptools'. A biblioteca 'setuptools' oferece mais recursos e é a recomendada para a criação de pacotes Python.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 13)
- **Obsolescência detectada:** A chave 'author_email' agora é uma string simples. A sintaxe com aspas simples não é mais necessária.
- **Código atual:** author_email='seu.email@example.com',
- **Sugestão:** author_email='seu.email@example.com'

