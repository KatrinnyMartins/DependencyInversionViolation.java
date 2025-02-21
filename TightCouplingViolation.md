Erro: No codigo o erro esta na dependência direta entre a classe Motor e a classe Carro viola o princípio OCP, pois a classe Carro deveria estar aberta para extensão e fechada para modificação.

Solução do erro : Aplicar uma da versão de dependência, criando uma interface para o Engine assim a classe Car dependerá dessa interface, em vez de depender diretamente da classe específica Engine, permitindo que novas implementações de motores possam ser adicionadas sem modificação à classe Car.
