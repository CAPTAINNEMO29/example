<template>
  <section class="Bitcoin">
    <img class="" src="images/bitcoin-225080_640.png" alt="Bitcoin" />
    <br />

    <h1>Bitcoin</h1>
    <p class="Header">
      "I've been working on a new electronic cash system that's fully
      peer-to-peer, with no trusted third party..."-Satoshi Nakamoto.
    </p>
    <img class="" src="" alt="" />
    <hr />

    <div class="BFT">
      <img class="" src="" alt="" />
      <h2>The bizantine General's Problem.</h2>
      <p>
        El problema de los geneales bizantinos fue presentado por leslie lamport
        y otros dos co-autores en el año 1982.
      </p>
      <br />
      <p>
        La alegoria del problema es asi.La noche antes del ataque el comandante
        encia un mensaje a sus generales estos deben recibir el mensaje y atacar
        a la misma hora o fallaran en el ataque, ademas deben de esatr seguros
        de que no habra espias enemigos que se enteren del ataque.
      </p>
      <br />
      <p>
        ¿Cual es la similitud con el Bitcoin?,bien pues si el traspaso de fondos
        entre dos personas no es seguro dichos fondos pueden ser robados.
      </p>
      <br />
      <p>
        Una de las primeras respuestas presentadas al problema fue escrito por
        Miguel Castro Y Barbara Liskov en 1999, ellos propusieron el BFT
        (Byzantine Fault Tolerance Protocol), la idea basicamente era qeu un
        nodo principal fuera mandando mensajes a los demas nodos, en esta
        solucion la mayoria de los nodos deben de ser honestos para que
        funcione.
      </p>
      <a
        class="Link1"
        href="https://people.eecs.berkeley.edu/~luca/cs174/byzantine.pdf"
        >Bizantine Generals Problem</a
      >
    </div>
    <hr />

    <div class="B-money">
      <h2>The B-Money</h2>
      <p>El concepto del B-Money de Wei Dai.</p>
      <br />
      <p>
        El principal objetivo en el mundo crypto anarquista, es que las
        relaciones entre las personas estan protegidas bajo el uso del
        anonimato, por lo cual la violencia no puede ser usada cuando hay
        desacuerdo.
      </p>
      <br />
      <p>
        El dinero puede ser creado y repartido entre los participantes, donando
        parte de su poder de computacion.
      </p>
      <br />
      <a class="Link1" href="http://www.weidai.com/bmoney.txt">Bit-Gold</a>
    </div>
    <hr />

    <div class="Merkle">
      <h2>The Merkle Root and SHA256.</h2>
      <img class="" src="" alt="" />
      <p>
        EL algoritmo SHA-256 consiste en 64 caracteres hexadecimales (256 bits)
        a diferencia de los algoritmos anterioes.Bitcoin con lo cual lo hace mas
        dificl de desencriptar. El Arbol de Merkle es la forma en la que se
        estrecturan los bloques que se van almacenando, dentro de cada bloques
        hay un numero de transacciones que seran pasadas a taves del algoritmo
        de forma que puedan quedar encriptadas.Bitcoin El lugar donde se van
        almacenando todas las transacciones que aun no han sido añadidas a la
        cadena de bloques, es llamado Mempool.
      </p>
      <br />
      <a
        class="Link1"
        href="https://medium.com/@stolman.b/1-1-hashing-and-sha-256-dd7d4b08d4bc"
        >SHA 256</a
      >
    </div>
    <hr />

    <div class="White-papper">
      <img class="" src="" alt="" />
      <h2>The Withe Papper</h2>
      <p>
        El Libro Blanco, es el documento que fue presentado para explicar el
        bitcoin y todos los procesos que tienen lugar dentro, de una manera
        general, aunque cada apartado dentro engloba muchas mas cosas.
      </p>
      <br />
      <a class="Link1" href="https://nakamotoinstitute.org/bitcoin/"
        >White Papper</a
      >
    </div>
  </section>
</template>

<script>
export default {
  name: "Bitcoin"
};
</script>

<style>
.Bitcoin {
  background-color: #b7fbff;
}

.Header {
  text-align: center;
}

p {
  text-align: justify;
  padding: 10px 10px;
}

.Link1 {
  font-size: 22px;
}
</style>
