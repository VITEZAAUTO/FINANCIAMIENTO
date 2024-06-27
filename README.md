<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Financiamiento VITEZA - Venta de Autos</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-image: url('https://img.remediosdigitales.com/07fff0/lanzamientos-2023/1366_521.jpg'); /* Ruta a tu imagen de fondo */
            background-size: cover; /* Ajusta la imagen para cubrir toda la pantalla */
            background-position: center; /* Centra la imagen */
            background-repeat: no-repeat; /* Evita que la imagen se repita */
            background-attachment: fixed; /* Fija la imagen de fondo para que no se mueva al hacer scroll */
            background-color: #f0f0f0; /* Color de fondo alternativo */
        }
        header {
            background-color: #3750c0;
            color: #fff;
            text-align: center;
            padding: 10px 0;
        }
        nav {
            background-color: #444;
            padding: 10px;
            text-align: center;
        }
        nav a {
            color: #fff;
            text-decoration: none;
            margin: 0 10px;
            font-size: 16px;
        }
        nav a:hover {
            text-decoration: underline;
        }
        main {
            width: 80%;
            margin: 20px auto;
            background-color: rgba(255, 255, 255, 0.8);
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 20px rgba(0, 0, 0, 0.1);
        }
        section {
            margin-bottom: 30px;
        }
        .boton {
            display: inline-block;
            padding: 10px 20px;
            background-color: #333;
            color: #fff;
            text-decoration: none;
            border-radius: 5px;
            margin-right: 10px;
            margin-bottom: 10px;
            transition: background-color 0.3s ease;
        }
        .boton:hover {
            background-color: #555;
        }
        footer {
            text-align: center;
            padding: 10px 0;
            background-color: #333;
            color: #fff;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
        table {
            width: 100%;
            border-collapse: collapse;
            margin-bottom: 20px;
        }
        table, th, td {
            border: 1px solid #ccc;
        }
        th, td {
            padding: 10px;
            text-align: left;
        }
    </style>
</head>
<body>
    <header>
        <h1>Financiamiento VITEZA - Venta de Autos</h1>
        <a href="tel:+527225928203" class="boton">Atención al Cliente</a>
    </header>
    <nav>
        <a href="https://www.facebook.com/share/bft2Pwwujd5NiWiA/?mibextid=qi2Omg" class="boton" target="_blank">Catálogo de Autos</a>
    </nav>
    <main>
        <section id="catalogo">
            <h2>Catálogo de Autos</h2>
            <p>Aquí puedes listar los autos disponibles para la venta, con detalles y fotos.</p>
            <a href="https://www.facebook.com/share/bft2Pwwujd5NiWiA/?mibextid=qi2Omg" class="boton" target="_blank">Ver Catálogo</a>
        </section>
        <section id="mision">
            <h2>Misión de Financiamiento VITEZA</h2>
            <p>Nuestra misión es proporcionar opciones accesibles de financiamiento para la adquisición de vehículos, asegurando la satisfacción y confianza de nuestros clientes.</p>
        </section>
        <section id="vision">
            <h2>Visión de Financiamiento VITEZA</h2>
            <p>Convertirnos en líderes en el sector automotriz, ofreciendo soluciones innovadoras y accesibles que mejoren la movilidad y la calidad de vida de nuestros clientes.</p>
        </section>
        <section id="valores">
            <h2>Valores de Financiamiento VITEZA</h2>
            <ul>
                <li>Transparencia</li>
                <li>Integridad</li>
                <li>Innovación</li>
                <li>Servicio al cliente</li>
            </ul>
        </section>
        <section id="informacion">
            <h2>Información del Cliente</h2>
            <table>
                <tr>
                    <th>Dato</th>
                    <th>Descripción</th>
                </tr>
                <tr>
                    <td>Nombre del Cliente</td>
                    <td><input type="text" id="nombre" name="nombre" required></td>
                </tr>
                <tr>
                    <td>Estado de Origen</td>
                    <td><input type="text" id="estado" name="estado" required></td>
                </tr>
                <tr>
                    <td>Unidad de Interés</td>
                    <td><input type="text" id="unidad" name="unidad" required></td>
                </tr>
                <tr>
                    <td>Capital de Inicio</td>
                    <td><input type="text" id="capital" name="capital" required></td>
                </tr>
            </table>
            <input type="submit" value="Enviar">
        </section>
        <section id="requisitos">
            <h2>Requisitos para Obtener Financiamiento</h2>
            <table>
                <tr>
                    <th>Requisito</th>
                    <th>Descripción</th>
                </tr>
                <tr>
                    <td>CURP</td>
                    <td>Clave Única de Registro de Población</td>
                </tr>
                <tr>
                    <td>Comprobante de Domicilio</td>
                    <td>Recibo reciente de luz, agua o teléfono</td>
                </tr>
                <tr>
                    <td>INE Vigente</td>
                    <td>Identificación Nacional Electoral (IFE o INE)</td>
                </tr>
                <tr>
                    <td>Referencias Personales</td>
                    <td>Dos referencias que no sean familiares directos y no vivan en la misma vivienda</td>
                </tr>
            </table>
        </section>
        <section id="horarios">
            <h2>Horarios de Atención</h2>
            <table>
                <tr>
                    <th>Día</th>
                    <th>Horario</th>
                </tr>
                <tr>
                    <td>Lunes a Viernes</td>
                    <td>10:00 A.M. - 6:00 P.M.</td>
                </tr>
                <tr>
                    <td>Sábado y Domingo</td>
                    <td>11:00 A.M. - 6:00 P.M.</td>
                </tr>
            </table>
        </section>
    </main>
    <footer>
        <p>&copy; 2024 Financiamiento VITEZA - Venta de Autos - Todos los derechos reservados.</p>
    </footer>
</body>
</html>
