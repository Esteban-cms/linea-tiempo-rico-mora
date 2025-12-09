<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>Línea de Tiempo - Proyecto Rico Mora</title>
<style>
  body {
    font-family: Arial, sans-serif;
    background: #f4f4f4;
    margin: 0;
    padding: 20px;
  }
  h1 {
    text-align: center;
    margin-bottom: 40px;
  }
  .timeline {
    position: relative;
    max-width: 900px;
    margin: auto;
  }
  .timeline::after {
    content: "";
    position: absolute;
    width: 4px;
    background: #2c3e50;
    top: 0;
    bottom: 0;
    left: 50%;
    margin-left: -2px;
  }
  .entry {
    padding: 15px;
    background: white;
    position: relative;
    width: 45%;
    border-radius: 6px;
    box-shadow: 0 2px 6px rgba(0,0,0,0.15);
    margin: 20px 0;
  }
  .left {
    left: 0;
  }
  .right {
    left: 55%;
  }
  .entry::after {
    content: "";
    position: absolute;
    top: 15px;
    width: 12px;
    height: 12px;
    border-radius: 50%;
    background: #2980b9;
    border: 2px solid #1f3f60;
  }
  .left::after { right: -20px; }
  .right::after { left: -20px; }
  .date {
    font-weight: bold;
    color: #2c3e50;
    margin-bottom: 5px;
  }
  .actor {
    font-size: 14px;
    font-weight: bold;
  }
  .info {
    font-size: 14px;
    margin-top: 5px;
  }
</style>
</head>
<body>
<h1>Línea de Tiempo - Proyecto Minero Rico Mora</h1>
<div class="timeline">

  <!-- Entries -->
  <div class="entry left"><div class="date">28/07/2015</div><div class="actor">Compañía</div><div class="info">Suscripción del contrato IH8-10541 para explotación de minerales en Yalí.</div></div>
  <div class="entry right"><div class="date">14/08/2016</div><div class="actor">Título minero</div><div class="info">Período de suspensión de obligaciones inscrito en Registro Minero.</div></div>
  <div class="entry left"><div class="date">27/02/2020</div><div class="actor">Compañía Rico Mora</div><div class="info">Solicitud de licencia ambiental (160ZF-COE2002-6660).</div></div>
  <div class="entry right"><div class="date">14/04/2020</div><div class="actor">Autoridad Ambiental</div><div class="info">Requerimiento para complementar FUR y ampliación de plazo.</div></div>
  <div class="entry left"><div class="date">08/07/2020</div><div class="actor">Compañía Rico Mora</div><div class="info">Entrega de complemento al Estudio de Impacto Ambiental – EIA.</div></div>
  <div class="entry right"><div class="date">03/09/2020</div><div class="actor">Autoridad Ambiental</div><div class="info">Informe técnico del EIA (sin visita por emergencia).</div></div>
  <div class="entry left"><div class="date">09/09/2020</div><div class="actor">Autoridad Ambiental</div><div class="info">Negación de la licencia ambiental.</div></div>
  <div class="entry right"><div class="date">01/10/2020</div><div class="actor">Autoridad Ambiental</div><div class="info">Recurso de reposición y entrega de información adicional.</div></div>
  <div class="entry left"><div class="date">15/10/2020</div><div class="actor">Autoridad Ambiental</div><div class="info">Se ordena continuar trámite con nuevos requerimientos.</div></div>
  <div class="entry right"><div class="date">10/05/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Memorando solicitando información sobre inversión del 1%.</div></div>
  <div class="entry left"><div class="date">26/05/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Revocación de negación; trámite vuelve a etapa de información adicional.</div></div>
  <div class="entry right"><div class="date">04/06/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Solicitud de información complementaria.</div></div>
  <div class="entry left"><div class="date">12/08/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Respuesta a requerimientos complementarios.</div></div>
  <div class="entry right"><div class="date">13/10/2021</div><div class="actor">Título minero</div><div class="info">Adición de materiales de construcción al contrato IH8-10541.</div></div>
  <div class="entry left"><div class="date">28/10/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Información completa para decidir licencia ambiental.</div></div>
  <div class="entry right"><div class="date">29/10/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Se otorga la Licencia Ambiental Mina Malabrigo.</div></div>
  <div class="entry left"><div class="date">22/11/2021</div><div class="actor">Autoridad Ambiental</div><div class="info">Respuesta sobre inversión forzosa del 1%.</div></div>
  <div class="entry right"><div class="date">26/08/2022</div><div class="actor">Autoridad Ambiental</div><div class="info">Solicitud de inscripción en RUA.</div></div>
  <div class="entry left"><div class="date">26/10/2022</div><div class="actor">Compañía Rico Mora</div><div class="info">Radicación ICA No. 1.</div></div>
  <div class="entry right"><div class="date">15/11/2022</div><div class="actor">Compañía Rico Mora</div><div class="info">Respuesta a requerimientos.</div></div>
  <div class="entry left"><div class="date">07/12/2022</div><div class="actor">Autoridad Ambiental</div><div class="info">Informe Técnico con oportunidades de mejora.</div></div>
  <div class="entry right"><div class="date">27/12/2022</div><div class="actor">Autoridad Ambiental</div><div class="info">Acto Administrativo que requiere cumplimiento.</div></div>
  <div class="entry left"><div class="date">31/01/2023</div><div class="actor">Compañía Rico Mora</div><div class="info">Autodeclaración TUA 2022.</div></div>
  <div class="entry right"><div class="date">08/02/2023</div><div class="actor">Autoridad Ambiental</div><div class="info">Objeción a volúmenes reportados en TUA.</div></div>
  <div class="entry left"><div class="date">10/04/2023</div><div class="actor">Compañía Rico Mora</div><div class="info">Respuesta parcial a requerimientos.</div></div>
  <div class="entry right"><div class="date">01/06/2023</div><div class="actor">Compañía Rico Mora</div><div class="info">Informe de seguimiento (jul–dic 2022).</div></div>
  <div class="entry left"><div class="date">09/06/2023</div><div class="actor">Compañía Rico Mora</div><div class="info">PMIRS presentado.</div></div>
  <div class="entry right"><div class="date">24/08/2023</div><div class="actor">Compañía Rico Mora</div><div class="info">Informe de Seguimiento Ambiental ene–jun 2023.</div></div>
  <div class="entry left"><div class="date">25/10/2023</div><div class="actor">Autoridad Ambiental</div><div class="info">Informe Técnico tras visita del 12 jul 2023.</div></div>
  <div class="entry right"><div class="date">17/11/2023</div><div class="actor">Autoridad Ambiental</div><div class="info">Acto Administrativo solicitando subsanar obligaciones.</div></div>
  <div class="entry left"><div class="date">20/03/2024</div><div class="actor">Compañía Rico Mora</div><div class="info">Respuesta parcial al Acto 040-ADM2311-10806.</div></div>

</div>
</body>
</html>
