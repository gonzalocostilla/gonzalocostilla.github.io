
<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Política de Privacidad de Future Gym - Aplicación de gestión para centros de fitness">
    <meta name="author" content="Future Gym">
    <title>Política de Privacidad - Future Gym</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: -apple-system, BlinkMacSystemFont, 'Segoe UI', Roboto, 'Helvetica Neue', Arial, sans-serif;
            line-height: 1.6;
            color: #333;
            background: linear-gradient(135deg, #000000 0%, #1a1a1a 50%, #000000 100%);
            min-height: 100vh;
            padding: 20px;
        }

        .container {
            max-width: 900px;
            margin: 0 auto;
            background: #ffffff;
            padding: 40px;
            border-radius: 12px;
            box-shadow: 0 10px 40px rgba(0, 0, 0, 0.3);
        }

        .header {
            text-align: center;
            margin-bottom: 40px;
            padding-bottom: 30px;
            border-bottom: 3px solid #2bacac;
        }

        .app-name {
            font-size: 36px;
            font-weight: 900;
            color: #2bacac;
            margin-bottom: 10px;
            letter-spacing: 1px;
        }

        .policy-title {
            font-size: 28px;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 15px;
        }

        .version-info {
            display: flex;
            justify-content: center;
            gap: 30px;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        .version-badge {
            background: #f5f5f5;
            padding: 8px 20px;
            border-radius: 20px;
            font-size: 14px;
            color: #666;
            border: 1px solid #e0e0e0;
        }

        .version-badge strong {
            color: #2bacac;
            font-weight: 600;
        }

        .content {
            margin-top: 30px;
        }

        .section {
            margin-bottom: 35px;
        }

        .section-title {
            font-size: 22px;
            font-weight: 700;
            color: #1a1a1a;
            margin-bottom: 15px;
            padding-bottom: 10px;
            border-bottom: 2px solid #2bacac;
        }

        .section-subtitle {
            font-size: 18px;
            font-weight: 600;
            color: #2bacac;
            margin-top: 20px;
            margin-bottom: 12px;
        }

        .paragraph {
            margin-bottom: 15px;
            text-align: justify;
            color: #444;
            font-size: 16px;
        }

        .highlight-box {
            background: linear-gradient(135deg, #e8f8f8 0%, #d4f1f1 100%);
            border-left: 4px solid #2bacac;
            padding: 20px;
            margin: 25px 0;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(43, 172, 172, 0.1);
        }

        .highlight-box p {
            font-weight: 600;
            color: #1a5555;
            margin: 0;
        }

        .warning-box {
            background: linear-gradient(135deg, #fff8e1 0%, #fff3cd 100%);
            border-left: 4px solid #f39c12;
            padding: 20px;
            margin: 25px 0;
            border-radius: 8px;
            box-shadow: 0 2px 8px rgba(243, 156, 18, 0.1);
        }

        .warning-box p {
            font-weight: 600;
            color: #8b6914;
            margin: 0;
        }

        .list {
            margin: 15px 0;
            padding-left: 0;
            list-style: none;
        }

        .list li {
            padding: 10px 0 10px 35px;
            position: relative;
            color: #444;
            font-size: 16px;
        }

        .list li:before {
            content: "✓";
            position: absolute;
            left: 0;
            top: 10px;
            color: #2bacac;
            font-weight: bold;
            font-size: 18px;
        }

        .rights-section {
            background: #f9f9f9;
            padding: 25px;
            border-radius: 8px;
            margin: 20px 0;
            border: 1px solid #e0e0e0;
        }

        .rights-title {
            font-size: 20px;
            font-weight: 700;
            color: #2bacac;
            margin-bottom: 15px;
        }

        .rights-list {
            margin: 0;
            padding-left: 0;
            list-style: none;
        }

        .rights-list li {
            padding: 12px 0 12px 40px;
            position: relative;
            color: #444;
            font-size: 16px;
            border-bottom: 1px solid #e8e8e8;
        }

        .rights-list li:last-child {
            border-bottom: none;
        }

        .rights-list li:before {
            content: "•";
            position: absolute;
            left: 15px;
            top: 12px;
            color: #2bacac;
            font-weight: bold;
            font-size: 24px;
        }

        .rights-list li strong {
            color: #2bacac;
            font-weight: 600;
        }

        .footer {
            margin-top: 50px;
            padding-top: 30px;
            border-top: 2px solid #e0e0e0;
            text-align: center;
        }

        .contact-info {
            background: #f5f5f5;
            padding: 20px;
            border-radius: 8px;
            margin-bottom: 20px;
        }

        .contact-info p {
            margin: 8px 0;
            color: #666;
            font-size: 15px;
        }

        .contact-info strong {
            color: #2bacac;
        }

        .contact-info a {
            color: #2bacac;
            text-decoration: none;
            font-weight: 600;
        }

        .contact-info a:hover {
            text-decoration: underline;
        }

        .footer-note {
            font-size: 14px;
            color: #999;
            margin-top: 20px;
        }

        /* Responsive */
        @media (max-width: 768px) {
            .container {
                padding: 25px;
            }

            .app-name {
                font-size: 28px;
            }

            .policy-title {
                font-size: 22px;
            }

            .section-title {
                font-size: 20px;
            }

            .version-info {
                flex-direction: column;
                align-items: center;
                gap: 10px;
            }
        }

        @media print {
            body {
                background: white;
                padding: 0;
            }

            .container {
                box-shadow: none;
                max-width: 100%;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <div class="header">
            <h1 class="app-name">Future Gym</h1>
            <h2 class="policy-title">Política de privacidad</h2>
            <div class="version-info">
                <span class="version-badge"><strong>Versión:</strong> 0.0.2</span>
                <span class="version-badge"><strong>Fecha efectiva:</strong> 1 de octubre de 2025</span>
            </div>
        </div>

        <div class="content">
            <!-- Sección 1 -->
            <div class="section">
                <h3 class="section-title">1. INTRODUCCIÓN</h3>
                <p class="paragraph">
                    La presente Política de Privacidad describe cómo la aplicación Future Gym gestiona y protege los datos personales de los usuarios de centros de fitness que utilizan la plataforma.
                </p>
            </div>

            <!-- Sección 2 -->
            <div class="section">
                <h3 class="section-title">2. ROL Y RESPONSABILIDAD</h3>
                <p class="paragraph">
                    Future Gym es un sistema desarrollado y administrado por Gonzalo Nicolás Costilla Vallés, desarrollador independiente, con domicilio en City Bell, Partido de La Plata, Provincia de Buenos Aires, Argentina.
                </p>
                <p class="paragraph">
                    Future Gym actúa como encargado del tratamiento de datos personales en nombre de los centros de fitness que utilizan la plataforma. Cada centro de fitness es el responsable principal de los datos de sus socios, ya que decide qué información se recolecta, cómo se utiliza y durante cuánto tiempo se conserva.
                </p>
            </div>

            <!-- Sección 3 -->
            <div class="section">
                <h3 class="section-title">3. DATOS TRATADOS Y FINALIDAD</h3>
                <p class="paragraph">
                    Al utilizar la aplicación, se recopilan, procesan y almacenan los siguientes datos personales del usuario:
                </p>

                <h4 class="section-subtitle">Datos de identificación:</h4>
                <ul class="list">
                    <li>Nombre y apellido</li>
                    <li>DNI</li>
                    <li>Teléfono</li>
                    <li>Teléfono de emergencia</li>
                    <li>Correo electrónico</li>
                    <li>Fecha de nacimiento</li>
                    <li>Sexo</li>
                </ul>

                <h4 class="section-subtitle">Datos de membresía:</h4>
                <ul class="list">
                    <li>Estado de cuota y pagos</li>
                    <li>Deudas pendientes</li>
                    <li>Fechas y horarios de acceso al centro de fitness</li>
                    <li>Turnos adquiridos</li>
                </ul>

                <h4 class="section-subtitle">Datos de entrenamiento y métricas:</h4>
                <ul class="list">
                    <li>Rutinas de entrenamiento</li>
                    <li>Progresos y evolución</li>
                    <li>Peso y altura</li>
                    <li>Medidas corporales</li>
                    <li>Registros de entrenamiento</li>
                </ul>

                <div class="warning-box">
                    <p>⚠️ Estos últimos se consideran datos sensibles, ya que permiten obtener información sobre su condición física. Su tratamiento se realiza únicamente con su consentimiento explícito, otorgado al momento de usar la aplicación.</p>
                </div>

                <h4 class="section-subtitle">Finalidad del tratamiento:</h4>
                <p class="paragraph">
                    Los datos recopilados se utilizan exclusivamente para:
                </p>
                <ul class="list">
                    <li>Permitir su acceso al centro de fitness mediante código QR, DNI o métodos alternativos.</li>
                    <li>Habilitar y gestionar la reserva de turnos o clases.</li>
                    <li>Mostrar el estado de su membresía, cuotas y pagos</li>
                    <li>Facilitar la visualización de sus entrenamientos, métricas y progresos físicos</li>
                    <li>Generar indicadores de rendimiento, como el Índice de Masa Corporal (IMC).</li>
                </ul>

                <div class="highlight-box">
                    <p>🔒 Future Gym no utiliza ni comparte estos datos con fines comerciales, publicitarios ni ajenos al funcionamiento del servicio.</p>
                </div>
            </div>

            <!-- Sección 4 -->
            <div class="section">
                <h3 class="section-title">4. ALMACENAMIENTO Y SEGURIDAD</h3>
                <p class="paragraph">
                    Los datos se almacenan en servidores gestionados por Future Gym, utilizando infraestructura de Google Cloud y Hostinger (Brasil) y AWS (Estados Unidos), proveedores que aplican altos estándares internacionales de seguridad y cifrado.
                </p>
                <p class="paragraph">
                    El acceso a la información está restringido al centro de fitness correspondiente y al desarrollador responsable del mantenimiento técnico. Se aplican medidas técnicas y organizativas adecuadas para prevenir accesos no autorizados, pérdida, alteración o divulgación indebida de los datos personales.
                </p>
            </div>

            <!-- Sección 5 -->
            <div class="section">
                <h3 class="section-title">5. TRANSFERENCIA INTERNACIONAL DE DATOS</h3>
                <p class="paragraph">
                    Debido al uso de proveedores tecnológicos externos, los datos pueden ser procesados o almacenados en servidores ubicados fuera del país, principalmente en Brasil y Estados Unidos. Al aceptar esta política, el usuario autoriza la transferencia internacional de sus datos personales, comprendiendo que estos proveedores garantizan niveles de protección y confidencialidad adecuados.
                </p>
            </div>

            <!-- Sección 6 -->
            <div class="section">
                <h3 class="section-title">6. DERECHOS DEL TITULAR DE LOS DATOS</h3>
                
                <div class="rights-section">
                    <h4 class="rights-title">Tus derechos</h4>
                    <ul class="rights-list">
                        <li><strong>Acceso:</strong> Podés solicitar información sobre los datos que tenemos</li>
                        <li><strong>Rectificación:</strong> Podés corregir datos incorrectos o desactualizados</li>
                        <li><strong>Cancelación:</strong> Podés solicitar la eliminación de su cuenta y los datos personales asociados que no sean obligatorios de conservar por ley o contrato.</li>
                        <li><strong>Oposición:</strong> Podés oponerte a que sus datos sean tratados para fines específicos, como el envío de comunicaciones no esenciales.</li>
                    </ul>
                </div>

                <ul class="list">
                    <li>Para datos vinculados a su identificación, membresía o entrenamiento, deberá comunicarse directamente con su centro de fitness, que es el responsable del tratamiento y conservación de dicha información.</li>
                    <li>Para eliminar su cuenta central de Future Gym (correo electrónico y lista de centros de fitness asociados), puede solicitarlo desde la aplicación o escribiendo a <a href="mailto:futureargentinaoficial@gmail.com">futureargentinaoficial@gmail.com</a>.</li>
                </ul>

                <p class="paragraph">
                    Una vez recibida la solicitud, Future Gym eliminará la cuenta central y los datos vinculados a ella en un plazo máximo de cinco (5) días hábiles.
                </p>
                <p class="paragraph">
                    Esta acción no implica la eliminación de la información almacenada por su centro de fitness, ya que pertenece a la relación contractual entre el usuario y esa entidad.
                </p>
            </div>

            <!-- Sección 7 -->
            <div class="section">
                <h3 class="section-title">7. CAMBIOS EN LA POLÍTICA DE PRIVACIDAD</h3>
                <p class="paragraph">
                    Future Gym podrá modificar esta Política de Privacidad en cualquier momento. Cualquier cambio sustancial será notificado a través de la aplicación o por correo electrónico, con un plazo razonable antes de su entrada en vigor.
                </p>
            </div>

            <!-- Sección 8 -->
            <div class="section">
                <h3 class="section-title">8. CONFORMIDAD</h3>
                <p class="paragraph">
                    Al aceptar esta Política de Privacidad, el usuario consiente el tratamiento de sus datos personales conforme a lo aquí establecido. Si no está de acuerdo con alguna parte de esta política, debe abstenerse de utilizar la aplicación.
                </p>
            </div>
        </div>

        <div class="footer">
            <div class="contact-info">
                <p><strong>Contacto:</strong></p>
                <p>Email: <a href="mailto:futureargentinaoficial@gmail.com">futureargentinaoficial@gmail.com</a></p>
                <p>Desarrollador: Gonzalo Nicolás Costilla Vallés</p>
                <p>Ubicación: City Bell, Partido de La Plata, Provincia de Buenos Aires, Argentina</p>
            </div>
            <p class="footer-note">
                Última actualización: 1 de octubre de 2025 • Versión 0.0.2
            </p>
        </div>
    </div>
</body>
</html>
