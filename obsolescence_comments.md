# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' não suporta a instalação de dependências. Use 'setuptools' para instalar pacotes externos.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['setuptools']


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 12)
- **Obsolescência detectada:** A função 'print' não é mais considerada uma função de primeira classe em Python 3.12. Utilize a função 'print()' com parâmetros entre parênteses.
- **Código atual:**     print("Pacote configurado com sucesso!")
- **Sugestão:**     print("Pacote configurado com sucesso!")

