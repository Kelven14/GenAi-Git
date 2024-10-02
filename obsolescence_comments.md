# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. A partir do Python 3.12, 'distutils' foi removido. Utilize 'setuptools' para gerenciar seus pacotes.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 5)
- **Obsolescência detectada:** O Python 3.12 exige a especificação de um requisito de versão Python para o pacote. Utilize 'python_requires' para garantir a compatibilidade com as versões Python suportadas.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        ...

