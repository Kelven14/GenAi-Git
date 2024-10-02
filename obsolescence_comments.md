# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** 'distutils' is deprecated and will be removed in Python 3.12. Use 'setuptools' instead.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 5)
- **Obsolescência detectada:** In Python 3.12, 'distutils' no longer automatically creates packages for modules in subdirectories. You need to specify the package directory explicitly.
- **Código atual:**     setup(
- **Sugestão:**     setup(packages=['meu_modulo'],
        package_dir={'': 'meu_modulo'},
        ...


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 5)
- **Obsolescência detectada:** Para garantir compatibilidade com Python 3.6 e superior, é recomendado definir o requisito mínimo da versão do Python usando 'python_requires'.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        

