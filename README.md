<h1>Ciclo de vida da Activity (N3) 🖥️</h1>
<h4>  O ciclo de vida de uma Activity no Android consiste em uma serie de etapas da criação a finalização, Essas etapas são controladas por diversos callbacks, que possibilitam aos programadores personalizarem o modo como a Activity se comporta diante das alterações no estado da aplicação.
 São elas:</h4>
<li>onCreate - Na Activity, é a primeira função a ser acionada. Normalmente, ela cuida de carregar os layouts XML e realizar outras operações iniciais. É realizada apenas uma vez.</li>
<li>onStart() - Quando a Activity se torna visível para o usuário, é acionado. Nesse momento, a Activity estará prestes a se tornar interativa. </li>
<li>onResume() - Ao ser iniciada a interação com o usuário, a Activity é colocada no topo da pilha de atividades e passa a receber todas as entradas do usuário.</li>
<li>onPause() -É a primeira funçao a ser iniciada quando você quer interromper ações.</li>
<li>onStop() -Acionado quando a Activity não está mais sendo exibida ao usuário. Isso pode ocorrer devido à destruição da Activity ou ao início de outra Activity.</li>
<li>onDestroy() - Acionado quando a Activity não está mais sendo exibida ao usuário. Isso pode ocorrer devido à destruição da Activity ou ao início de outra Activity.</li>
<li>onRestart() - É ativado quando a Activity não está mais visível para o usuário. Isso pode acontecer devido à finalização da Activity ou ao início de outra Activity.</li>
