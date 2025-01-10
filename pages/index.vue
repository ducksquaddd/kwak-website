<template>
  <div class="flex items-center justify-center mt-10">
    <div class="max-w-3xl mx-auto text-center">
      <h1 class="text-7xl font-bold mb-8 text-white">
        Elys <span class="text-yellow-400">Scan</span>
      </h1>

      <div
        class="bg-gray-800 rounded-lg p-8 shadow-lg transform hover:scale-105 transition-transform duration-300"
      >
        <p class="text-gray-300 text-xl mb-6">
          Elys Scan is our Elys dedicated block explorer.
        </p>

        <p class="text-gray-400 text-lg mb-6">
          Elys Scan is an advanced tool that that not only indexes transactions,
          but events. Transactions include Swaps (Market Orders), Adding
          Liquidity, Staking, etc.
        </p>

        <p class="text-gray-400 text-lg">
          Event's can include when Swaps execute (E.g Limit buys),
          Liquidiations, Take Profit, etc.
          <em>Most</em> On and Offchain things.
        </p>

        <div class="flex justify-center space-x-4 mt-8">
          <a
            href="https://elysscan.io"
            target="_blank"
            class="px-8 py-3 bg-yellow-500 text-gray-900 font-bold rounded-lg hover:bg-yellow-400 transition-colors duration-300"
          >
            Visit Elys Scan
          </a>
          <a
            href="https://github.com/kwak-labs"
            target="_blank"
            class="px-8 py-3 bg-gray-700 text-white font-bold rounded-lg hover:bg-gray-600 transition-colors duration-300"
          >
            View More Projects
          </a>
        </div>
      </div>
    </div>
  </div>
</template>

<style>
.text-yellow-400 {
  color: #e1b723;
}
</style>
