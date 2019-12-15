<template>
  <section>
    <img class="Ethereum" src="images/ethereum.jpg" alt="Ethereum" />

    <h1>Vitalik Buterin and POS.</h1>
    <p></p>

    <div class="">
      <img class="" src="" alt="" />
      <div class="">
        <h2>The white papper and the yellow papper.</h2>
        <p>
          Las tres principales caracteristicas de las que hablaba Vitalik que
          podrian beneficiar el tener un sistema de turing completo eran:
        </p>

        <ul>
          <li>
            1-la sub-moneda podria ser completanmente almacenada como un
            contrato.
          </li>
          <li>
            2-El arbol de Merkle de la sub-moneda puede ser almacenado en un
            contrato, y en la parte superior de la cadena con lo que con cada
            actualizacion del arbol es validado por el contrato.
          </li>
          <li>
            3-Dos cadenas de bloques pero donde ethereum posee un cliente SPV en
            la otra cadena.
          </li>
        </ul>
        <a class="Link1" href="https://ethereum.org/">Ethereum.org</a>
      </div>
    </div>
    <hr />
    <div class="">
      <h2>What is POS?</h2>
      <div class="">
        <img class="" src="" alt="" />
        <h3></h3>
        <p>
          El concepto de Proof of Stake, empezo tambien a ser implementado con
          la crypto Ethereum. La utilidad en si de esta tecnologia es que no hay
          una competicion por ser el que tiene mas potencia de computo para
          generar un bloque, sino que en funcion de las monedas que tengas seras
          recompensado proporcionalmente. Para que pudiese generarse un bloque
          malicioso haria falta al menos el 51% de dichas monedas.
        </p>
      </div>
    </div>
    <hr />
    <div class="">
      <h2>EVM</h2>
      <p>
        The Ethereum Virtual Machine. Los Smart Contracts estan escritos en
        Solidity, lenguaje similar a JavaScript y C++. Estos no pueden ser
        ejecutados directamente por la maquina virtual, primero neecsitan ser
        compilados a un nivel mas bajo llamado Opcodes.Gracias a estas
        instrucciones basicas, la maquina virtual puede ejecutar un sistema
        turing completo.
      </p>
      <a class="" href=""></a>
      <hr />
    </div>
  </section>
</template>

<script>
export default {
  name: "Ethereum"
};
</script>

<style>
p {
  padding: 10px, 5px;
}

.Link1 {
  font-size: 22px;
}

.Link2 {
  font-size: 22px;
}

li {
  text-align: justify;
}
</style>
