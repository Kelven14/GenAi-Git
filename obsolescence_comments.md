# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** A partir do Python 3.12, 'packages' não é mais suportado. Use 'package_dir' para especificar o diretório raiz do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools'. Usar 'setuptools' é recomendado para novos projetos.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 13)
- **Obsolescência detectada:** A função 'print' não inclui uma quebra de linha por padrão no Python 3.12. É recomendável adicionar um '\n' para melhor legibilidade.
- **Código atual:** print("Pacote configurado com sucesso!")
- **Sugestão:** print("Pacote configurado com sucesso!\n")

