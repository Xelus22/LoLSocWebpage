---
layout: post
title: Gangplank, The Saltwater Scourge
subtitle: ''
gallery: []

---
<head>
  <h4> Event Timeline </h4>

  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    * {
      box-sizing: border-box;
    }

    body {
      color:black;
      font-family: Helvetica, sans-serif;
    }
    #para1 {
      color: white;
    } 

    /* The actual timeline (the vertical ruler) */
    .timeline {
      position: relative;
      max-width: 1200px;
      margin: 0 auto;
    }

    /* The actual timeline (the vertical ruler) */
    .timeline::after {
      content: '';
      position: absolute;
      width: 6px;
      background-color: black;
      top: 0;
      bottom: 0;
      left: 50%;
      margin-left: -3px;
    }

    /* Container around content */
    .container {
      padding: 5px 40px;
      position: relative;
      background-color: inherit;
      width: 40%;
    }

    /* Place the container to the left */
    .left {
      left: 10%;
    }

    /* Place the container to the right */
    .right {
      left: 50%;
    }

    /* Add arrows to the left container (pointing right) */
    .left::before {
      content: " ";
      height: 0;
      position: absolute;
      top: 22px;
      width: 0;
      z-index: 1;
      right: 30px;
      border: medium solid black;
      border-width: 10px 0 10px 10px;
      border-color: transparent transparent transparent black;
    }

    /* Add arrows to the right container (pointing left) */
    .right::before {
      content: " ";
      height: 0;
      position: absolute;
      top: 22px;
      width: 0;
      z-index: 1;
      left: 30px;
      border: medium solid black;
      border-width: 10px 10px 10px 0;
      border-color: transparent black transparent transparent;
    }

    /* Fix the circle for containers on the right side */
    .right::after {
      left: -16px;
    }

    /* The actual content */
    .content {
      padding: 5px 30px;
      background-color:black;
      position: relative;
      border-radius: 6px;
    }

    /* Media queries - Responsive timeline on screens less than 600px wide */
    @media screen and (max-width: 600px) {
      /* Place the timelime to the left */
      .timeline::after {
        left: 31px;
      }

      /* Full-width containers */
      .container {
        width: 100%;
        padding-left: 70px;
        padding-right: 25px;
      }

      /* Make sure that all arrows are pointing leftwards */
      .container::before {
        left: 60px;
        border: medium solid white;
        border-width: 10px 10px 10px 0;
        border-color: transparent white transparent transparent;
      }

      /* Make sure all circles are at the same spot */
      .left::after, .right::after {
        left: 15px;
      }

      /* Make all right containers behave like the left ones */
      .right {
        left: 0%;
      }
    }
  </style>
</head>

<body>
  <div id="para1" class="timeline">
    <div class="container left">
    <div class="content">
        <p >Pirate training.</p>
     </div>
    </div>
    <div class="container right">
      <div class="content">
        <p>Illaoi saves Gangplank.</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <p>Gangplank falls in love with Illaoi.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <p>Illaoi leaves Gangplank for her god (Nagakaburos).</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <p>Gangplank kills Miss Fortune’s parents.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <p>Gangplank rules Bilgewater.</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <p>Gangplank raids Zed’s temple.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <p>Gangplank takes Swain’s battleship (Leviathan).</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <p>Gangplank defends Bilgewater against the Harrowing.</p>
      </div>
    </div>
    <div class="container right">
      <div class="content">
        <p>Gangplank throws Graves and Twisted Fate into the ocean.</p>
      </div>
    </div>
    <div class="container left">
      <div class="content">
        <p>Miss Fortune shoots Gangplank.</p>
      </div>
    </div>
  </div>
</body>