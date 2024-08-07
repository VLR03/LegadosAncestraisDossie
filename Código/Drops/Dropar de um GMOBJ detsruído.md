O GameObject precisará ter os scripts "Destrutivel" (dependendo da situação. por ex, inimigos não tem) e "PegarExtras".
Exemplo do GameObject de um arbusto:
![[Pasted image 20240730124108.png]]
No script "PegarExtras", é necessário especificar qual obj será dropado (prefab). O obj dropado precisará ter configurações especificas também, ver "Novo Tipo de Drop".
No caso de inimigos, será dropado assim que o jogador purificar um deles.