<template>
  <section class="Bitcoin">
    Blockchain

    <img class="" src="" alt="Bitcoin" />

    <h1>Bitcoin</h1>
    <p>
      "I've been working on a new electronic cash system that's fully
      peer-to-peer, with no trusted third party..."-Satoshi Nakamoto.
    </p>
    <img class="" src="" alt="" />
    <hr />

    <div class="BFT">
      <img class="" src="" alt="" />
      <h2>The bizantine General's Problem.</h2>
      <p>
        The Byzantine Generals Problem gets its name from a 1982 paper in which
        Leslie Lamport and two co-authors described an allegory for the problems
        of decentralized decision-making.
      </p>
      <br />
      <p>
        The allegory comes like this, the night before the atack, the comander
        send message to theri Generals but inside his own men they are traitors,
        so if the traitors read the operation the attack will fall.
      </p>
      <br />
      <p>
        What is the similitude with Bitcoin?, well it is that if a transaction
        betwen two person are non trusted, their funds can be stolen.
      </p>
      <br />
      <p>
        One of the first methods suggested to deal with this issue came about in
        1999 in a paper written by Miguel Castro and Barbara Liskov. They
        proposed the Practical Byzantine Fault Tolerance protocol. this idea it
        was a client will sent a message to a one primary node that later will
        sent this message to the another nodes, in this idea the majority part
        of the nodes are supouse to be honest for not be in danger.
      </p>
    </div>
    <hr />

    <div class="B-money">
      <h2>The B-Money</h2>
      <p>The Concept of B-Money of Wei Dai.</p>
      <br />
      <p>
        The main objective about the money in the crypto anarchist, is that the
        realtions between people are protected, so violence can not be used if
        they start to disagree because they are protected for their privacy.
      </p>
      <br />
      <p>
        The money also can be create by anyone just using the power computation
        of your own CPU and you will be rewarded.
      </p>
      <br />
      <a class="" href="http://www.weidai.com/bmoney.txt">Bit-Gold</a>
    </div>
    <hr />

    <div class="Merkle">
      <h2>The Merkle Root and SHA256.</h2>
      <img class="" src="" alt="" />
      <p></p>
    </div>
    <hr />

    <div class="White-papper">
      <img class="" src="" alt="" />
      <h2>The Withe Papper</h2>
      <p></p>
    </div>
    <hr />

    <div class="">
      <h2></h2>
      <router-link to=""></router-link>
      <router-link to=""></router-link>
      <h3></h3>
      <p></p>
      <a class="" href=""></a>
    </div>
    <hr />
  </section>
</template>

<script>
export default {
  name: "Blockchain"
};
</script>

<style>
.Bitcoin {
  background-color: #b7fbff;
}

p {
  text-align: justify;
  padding: 10px 10px;
}
</style>
