# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto no Python 3.12. Utilize 'setuptools' como alternativa.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 5)
- **Obsolescência detectada:** A sintaxe de chamada para a função setup() está obsoleta. Utilize a sintaxe de dicionário para definir os parâmetros.
- **Codigo atual:**     setup(
- **Sugestão:**     setup(
        name='meu_pacote',
        version='0.1dev',
        packages=['meu_modulo'],
        description='Um exemplo de pacote usando setuptools',
        author='Seu Nome',
        author_email='seu.email@example.com',
        url='http://exemplo.com',
    )


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' em seu lugar.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 4)
- **Obsolescência detectada:** O módulo 'distutils.core' não possui suporte para a especificação de requisitos de versão do Python. Utilize 'python_requires' no módulo 'setuptools' para especificar a versão mínima do Python necessária.
- **Codigo atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        

