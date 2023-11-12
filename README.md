Este é um exemplo simples de comunicação remota usando XML-RPC em Python. Neste exemplo, dois computadores podem se comunicar remotamente usando um servidor XML-RPC e um cliente que chama métodos remotamente.

Servidor (Computador B)
O servidor fornece um objeto chamado ObjetoSomadorB com um método Somar que soma dois números.

Executando o Servidor
bash
Copy code
python servidor.py
O servidor será iniciado em http://localhost:8000. Certifique-se de ajustar o endereço conforme necessário.

Cliente (Computador A)
O cliente cria um proxy para o objeto somador remoto no servidor (Computador B) e chama o método Somar remotamente.

Executando o Cliente
bash
Copy code
python cliente.py
O resultado da soma remota será exibido.
