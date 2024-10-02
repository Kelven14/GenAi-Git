# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools' no Python 3.12.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 7)
- **Obsolescência detectada:** A sintaxe 'packages' foi modificada no Python 3.12. A versão atualizada requer 'install_requires' para especificar as dependências do pacote.
- **Codigo atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  install_requires=['meu_modulo']


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto e deve ser substituído por 'setuptools'. Em Python 3.12, 'distutils.core' foi removido.
- **Codigo atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 8)
- **Obsolescência detectada:** O módulo 'distutils.core' não inclui o atributo 'install_requires'. Para definir dependências, você deve usar 'setuptools' e o atributo 'install_requires'. 
- **Codigo atual:** packages=['meu_modulo'],
- **Sugestão:** packages=['meu_modulo'],
    install_requires=[],

