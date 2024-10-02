# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em favor de 'setuptools' no Python 3.12.  'setuptools' oferece recursos mais avançados e é amplamente utilizado para a criação de pacotes Python.
- **Sugestão:** from setuptools import setup


### main.py (Linha 6)
- **Obsolescência detectada:** A opção 'packages' no setup() do distutils precisa ser complementada com a opção 'package_dir' para garantir o funcionamento correto em Python 3.12. A opção 'package_dir' especifica o diretório raiz do pacote.
- **Sugestão:** packages=['meu_modulo'], package_dir={'': 'meu_modulo'}


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para gerenciar pacotes.
- **Sugestão:** from setuptools import setup


### teste.py (Linha 7)
- **Obsolescência detectada:** O argumento 'packages' em 'setup' não define o diretório do pacote. Para evitar erros, defina o diretório do pacote com 'package_dir' em Python 3.12.
- **Sugestão:** packages=['meu_modulo'],
    package_dir={'': 'meu_modulo'},

