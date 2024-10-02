# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto no Python 3.12. Use 'setuptools' em vez disso.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 5)
- **Obsolescência detectada:** O Python 3.12 exige a especificação de requisitos de versão do Python para pacotes. Use 'python_requires' para definir a versão mínima do Python suportada.
- **Codigo atual:**     setup(
- **Sugestão:**     setup( 
        python_requires='>=3.7', 
        


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' para a criação de pacotes.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 6)
- **Obsolescência detectada:** O parâmetro 'packages' do setup() em distutils não reconhece a estrutura de diretórios por padrão. É necessário definir o parâmetro 'package_dir' para indicar a estrutura de diretórios do pacote.
- **Codigo atual:** packages=['meu_modulo'],
- **Sugestão:** packages=['meu_modulo'],
    package_dir={'': 'meu_modulo'},

