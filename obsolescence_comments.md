# Comentários sobre Obsolescências

### teste.py (Linha 1)
- **Obsolescência detectada:** O módulo 'distutils.core' foi depreciado em Python 3.12. O módulo 'setuptools' deve ser usado para criar pacotes Python.
- **Sugestão:** from setuptools import setup


### teste.py (Linha 12)
- **Obsolescência detectada:** O uso de 'print' com uma string literal é considerado uma sintaxe obsoleta em Python 3.12. O uso de 'f-strings' é recomendado para formatação de strings.
- **Sugestão:** print("Pacote configurado com sucesso!")

