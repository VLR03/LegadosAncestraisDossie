No exemplo a seguir, o jogador vai da "cena 1" para a "cena 2". Em seguida fará o caminho reverso.
Em cada cena terá pelo menos um prefab "AreaSaida", por onde ocorrerá a mudança de cenas
![[Pasted image 20240721160351.png]]
Na "AreaSaida" tem o script "Saida" (print feito na Cena1)
![[Pasted image 20240721160517.png]]
Na "AreaEntrada" tem o script "Entrada" (print feito na Cena1)
![[Pasted image 20240721160859.png]]

"Prox Cena" indica para qual cena esse caminho irá levar e "Nome Transicao" qual entrada especifica na próxima cena o jogador vai aparecer.

Agora na Cena2, os scripts estão desta maneira:
![[Pasted image 20240721160957.png]]
![[Pasted image 20240721161005.png]]
