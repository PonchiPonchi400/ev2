
class MiExcepcion(Exception):
    pass

try:
    ...
    if condicion:
        raise MiExcepcion('Ocurrio un error personalizado.')
    ...
except MiExceptcion as e:
    print(str(e))
except Excepction as e:
    print(str(e))
    
class ObjetoDeNegocio:
    def __init__ (self, atributo1, atributo2):
        self.atributo1 = atributo1
        self.atributo2 = atributo2
        
        def metodo1(self):

        def metodo2(self):

from mi_libreria import ObjetoDeNegocio

objeto = ObjetoDeNegocio("valor1", "valor2")
objeto.metodo1()
