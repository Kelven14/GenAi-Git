# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e 'setuptools' é a biblioteca recomendada para a criação de pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 4)
- **Obsolescência detectada:** O uso de 'packages' e 'include_package_data' é recomendado para garantir a inclusão de todos os arquivos necessários no pacote.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        packages=find_packages(),
        include_package_data=True,
    )


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. Para usar o módulo 'setuptools', importe-o com 'from setuptools import setup'.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** O argumento 'packages' deve estar presente no dicionário de configuração. Além disso, adicione 'install_requires=['setuptools']' para garantir que o 'setuptools' seja instalado como dependência.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['setuptools']

