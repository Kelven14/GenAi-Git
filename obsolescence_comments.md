# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O atributo 'packages' é usado para especificar os pacotes do projeto, mas 'install_requires' é usado para especificar as dependências do projeto, como 'meu_modulo'. O atributo 'packages' não é mais usado na versão 3.12 e deve ser substituído por 'install_requires'.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['meu_modulo']


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 11)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'

