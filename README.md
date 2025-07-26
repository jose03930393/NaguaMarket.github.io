<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Formulario Full Claro Doble Play</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-image: url('FONDO.jpg'); /* Asegúrate de subir esta imagen también */
      background-size: cover;
      background-repeat: no-repeat;
      background-position: center;
      margin: 0;
      padding: 0;
      backdrop-filter: brightness(0.8);
    }

    .form-container {
      background-color: rgba(255, 255, 255, 0.95);
      max-width: 500px;
      margin: 40px auto;
      padding: 20px;
      border-radius: 15px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.2);
    }

    h2 {
      color: #E60000;
      text-align: center;
    }

    label {
      display: block;
      margin-top: 15px;
      font-weight: bold;
      color: #333;
    }

    input[type="text"],
    input[type="email"],
    input[type="tel"],
    input[type="file"] {
      width: 100%;
      padding: 10px;
      margin-top: 5px;
      border: 1px solid #ccc;
      border-radius: 8px;
    }

    input[type="submit"] {
      background-color: #E60000;
      color: white;
      padding: 12px;
      border: none;
      border-radius: 8px;
      margin-top: 20px;
      width: 100%;
      font-size: 16px;
      cursor: pointer;
    }

    input[type="submit"]:hover {
      background-color: #b90000;
    }

    .note {
      font-size: 0.9em;
      color: #555;
      margin-top: 10px;
    }
  </style>
</head>
<body>

<div class="form-container">
  <h2>Venta Full Claro Doble Play</h2>
  <form id="claroForm" enctype="multipart/form-data">
    <label for="nombre">Nombre del Cliente</label>
    <input type="text" id="nombre" name="nombre" required>

    <label for="correo">Correo Electrónico</label>
    <input type="email" id="correo" name="correo" required>

    <label for="telefono1">Teléfono #1</label>
    <input type="tel" id="telefono1" name="telefono1" required>

    <label for="telefono2">Teléfono #2</label>
    <input type="tel" id="telefono2" name="telefono2">

    <label for="cedula_frontal">Foto de Cédula (Frente)</label>
    <input type="file" id="cedula_frontal" name="cedula_frontal" accept="image/*" required>

    <label for="cedula_trasera">Foto de Cédula (Atrás)</label>
    <input type="file" id="cedula_trasera" name="cedula_trasera" accept="image/*" required>

    <label for="foto_medidor">Foto del Medidor de la Casa</label>
    <input type="file" id="foto_medidor" name="foto_medidor" accept="image/*" required>

    <input type="submit" value="Enviar Solicitud">
    <p class="note">Este formulario no almacena datos automáticamente. Para funcionalidad real, se requiere backend o integración con servicio externo.</p>
  </form>
</div>

</body>
</html>