# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 11)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para criar pacotes Python.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 13)
- **Obsolescência detectada:** O uso de 'print' sem um argumento 'file' pode causar problemas de compatibilidade com versões futuras do Python.
- **Código atual:** print("Pacote configurado com sucesso!")
- **Sugestão:** print("Pacote configurado com sucesso!", file=sys.stderr)

