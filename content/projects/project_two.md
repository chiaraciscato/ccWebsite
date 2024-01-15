---
title: Climate Change in the Arctic
draft: false
language: english
tags:
    - Python
    - Climate Change
    - Arctic
hideSummary: true
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/chiaraciscato/arcticVisuals/
---

{{< rawhtml >}}
<head>
    <style>
        .btn1 {
            border: .5px solid black;
            background-color: white;
            border-radius: 10px;
            color: black;
            padding: 15px 20px;
            font-size: 13px;
            cursor: pointer;
            position: absolute;
            /* right: 40%;
            top: 41% */
        }
    </style>
</head>
<body>
    <div class="container" style="text-align: center; margin-top: 5em;">
        <img src="/MonthlyArcticTemp.png" onclick="enlargeImg()" id="ampl" />
        <br /><br /><br />
        <div class="btn1">
            <button onclick="resetImg()">reset image size</button>
        </div>
    </div>
    
    <!-- script to set display property -->
    <script>
        img = document.getElementById("ampl");
        function enlargeImg() {
            img.style.transform = "scale(1.4)";
            img.style.transition = "transform 0.25s ease";
        }
        function resetImg() {
            img.style.transform = "scale(1)";
            img.style.transition = "transform 0.25s ease";
        }
    </script>
</body>

{{< /rawhtml >}}

<!-- <center><img loading="lazy" src="" alt="" class="centerImage" width="700" height="380"></center> -->

{{< rawhtml >}}

<p style="margin-bottom:7em"></p>

{{< /rawhtml >}}

### Context

{{< rawhtml >}}

<p>The Arctic is the Earth's region that lies North of the 66° 34' parallel. Geographically, it expands over multiple countries, including Canada, Finland, Greenland, Iceland, Norway, Russia, Sweden and the United States, in Alaska, and it is mainly composed of water that freezes over the cold months and melts over the warm months.</p> 

<p>Together with its geographic opposite, the Antarctic, the Arctic has a fundamental role in global climate stabilisation. On the one hand, its white surface is able to radiate most of the incoming solar radiation back into space, therefore reflecting part of the Sun's heat. On the other, the Arctic tundra stores immense quantities of carbon dioxide (CO<sub>2</sub>) and methane (CH<sub>4</sub>) that would otherwise contribute to further global warming.</p>

<p>With regard to climate change, the Arctic is an area of extreme vulnerability. Temperatures are rising twice to three times as fast compared to the global average, in a process that is commonly referred to as Arctic amplification. When sea ice melts, it leaves land and ocean surfaces uncovered which, of darker colour, absorb heat and accelerate further ice loss. </p>

{{< /rawhtml >}}

[access the GitHub repository](https://github.com/chiaraciscato/arcticVisuals/tree/main) 

{{< rawhtml >}}

<hr />

{{< /rawhtml >}}

<p>
</p>

{{< rawhtml >}}

<p>Here are some of my contributions for <a href="https://www.osservatorioartico.it/" title="OsservatorioArtico">OsservatorioArtico</a>, an Italian online journal that focuses on the Arctic region:<p>

<p><a href="https://www.osservatorioartico.it/amplificazione-artica/" title="What is Arctic Amplification">What is Arctic Amplification</a><p>
<p><a href="https://www.osservatorioartico.it/mare-co2-beaufort/" title="The Beaufort Sea is emitting CO<sub>2</sub>">The Beaufort Sea is emitting CO<sub>2</sub></a><p>

{{< /rawhtml >}}