# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado. Use 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 12)
- **Obsolescência detectada:** Esta linha de código não está diretamente relacionada à obsolescência do 'distutils.core', mas é uma prática recomendada usar a função 'print' com parâmetros de string formatados. Por exemplo: print(f"Pacote configurado com sucesso!")
- **Código atual:** print("Pacote configurado com sucesso!")
- **Sugestão:** print("Pacote configurado com sucesso!")


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído por 'setuptools'. Para instalar o 'setuptools', use 'pip install setuptools'.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** Para encontrar todos os pacotes em seu projeto, é recomendado usar 'find_packages()' do 'setuptools' em vez de listar os pacotes manualmente.
- **Código atual:**         packages=['meu_modulo'],
- **Sugestão:**         packages=find_packages(),

