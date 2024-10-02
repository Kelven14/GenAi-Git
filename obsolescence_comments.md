# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' como alternativa.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 6)
- **Obsolescência detectada:** Para garantir compatibilidade com Python 3.6 e versões posteriores, especifique 'python_requires' no setup.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 5)
- **Obsolescência detectada:** O módulo 'distutils.core' não suporta Python 3.6 ou superior. Adicione 'python_requires' para garantir compatibilidade.
- **Código atual:**     setup(
- **Sugestão:**     setup( 
        python_requires='>=3.6',

