# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O argumento 'packages' em 'setup' exige a especificação do diretório do pacote para evitar conflitos de nomes.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** Para pacotes complexos, é recomendado usar 'find_packages()' para detectar pacotes automaticamente e especificar dependências com 'install_requires'.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        packages=find_packages(),
        install_requires=[
            # adicione suas dependências aqui
        ]
    )

