# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em Python 3.10 e removido em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** Para o setuptools, a definição de 'packages' requer a especificação do diretório raiz dos pacotes. O diretório raiz é 'meu_modulo' neste caso, mas o setuptools exige que 'meu_modulo' seja um diretório em relação ao diretório raiz. O código atual não define o diretório raiz, levando a um erro. Esta correção define o diretório raiz como o diretório atual.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 11)
- **Obsolescência detectada:** O módulo 'distutils.core' não suporta corretamente a organização de pacotes. Use 'setuptools' para garantir a organização correta dos pacotes.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}

