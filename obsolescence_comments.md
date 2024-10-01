# Coment�rios sobre Obsolesc�ncias

### main.py (Linha 1)
- **Obsolesc�ncia detectada:** O m�dulo 'distutils.core' est� obsoleto no Python 3.12. Use 'setuptools' para a cria��o de pacotes.
- **Sugest�o:** from setuptools import setup


### main.py (Linha 11)
- **Obsolesc�ncia detectada:** O atributo 'author_email' � considerado obsoleto em 'setup' do 'setuptools'. Embora ainda funcione, � recomend�vel usar 'author_email' no lugar.
- **Sugest�o:** author_email='seu.email@example.com',

