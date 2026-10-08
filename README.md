<html lang="es">
<head>
<meta charset="utf-8">
<meta name="viewport" content="width=device-width, initial-scale=1">

<title>Boris Jesús Steinbach Saucedo — Portfolio</title>

<style>

:root{
  --bg:#fff;
  --fg:#111;
  --muted:#666;
  --line:#e3e3e3;
  --accent:#111;
  --card:#f6f6f6;
}

@media (prefers-color-scheme:dark){
  :root{
    --bg:#0e0e0e;
    --fg:#eee;
    --muted:#999;
    --line:#2a2a2a;
    --accent:#fff;
    --card:#181818;
  }
}

*{
  box-sizing:border-box;
}

body{
  margin:0;
  background:var(--bg);
  color:var(--fg);
  font-family:system-ui,-apple-system,"Segoe UI",Roboto,sans-serif;
  line-height:1.55;
}

header{
  background:#000;
  color:#fff;
  padding:4rem 1.25rem;
}

.wrap{
  max-width:900px;
  margin:0 auto;
  padding:0 1.25rem;
}

header .wrap{
  padding:0;
}

h1{
  margin:0 0 .5rem;
  font-size:clamp(2rem,5vw,3rem);
  font-weight:600;
  letter-spacing:-.03em;
}

header .headline{
  font-size:1.1rem;
  color:#ddd;
  margin:.5rem 0;
}

header .contact{
  color:#aaa;
  margin-top:1rem;
}

header a{
  color:#fff;
}

.button{
  display:inline-block;
  margin-top:1.4rem;
  padding:.65rem 1rem;
  border:1px solid #fff;
  border-radius:6px;
  color:#fff;
  text-decoration:none;
  font-weight:600;
}

.button:hover{
  background:#fff;
  color:#000;
}

section{
  padding:2.5rem 0;
  border-bottom:1px solid var(--line);
}

h2{
  font-size:1.35rem;
  margin:0 0 1.2rem;
  font-weight:600;
}

h3{
  margin:0 0 .4rem;
  font-size:1rem;
}

.item{
  margin-bottom:1.5rem;
}

.item:last-child{
  margin-bottom:0;
}

.item .row{
  display:flex;
  justify-content:space-between;
  gap:1rem;
  flex-wrap:wrap;
}

.item b{
  font-weight:600;
}

.muted{
  color:var(--muted);
  font-size:.95rem;
}

.tags{
  display:flex;
  flex-wrap:wrap;
  gap:.5rem;
  padding:0;
  margin:0;
  list-style:none;
}

.tags li{
  background:var(--card);
  border:1px solid var(--line);
  border-radius:999px;
  padding:.35rem .8rem;
  font-size:.9rem;
}

.project{
  background:var(--card);
  border:1px solid var(--line);
  border-radius:8px;
  padding:1.4rem;
}

.project-title{
  display:flex;
  justify-content:space-between;
  align-items:flex-start;
  gap:1rem;
  flex-wrap:wrap;
}

.project a{
  display:inline-block;
  margin-top:.5rem;
  color:var(--fg);
  font-weight:600;
}

.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
  gap:1.2rem;
}

.card{
  border:1px solid var(--line);
  border-radius:8px;
  padding:1.2rem;
}

.card p{
  margin:.4rem 0 0;
  color:var(--muted);
}

footer{
  padding:2rem 0;
  color:var(--muted);
  font-size:.85rem;
  text-align:center;
}

@media(max-width:600px){

  header{
    padding:3rem 1.25rem;
  }

  .item .row{
    display:block;
  }

  .item .row .muted{
    display:block;
    margin-top:.2rem;
  }

}

</style>
</head>


<body>


<header>

  <div class="wrap">

    <h1>Boris Steinbach Saucedo</h1>

    <p class="headline">
      Ingeniería Comercial · Análisis de datos · Gestión comercial
    </p>

    <p class="contact">
      <a href="mailto:boris.steinbach.saucedo@gmail.com">
        boris.steinbach.saucedo@gmail.com
      </a>
      · Santa Cruz de la Sierra, Bolivia
    </p>

    <a class="button" href="analisis-datos.html">
      Ver proyecto de análisis de datos →
    </a>

  </div>

</header>


<main class="wrap">


<section>

  <h2>Perfil</h2>

  <p>
    Estudiante de Ingeniería Comercial con experiencia en gestión
    comercial, control de ventas y relación con clientes. Actualmente
    desarrollo competencias en análisis de datos utilizando Python,
    Pandas, Excel y Power BI, con interés en aplicar herramientas
    analíticas a problemas de negocio y toma de decisiones.
  </p>

</section>


<section>

  <h2>Experiencia</h2>


  <div class="item">

    <div class="row">
      <b>Sales Controller</b>
      <span class="muted">ene 2021 – dic 2026</span>
    </div>

    <div class="muted">
      Fábrica de Mermeladas y Caramelos Watt's Casal S.R.L.
      · Santa Cruz de la Sierra
    </div>

    <p>
      Gestión y seguimiento de información comercial, control de
      ventas y apoyo a procesos relacionados con clientes, rutas
      y desempeño comercial.
    </p>

  </div>


  <div class="item">

    <div class="row">
      <b>Ayudante de Iluminación — Programa «Uno Decide»</b>
      <span class="muted">ene – feb 2020</span>
    </div>

    <div class="muted">
      Red Uno · Santa Cruz de la Sierra
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Actor</b>
      <span class="muted">dic 2017</span>
    </div>

    <div class="muted">
      Paceña · Cervecería Boliviana Nacional S.A.
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Marketing Digital</b>
      <span class="muted">2016 – 2021</span>
    </div>

    <div class="muted">
      Khro H. | Bienes Raíces · Santa Cruz de la Sierra
    </div>

    <p>
      Community Manager y edición de imagen y video.
    </p>

  </div>


  <div class="item">

    <div class="row">
      <b>Street Marketing</b>
      <span class="muted">ago 2016</span>
    </div>

    <div class="muted">
      SAE S.A.
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Encargado de Almacén</b>
      <span class="muted">2015</span>
    </div>

    <div class="muted">
      Lavayen Motors · Santa Cruz de la Sierra
    </div>

    <p>
      Control de inventario.
    </p>

  </div>


  <div class="item">

    <div class="row">
      <b>Técnico en computación</b>
      <span class="muted">2012</span>
    </div>

    <div class="muted">
      Zsolutions Corp · Santa Cruz de la Sierra
    </div>

    <p>
      Reparación de hardware y software.
    </p>

  </div>

</section>


<section>

  <h2>Formación</h2>


  <div class="item">

    <div class="row">
      <b>Ingeniería Comercial</b>
      <span class="muted">2018 – presente</span>
    </div>

    <div class="muted">
      Universidad NUR · Santa Cruz de la Sierra
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Diseño Gráfico y Edición de Video</b>
      <span class="muted">2021</span>
    </div>

    <div class="muted">
      EduDiseño
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Marketing Digital</b>
      <span class="muted">2021</span>
    </div>

    <div class="muted">
      EduDiseño
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Ventas directas, negociación y relación con clientes</b>
      <span class="muted">2022</span>
    </div>

    <div class="muted">
      Crehana · Online
    </div>

  </div>


  <div class="item">

    <div class="row">
      <b>Academia de Excel</b>
      <span class="muted">en curso</span>
    </div>

    <div class="muted">
      Crehana · Online
    </div>

  </div>


  <div class="item">

    <b>Bachiller en Humanidades</b>

    <div class="muted">
      Colegio Isabel Saavedra
    </div>

  </div>

</section>


<section>

  <h2>Proyecto destacado</h2>

  <div class="project">

    <div class="project-title">

      <b>Análisis Comercial y Segmentación de Clientes</b>

      <span class="muted">
        Python · Pandas · NumPy · Matplotlib
      </span>

    </div>

    <p>
      Proyecto de análisis de datos comerciales orientado a
      identificar patrones de ventas, comportamiento de clientes
      y oportunidades de segmentación.
    </p>

    <p>
      Incluye análisis por zona, rutas, rubros y segmentación
      ABC de clientes.
    </p>

    <a href="analisis-datos.html">
      Ver proyecto completo →
    </a>

  </div>

</section>


<section>

  <h2>Competencias</h2>

  <div class="grid">

    <div class="card">

      <h3>Análisis y datos</h3>

      <ul class="tags">
        <li>Python</li>
        <li>Pandas</li>
        <li>NumPy</li>
        <li>Matplotlib</li>
        <li>Excel</li>
        <li>Power BI</li>
        <li>Power Pivot</li>
      </ul>

    </div>


    <div class="card">

      <h3>Gestión comercial</h3>

      <ul class="tags">
        <li>Ventas</li>
        <li>Negociación</li>
        <li>Relación con clientes</li>
        <li>Control comercial</li>
        <li>Dual ERP</li>
        <li>Facturación electrónica</li>
      </ul>

    </div>


    <div class="card">

      <h3>Creatividad y tecnología</h3>

      <ul class="tags">
        <li>Photoshop</li>
        <li>Illustrator</li>
        <li>Premiere</li>
        <li>Audition</li>
        <li>Ableton</li>
        <li>FL Studio</li>
      </ul>

    </div>

  </div>

</section>


<section>

  <h2>Aptitudes</h2>

  <ul class="tags">

    <li>Proactividad</li>
    <li>Pensamiento crítico</li>
    <li>Aprendizaje continuo</li>
    <li>Adaptación</li>
    <li>Creatividad</li>
    <li>Negociación</li>
    <li>Relación con clientes</li>

  </ul>

</section>


<section style="border:0">

  <h2>Intereses</h2>

  <ul class="tags">

    <li>Economía</li>
    <li>Tecnología</li>
    <li>Filosofía</li>
    <li>Psicología</li>
    <li>Gastronomía</li>
    <li>Arte</li>

  </ul>

</section>


</main>


<footer>

  <div class="wrap">
    © Boris Steinbach Saucedo
  </div>

</footer>


</body>
</html>
