<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Formulario de Contacto</title>
<style>

        body {
            font-family: Arial, sans-serif;
            background-color: #CCCCCC;
            margin: 0;
            padding: 0;

        .contenedor-formulario {
            width: 400px;
            margin: 50px auto;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }

        h1 {
            text-align: center;
            color: #333;
        }


        p {
            text-align: center;
            font-size: 14px;
            color: #666;
        }


        label {
            display: block;
            margin-bottom: 8px;
            color: #000000;
        }

        input, select, textarea {
            width: 100%;
            padding: 10px;
            margin-bottom: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            box-sizing: border-box;
        }

        textarea {
            height: 100px;
            resize: vertical;
        }


        button {
            width: 100%;
            padding: 10px;
            background-color: #4CAF50;
            color: white;
            border: none;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #45a049;
        }
    </style>
</head>
<body>

    <div class="contenedor-formulario">
        <form action="#" method="post">
            <h1>Formulario de Contacto</h1>
            <p>Completa el formulario con tu información.</p>

            <label for="nombre">Nombre:</label>
            <input type="text" id="nombre" name="nombre" required>

            <label for="email">Correo electrónico:</label>
            <input type="email" id="email" name="email" required>

            <label for="telefono">Teléfono:</label>
            <input type="tel" id="telefono" name="telefono" required>

            <label for="pais">País:</label>
            <select id="pais" name="pais" required>
                <option value="">Selecciona un país</option>
                <option value="es">Tailandia</option>
                <option value="mx">México</option>
                <option value="ar">Filiínas</option>
                <option value="co">Canada</option>
                <option value="pe">Colombida</option>
            </select>

            <label for="comentarios">Comentarios o Preguntas:</label>
            <textarea id="comentarios" name="comentarios" required></textarea>

            <button type="submit">Enviar</button>
        </form>
    </div>

</body>
</html>
