# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Para usar o 'setup', importe-o de 'setuptools'.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O código usa 'distutils' na descrição, mas 'setuptools' é o módulo recomendado para criação de pacotes.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em seu lugar.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 12)
- **Obsolescência detectada:** A sintaxe de string f-string é recomendada para strings literais.  Use f'seu.email@example.com' em vez de 'seu.email@example.com'.
- **Código atual:** author_email='seu.email@example.com',
- **Sugestão:** author_email='seu.email@example.com'

