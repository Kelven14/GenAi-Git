# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 6)
- **Obsolescência detectada:** O argumento 'name' é recomendado para ser usado em 'setup()' para maior clareza.
- **Código atual:**         name='meu_pacote',
- **Sugestão:**         name='meu_pacote',


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 8)
- **Obsolescência detectada:** A chave 'packages' precisa ter um valor de lista e um separador de vírgula no final.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],

