<script>

// https://github.com/brene/adaptive-gradient
function gradient(hex) {
  var hsl = convert.hex.hsl(hex);
  var h = (hsl[0] - 25 + 360) % 360;
  var s = Math.min(Math.max(hsl[1] - 20, 50), 100);
  var l = Math.min(Math.max(hsl[2] + 10, 0), 100);

  var rgb = convert.hex.rgb(hex);
  var brightness = Math.sqrt(Math.pow(rgb[0], 2) * .299 + Math.pow(rgb[1], 2) * .587 + Math.pow(rgb[2], 2) * .114);

  return {
    start: hex,
    end: convert.hsl.hex([h, s, l]),
    fontShouldBeLight: brightness < 128
  };
};

</script>
