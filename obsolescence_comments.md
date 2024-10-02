# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para a criação de pacotes.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 10)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para a criação de pacotes.
- **Código atual:** description='Um exemplo de pacote usando distutils'
- **Sugestão:** description='Um exemplo de pacote usando setuptools'


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 10)
- **Obsolescência detectada:** A partir do Python 3.12, o argumento 'packages' do setup não é mais usado. O argumento 'package_dir' deve ser usado para especificar o diretório raiz do pacote.
- **Código atual:** packages=['meu_modulo']
- **Sugestão:** packages=['meu_modulo'],  package_dir={'': 'meu_modulo'}

