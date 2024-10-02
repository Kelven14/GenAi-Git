# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** A opção 'packages' agora é desabilitada por padrão. Use 'install_requires' para especificar as dependências do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['meu_modulo']


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. Para usar o módulo 'setup', importe-o de 'setuptools'
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 4)
- **Obsolescência detectada:** O módulo 'distutils' está obsoleto e não oferece suporte a recursos modernos, como 'python_requires'. Use 'setuptools' para garantir a compatibilidade com as versões mais recentes do Python
- **Código atual:**     setup(
- **Sugestão:**     setup(
        # ... outras opções de configuração ...
        python_requires='>=3.6', # Adicione esta linha para garantir compatibilidade com Python 3.6 ou superior
    )

