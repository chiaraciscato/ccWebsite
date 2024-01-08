---
title: Effects of Ocean Alkalinity Enhancement on the Seasonal Cycle of CO₂ Flux and Ocean pCO₂
draft: false
language: english
hideSummary: true
tags:
    - Python
    - Climate Change
    - Carbon Dioxide Removal
links:
- icon: github
  icon_pack: fab
  name: Code
  url: https://github.com/chiaraciscato/OAEseasonality/tree/main
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
            right: 40%;
            top: 53%
        }
    </style>
</head>
<body>
    <div class="container" style="text-align: center; margin-top: 5em;">
        <img src="/alkalinity_addition.png" onclick="enlargeImg()" id="ampl" />
        <br /><br /><br />
        <div class="btn1">
            <button onclick="resetImg()">reset image size</button>
        </div>
    </div>
    
    <!-- script to set display property -->
    <script>
        img = document.getElementById("ampl");
        function enlargeImg() {
            img.style.transform = "scale(1.2)";
            img.style.transition = "transform 0.25s ease";
        }
        function resetImg() {
            img.style.transform = "scale(1)";
            img.style.transition = "transform 0.25s ease";
        }
    </script>
</body>

{{< /rawhtml >}}

<!-- {{< rawhtml >}}

<center><img loading="lazy" src="/alkalinity_addition.png" alt="" class="centerImage" width="500" height="500"></center>

{{< /rawhtml >}} -->

### Abstract

{{< rawhtml >}}

<p>Anthropogenic climate change is induced by, among other causes, the release of heat-trapping CO<sub>2</sub> into the atmosphere from fossil fuel burning. According to the Intergovernmental Panel on Climate Change, in order to meet the target set by the Paris Agreement, emission reduction must be complemented by Carbon Dioxide Removal technologies aiming to sequester CO<sub>2</sub>  from the atmosphere and store it in natural reservoirs. One of such methods is Ocean Alkalinity Enhancement (OAE), which aims to lower ocean CO<sub>2</sub> partial pressure (pCO<sub>2</sub>) and accelerate the natural CO<sub>2</sub> uptake through chemical weathering. As seasonality is a fundamental component of the ocean net annual CO<sub>2</sub> uptake, this study aims to bridge the knowledge gap on the impacts of OAE on the seasonal cycle of CO<sub>2</sub>  flux and ocean pCO<sub>2</sub>. </p>

<p>An analysis was conducted on two Earth System Model outputs simulating alkalinity addition along the European coastline (with the exception of the Baltic and the Mediterranean seas), for both a low and a high emission scenario (SSP1-2.6 and SSP3-7.0, respectively). It was found that: the CO<sub>2</sub> seasonal flux is amplified with alkalinity addition, especially in winter, likely as a consequence of a larger imbalance at the air-sea interface; the ocean pCO<sub>2</sub> seasonal cycle is dampened, especially in summer, due to its decreased sensitivity to CO<sub>2</sub> fluctuations in an alkalinised ocean; both effects are magnified under SSP3-7.0. This suggests that OAE induces asymmetrical impacts on CO<sub>2</sub> seasonality, with potentially significant alterations to the net annual cycle. </p>

{{< /rawhtml >}}

**[download my MSc Thesis](/mscThesis.pdf)**
