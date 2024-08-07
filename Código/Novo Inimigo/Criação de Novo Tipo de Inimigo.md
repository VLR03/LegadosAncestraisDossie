Componentes Obrigatórios:

Collider2D
RigidBody2D
InimigoIA
- campos modificáveis: 
	- Rcdf - de quanto em quanto tempo o inimigo mudará de direção;
	- TipoInimigo - o script específico do inimigo, ex: atirador, padrao;
	- PararQndAtaca - booleano, Identifica se, ao encontrar o player, o inimigo irá parar de se mover para atacar, ex: atirador;
	- Ataque Cooldown - de quanto em quanto tempo o inimigo irá atacar;
InimigoPathFinding
- campos modificáveis: 
	- Mov Vel - velocidade de movimento
	- Pegar Dist - qual o 'range' para encontrar o player 
InimigoVida
- campos modificáveis: 
	- Vida Inicial 
Empurrao
Flash
PegarExtras
- campos modificáveis: 
	- Moeda Prefab - prefab a ser instanciado ao derrotar o inimigo

Script do tipo de Inimigo:

![[Pasted image 20240806175141.png]]
Para o funcionamento normal, é necessário apenas herdar do _IInimigo_ a função _Atacar_ e implementá-la. Esse script deverá ser atribuído no campo _TipoInimigo_ do script _InimigoIA_.


