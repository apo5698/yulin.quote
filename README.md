<div id="quote"></div>
<script>
  const quotesFile = '/yulin.quote/quotes.txt';
  fetch(quotesFile)
    .then(res => response.text())
    .then(text => {
      // let quotes = text.split('\n');
      document.getElementById('quote').innerHTML = text;
    })
</script>