# Comentários sobre Obsolescências

### main.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' está obsoleto no Python 3.12. Use 'setuptools' para a criação de pacotes.
- **Sugestão:** from setuptools import setup


### main.py (Linha 11)
- **Obsolescência detectada:** O atributo 'author_email' é considerado obsoleto em 'setup' do 'setuptools'. Embora ainda funcione, é recomendável usar 'author_email' no lugar.
- **Sugestão:** author_email='seu.email@example.com',

