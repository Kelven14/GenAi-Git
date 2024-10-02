# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado e o 'setuptools' é recomendado para a criação de pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** A partir do Python 3.12, o atributo 'packages' do 'setup' precisa ser usado em conjunto com 'package_dir' para especificar corretamente a estrutura do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}

