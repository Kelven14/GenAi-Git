**main.py (Linha 1):** Obsolesc�ncia detectada. Raz�o: O m�dulo 'distutils.core' est� obsoleto em Python 3.12. Utilize 'setuptools' para criar pacotes.. Sugest�o: from setuptools import setup.
**main.py (Linha 4):** Obsolesc�ncia detectada. Raz�o: � recomendado definir a vers�o m�nima do Python compat�vel para o pacote. Adicione 'python_requires' para garantir a compatibilidade com Python 3.6 ou superior.. Sugest�o:     setup(
        name='meu_pacote',
        version='0.1dev',
        packages=['meu_modulo'],
        description='Um exemplo de pacote usando setuptools',
        author='Seu Nome',
        author_email='seu.email@example.com',
        url='http://exemplo.com',
        python_requires='>=3.6',
    ).