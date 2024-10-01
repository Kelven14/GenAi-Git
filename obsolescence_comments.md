**main.py (Linha 1):** Obsolescência detectada. Razão: O módulo 'distutils.core' está obsoleto em Python 3.12. Utilize 'setuptools' para criar pacotes.. Sugestão: from setuptools import setup.
**main.py (Linha 4):** Obsolescência detectada. Razão: É recomendado definir a versão mínima do Python compatível para o pacote. Adicione 'python_requires' para garantir a compatibilidade com Python 3.6 ou superior.. Sugestão:     setup(
        name='meu_pacote',
        version='0.1dev',
        packages=['meu_modulo'],
        description='Um exemplo de pacote usando setuptools',
        author='Seu Nome',
        author_email='seu.email@example.com',
        url='http://exemplo.com',
        python_requires='>=3.6',
    ).