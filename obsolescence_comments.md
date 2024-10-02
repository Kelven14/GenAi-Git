# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 4)
- **Obsolescência detectada:** O Python 3.12 exige que a versão mínima do Python seja especificada no campo 'python_requires' do setup.py.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        ...


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e foi substituído pelo módulo 'setuptools'.  Use 'setuptools' para criar e gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 5)
- **Obsolescência detectada:** A partir do Python 3.6, o módulo 'setuptools' exige a especificação da versão mínima do Python compatível.  Adicione 'python_requires' para garantir a compatibilidade.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        name='meu_pacote',
        version='0.1dev',
        packages=['meu_modulo'],
        description='Um exemplo de pacote usando distutils',
        author='Seu Nome',
        author_email='seu.email@example.com',
        url='http://exemplo.com',
        python_requires='>=3.6',
    )

