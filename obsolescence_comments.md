# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto. Utilize 'setuptools' para gerenciar pacotes Python.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### main.py (Linha 5)
- **Obsolescência detectada:** A partir do Python 3.6, é recomendado definir a versão mínima do Python necessária para o pacote. Isso garante a compatibilidade e evita erros de execução em versões anteriores.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        


### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto em Python 3.12. Use 'setuptools' em vez disso.
- **Código atual:** from distutils.core import setup
- **Sugestão:** from setuptools import setup


### teste.py (Linha 5)
- **Obsolescência detectada:** O parâmetro 'python_requires' é recomendado para especificar a versão mínima do Python necessária para o pacote.
- **Código atual:**     setup(
- **Sugestão:**     setup(
        python_requires='>=3.6',
        

