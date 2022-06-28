# No Simio, como mudar o ícone de um elemento após passar por um processo?

Mudança de ícone após um processo

Neste exemplo vamos utilizar um carro que necessita de consertos e irá para uma oficina mecânica. O elemento entrará com o ícone de um carro quebrado e deverá sair com o carro arrumado.


Primeiro é necessário selecionar dois ícones, um para o início do processo e outro para o final, basta clicar em “Add Additional Symbol” -> Apply Symbol”.



Feito isso, selecione o Server em que ocorrerá o processo e defina o “State Assignments” e selecione o momento em que o ícone deve mudar, ao clicar em “Add” e em “State Variable Name”-> “ModelEntity.Picture”-> colocar o número do ícone que deverá ser exibido.
 
A imagem a seguir mostra um carro com defeito entrando em uma oficina e após isso ele sairá arrumado.
 


Processos

Delay
Processo que estabelece o tempo em que algo deve ocorrer. Neste exemplo o conserto do carro vai demorar 10 minutos, isso será definido na aba “Processes”, selecione “Create”  e arraste “Delay” para o meio do início e do fim do processo. 
Em “Delay Time” e “Units” especifique os parâmetros, é possível definir um nome para o processo, basta clicar com o botão esquerdo no processo e “Rename”.
 

Após definido o processo, vá para o Server e coloque em algum dos casos, de acordo com o desejado, de “Add-On Process Triggers” . 









Dessa forma, antes de sair da oficina cada carro demorará 10 minutos.



Autores: Kelly Alves de Paula

Wagner Gurgel

Revisão: Arnaldo Gunzi

