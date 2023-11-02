<script>
    // TODO 課題1 クリックしてカウントが増えるごとにpタグ内のdoubled値がcountの2倍の値で反映されるようにしてください。
    // TODO 課題2 countが10以上になったらalertを出してcountを0にリセットしてください
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