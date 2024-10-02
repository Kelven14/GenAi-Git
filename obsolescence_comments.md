# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Para instalar o 'setuptools', execute 'pip install setuptools' no seu terminal.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Para instalar o 'setuptools', execute 'pip install setuptools' no seu terminal.
- **Código atual:**         description='Um exemplo de pacote usando distutils'
- **Sugestão:**         description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em Python 3.10. Use 'setuptools' para gerenciar pacotes.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 4)
- **Obsolescência detectada:** A especificação de requisitos de Python para o pacote é recomendada para garantir compatibilidade.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        

