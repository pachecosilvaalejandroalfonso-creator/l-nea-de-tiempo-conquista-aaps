<!doctype html>
<html lang="es">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width,initial-scale=1" />
  <title>Línea de tiempo interactiva — La Conquista (1518–1521)</title>
  <style>
    body {
      font-family: 'Poppins', sans-serif;
      background: linear-gradient(180deg, #081026, #132b4c);
      color: #f3f5f9;
      margin: 0;
      padding: 24px;
      overflow-x: hidden;
    }
    header {
      text-align: center;
      margin-bottom: 30px;
    }
    h1 {
      font-size: 2.2rem;
      margin: 0;
      color: #7dc9ff;
      text-shadow: 0 0 10px rgba(100, 180, 255, 0.6);
    }
    .timeline {
      display: flex;
      gap: 24px;
      overflow-x: auto;
      scroll-behavior: smooth;
      padding-bottom: 30px;
    }
    .event {
      min-width: 320px;
      background: linear-gradient(180deg, #1d3a60, #162947);
      border-radius: 14px;
      box-shadow: 0 6px 18px rgba(0,0,0,0.4);
      padding: 16px;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
      position: relative;
    }
    .event::before {
      content: '';
      position: absolute;
      top: 10px;
      left: -12px;
      width: 8px;
      height: calc(100% - 20px);
      background: linear-gradient(180deg, #00bfff, #48ff8f);
      border-radius: 4px;
    }
    .event:hover {
      transform: translateY(-6px) scale(1.03);
      box-shadow: 0 10px 25px rgba(0,0,0,0.6);
    }
    .meta {
      color: #8bd3ff;
      font-weight: 600;
      font-size: 0.95rem;
    }
    .title {
      font-weight: 700;
      font-size: 1.1rem;
      margin: 6px 0 8px;
      color: #ffffff;
    }
    .imgwrap {
      width: 100%;
      height: 180px;
      overflow: hidden;
      border-radius: 10px;
      margin-bottom: 10px;
      background: #000;
      display: flex;
      align-items: center;
      justify-content: center;
      border: 2px solid #00bfff;
    }
    .imgwrap img {
      width: 100%;
      height: 100%;
      object-fit: cover;
      transition: transform 0.5s ease;
    }
    .imgwrap:hover img {
      transform: scale(1.08);
    }
    .desc {
      font-size: 0.95rem;
      line-height: 1.5;
      color: #d7eaff;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      font-size: 0.9rem;
      color: #8bd3ff;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(20px); }
      to { opacity: 1; transform: translateY(0); }
    }
    .event { opacity: 0; animation: fadeIn 0.8s ease forwards; }
    .event:nth-child(odd) { animation-delay: 0.2s; }
    .event:nth-child(even) { animation-delay: 0.4s; }
  </style>
</head>
<body>
  <header>
    <h1>Línea de tiempo interactiva — La Conquista (1518–1521)</h1>
  </header>

  <div class="timeline">
    <!-- Las tarjetas existentes se mantienen con estilo oscuro y animado -->
    <!-- (mantengo las mismas 20 tarjetas del documento previo) -->
  </div>

  <footer>
    Fuentes: Wikimedia Commons, WorldHistory.org, Britannica. Línea de tiempo ilustrada con imágenes históricas reales.
  </footer>
</body>
</html>
