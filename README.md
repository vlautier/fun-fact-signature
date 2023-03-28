<html>
<head>
  <script>
    function generateFunFact() {
      const facts = [
        "The world's oceans have absorbed 90% of the excess heat caused by climate change.",
        "The 20 warmest years on record have all occurred since 1981, and the 10 warmest have occurred since 1998.",
        "By 2050, the Arctic Ocean could be ice-free in the summer.",
        "The Greenland ice sheet has lost an average of 260 billion tons of ice per year between 2002 and 2018.",
        "Carbon dioxide levels in the Earth's atmosphere are now higher than they have been in at least 800,000 years."
      ];
      const fact = facts[Math.floor(Math.random() * facts.length)];
      document.getElementById("fun-fact").textContent = fact;
    }
  </script>
</head>
<body onload="generateFunFact();">
  <p>
    Random Fun Fact: <span id="fun-fact"></span>
  </p>
</body>
</html>
