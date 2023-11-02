<script>
    // TODO 課題1 クリックしてカウントが増えるごとに変数doubledの値が2倍になるように修正してください
    let count = 0;
    let doubled = 0;
    function increment() {
        count += 1;
    }
</script>

<button on:click={increment}>
  Clicked {count}
  {count === 1 ? 'time' : 'times'}
</button>
<p>{count} doubled is {doubled}</p>