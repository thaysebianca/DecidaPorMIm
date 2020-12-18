# DecidaPorMIm
#script que responda qualquer pergunta que for feita a ele.

import random

class DecidaPorMim:
    def __init__(self):
        self.respostas = [
            'Sim, é claro!', 'Você tem o meu apoio.', 'SIIIIM', 'É o que sempre digo: Mais vale um pássaro na mão do que dois voando.',
            'Que tal você tentar? É melhor do que ficar na dúvida.',
            'Hmmm...acho melhor você rever isso.', 'Não, é óbvio que não!',
            'Poxa, isso não vai dar certo!', 'Uau, arrasou!', 'Adorei.', 'Ótimo, você sabe o que fazer.',
            'Me surpreenda, com o seu melhor.', 'Não!', 'Pode ser', 'Tanto faz, a escolha é sempre sua.']
    
    def inicio(self):
        input("Olá, sou sua conselheira. Me faça uma pergunta: ")
        print(random.choice(self.respostas))
        
decisao = DecidaPorMim()
decisao.inicio()
