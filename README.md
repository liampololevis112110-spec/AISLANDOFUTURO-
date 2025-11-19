# AISLANDOFUTURO-
<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Aislando Futuro - Lana de Oveja Sustentable y Capacitación Integral</title>
<style>
    /* Reseteo y estilo base */
    body {
        font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
        margin: 0; padding: 0;
        background-color: #fafbf7;
        color: #284422;
        line-height: 1.7;
        font-size: 1.1em;
    }
    header {
        background: linear-gradient(90deg, #548c2f 0%, #34611d 100%);
        color: #f0f7e8;
        text-align: center;
        padding: 70px 25px 50px;
        box-shadow: 0 6px 20px rgba(34, 66, 16, 0.48);
    }
    header h1 {
        font-size: 3.8em;
        margin-bottom: 0.3em;
        letter-spacing: 3px;
        font-weight: 900;
    }
    header p {
        font-size: 1.5em;
        font-style: italic;
        margin-top: 0;
        font-weight: 600;
        letter-spacing: 1px;
    }
    nav {
        background-color: #3a5820;
        box-shadow: 0 2px 10px rgba(38,71,19,0.44);
        display: flex;
        justify-content: center;
        gap: 35px;
        padding: 18px 20px;
        font-weight: 700;
        font-size: 1.15em;
        flex-wrap: wrap;
    }
    nav a {
        color: #cbd7b5;
        text-decoration: none;
        border-radius: 6px;
        padding: 10px 16px;
        transition: background-color 0.3s ease-in-out;
    }
    nav a:hover, nav a.active {
        background-color: #5a8343;
        color: #f1f8dd;
    }
    main {
        max-width: 1280px;
        margin: 50px auto 80px;
        background: #fffbee;
        border-radius: 14px;
        box-shadow: 0 10px 30px rgba(22,62,8,0.18);
        padding: 60px 70px;
    }
    section {
        margin-bottom: 75px;
    }
    h2 {
        font-size: 2.8em;
        color: #42732f;
        border-bottom: 5px solid #5a8343;
        padding-bottom: 10px;
        letter-spacing: 2px;
        margin-bottom: 35px;
        font-weight: 800;
    }
    h3 {
        color: #36591f;
        font-weight: 800;
        font-size: 1.7em;
        margin-bottom: 18px;
        letter-spacing: 1.3px;
    }
    p, li {
        margin-bottom: 18px;
    }
    p.lead {
        font-size: 1.25em;
        font-weight: 600;
        color: #496531;
    }
    ul {
        margin-left: 25px;
        list-style-type: disc;
        max-width: 850px;
        column-count: 2;
        column-gap: 40px;
        font-weight: 600;
    }
    ul.beneficios, ul.cursos-lista {
        column-count: 1;
        max-width: 900px;
    }
    ul li {
        margin-bottom: 14px;
    }
    ul.cursos-lista li, ul.testimonios-lista li, ul.faq-lista li {
        padding: 15px 25px;
        border-left: 6px solid #5a8447;
        margin-bottom: 24px;
        background-color: #e1ebc2;
        border-radius: 12px;
        box-shadow: 0 2px 8px rgba(90,128,52,0.3);
        font-weight: 700;
        font-size: 1.13em;
    }
    .image-left, .image-right {
        width: 380px;
        max-width: 100%;
        border-radius: 14px;
        box-shadow: 0 6px 18px rgba(39, 69, 20, 0.25);
        object-fit: cover;
    }
    .image-right {
        float: right;
        margin-left: 40px;
        margin-bottom: 22px;
    }
    .image-left {
        float: left;
        margin-right: 40px;
        margin-bottom: 22px;
    }
    .clearfix::after {
        content: "";
        display: table;
        clear: both;
    }
    .producto-detalle {
        background-color: #f3f6dc;
        border-left: 7px solid #7bb24b;
        padding: 20px 28px;
        margin-bottom: 30px;
        border-radius: 12px;
        box-shadow: 0 3px 8px rgba(123,178,75,0.25);
        font-size: 1.15em;
    }
    .btn-primary {
        display: inline-block;
        background-color: #5a8343;
        color: white;
        font-weight: 700;
        padding: 14px 38px;
        font-size: 1.25em;
        border-radius: 12px;
        text-decoration: none;
        margin-top: 18px;
        transition: background-color 0.3s ease;
    }
    .btn-primary:hover {
        background-color: #7bb24b;
    }
    footer {
        background-color: #3f6023;
        color: white;
        text-align: center;
        padding: 28px 15px;
        font-size: 1em;
        letter-spacing: 1.1px;
        border-top: 4px solid #7bb24b;
        box-shadow: 0 -6px 28px rgba(19, 44, 10, 0.5);
    }
    form label {
        font-weight: 700;
        font-size: 1.09em;
        color: #446823;
        margin-top: 12px;
        display: block;
    }
    form input, form textarea, form select {
        border-radius: 8px;
        border: 2px solid #7bb24b;
        box-sizing: border-box;
        padding: 12px 18px;
        width: 100%;
        font-size: 1.1em;
        margin-top: 6px;
        resize: vertical;
        background-color: white;
    }
    form button {
        background-color: #5a8343;
        border: none;
        color: white;
        padding: 14px 28px;
        font-weight: 700;
        cursor: pointer;
        font-size: 1.2em;
        margin-top: 24px;
        border-radius: 10px;
        transition: background-color 0.3s;
    }
    form button:hover {
        background-color: #7bb24b;
    }
    .reseñas-container {
        max-width: 850px;
        margin: 0 auto;
        background-color: #e6f0d9;
        padding: 25px 40px;
        border-radius: 12px;
        box-shadow: 0 6px 18px rgba(90, 133, 72, 0.3);
    }
    .reseñas-lista {
        list-style: none;
        padding-left: 0;
        max-height: 380px;
        overflow-y: auto;
        border: 1px solid #5a8343;
        border-radius: 8px;
        margin-bottom: 30px;
        background-color: white;
    }
    .reseñas-lista li {
        border-bottom: 1px solid #c1d990;
        padding: 18px 22px;
        font-size: 1em;
        font-weight: 700;
    }
    .reseñas-lista li:last-child {
        border-bottom: none;
    }
    .reseña-autor {
        font-weight: 900;
        color: #5a8343;
        margin-bottom: 6px;
    }
    .star-rating {
        color: #f4b30a;
        font-size: 1.2em;
        margin-bottom: 8px;
    }
    @media (max-width: 1025px) {
        nav {
            flex-wrap: wrap;
            gap: 18px;
        }
        .image-right, .image-left {
            float: none;
            margin: 0 auto 24px;
            display: block;
            width: 85%;
        }
        main {
            padding: 40px 30px;
        }
        ul {
            column-count: 1;
        }
    }
    @media (max-width: 480px) {
        header h1 {
            font-size: 2.3em;
        }
        nav {
            font-size: 1em;
        }
        main {
            padding: 30px 20px;
        }
        h2 {
            font-size: 2em;
        }
        h3 {
            font-size: 1.3em;
        }
        ul.cursos-lista li, ul.testimonios-lista li {
            font-size: 1em;
            padding: 10px 16px;
        }
    }
</style>
</head>
<body>

<header>
    <h1>Aislando Futuro</h1>
    <p>Soluciones de Lana de Oveja Sustentable con Capacitación y Apoyo Integral</p>
</header>

<nav>
    <a href="#sobre-nosotros" class="active">Sobre Nosotros</a>
    <a href="#productos">Productos</a>
    <a href="#capacitaciones">Capacitaciones</a>
    <a href="#beneficios">Beneficios Cliente</a>
    <a href="#equipo">Nuestro Equipo</a>
    <a href="#proyectos">Proyectos</a>
    <a href="#testimonios">Testimonios</a>
    <a href="#blog">Blog</a>
    <a href="#faq">Preguntas Frecuentes</a>
    <a href="#reseñas">Reseñas</a>
    <a href="#contacto">Contacto</a>
</nav>

<main>
    <!-- Sobre Nosotros (idéntico a antes, omitido aquí para brevedad) -->
    <section id="sobre-nosotros" class="clearfix">
        <h2>Sobre Nosotros</h2>
        <img src="https://images.unsplash.com/photo-1516912482297-5c21ab2e3b03?auto=format&fit=crop&w=600&q=80" alt="Lana de oveja natural" class="image-right" />
        <p class="lead">
            En <strong>Aislando Futuro</strong> ofrecemos una alternativa sustentable innovadora para aislamiento térmico con lana de oveja 100% natural. Nuestra empresa nace del compromiso de cuidar el medio ambiente, aplicar tecnología de punta y promover eficiencia energética en la construcción.
        </p>
        <p>
            A diferencia de los aislantes convencionales, nuestra lana de oveja es un producto certificado por el Laboratorio IDIEM, que cumple estrictas normativas de calidad y protección ambiental, asegurando el máximo desempeño térmico, durabilidad y seguridad contra incendios.
        </p>
        <p>
            Como parte de nuestro servicio integral, además de entregar productos premium, brindamos capacitaciones certificadas para maximizar el uso correcto de la lana en tus proyectos, junto a asesoría técnica constante, garantizando una experiencia completa y satisfactoria para nuestros clientes.
        </p>
    </section>

    <!-- Productos -->
    <section id="productos" class="clearfix">
        <h2>Productos</h2>

        <div class="producto-detalle clearfix">
            <h3>Rollo Aislante Térmico Sustentable</h3>
            <img src="https://images.unsplash.com/photo-1486308510493-cb558a7fb7f0?auto=format&fit=crop&w=600&q=80" alt="Rollo de lana de oveja aislante" class="image-left"/>
            <p>
                <strong>Precio:</strong> $10.000 + IVA por metro cuadrado.<br>
                <strong>Dimensiones:</strong> 2,40 x 0,60 metros.<br>
                <strong>Conductividad térmica:</strong> 0,046 W/mK°.<br>
                <strong>Certificación:</strong> Producto certificado por el Laboratorio IDIEM.<br>
                <strong>Composición:</strong> 100% lana de oveja natural, material ignífugo y ecológico.<br>
                <strong>Instalación:</strong> Fácil y rápida, perfecta para techos, paredes y otras aplicaciones térmicas en edificaciones.
            </p>
            <h4>Beneficios Técnicos:</h4>
            <ul class="beneficios">
                <li><strong>Reducción de Consumo Energético:</strong> Aislar con lana de oveja reduce el consumo eléctrico y térmico entre 50% a 65%.</li>
                <li><strong>Protección al Fuego:</strong> Ignífugo y evita intoxicación por humo tóxico.</li>
                <li><strong>Menor Impacto Ambiental:</strong> Producción con bajas emisiones y consumo energético comparado con aislantes sintéticos.</li>
                <li><strong>Espesor Optimizado:</strong> Cumplimos normas ambientales con espesores estándar de 50 mm.</li>
                <li><strong>Aislamiento Termorregulado:</strong> Mantiene ambientes saludables controlando humedad y temperatura.</li>
                <li><strong>Durabilidad:</strong> Garantiza prolongada vida útil del edificio.</li>
            </ul>
        </div>

        <div class="producto-detalle clearfix">
            <h3>Presentación a Granel para Proyectos a Gran Escala</h3>
            <img src="https://images.unsplash.com/photo-1514432324607-a09d9fca96de?auto=format&fit=crop&w=600&q=80" alt="Lana de oveja a granel" class="image-right"/>
            <p>
                <strong>Precio:</strong> $9.000 + IVA por m2.<br>
                <strong>Uso:</strong> Ideal para grandes construcciones, relleno térmico ecológico y proyectos especiales.<br>
                <strong>Características:</strong> Producto natural, ignífugo y de alta eficiencia térmica.
            </p>
            <p>Nuestro material a granel permite adaptabilidad y aplicación personalizada según requerimientos del proyecto, fomentando la sustentabilidad y el ahorro energético en edificaciones comerciales e industriales.</p>
        </div>

        <h3>Accesorios y Complementos</h3>
        <p>Complementa la instalación con fijaciones ecológicas, cintas adhesivas y sistemas de sellado diseñados para lana de oveja que garantizan hermeticidad y durabilidad completa. Consulta a nuestro equipo de asesores.</p>
    </section>

    <!-- Capacitaciones -->
    <section id="capacitaciones">
        <h2>Capacitaciones</h2>
        <p>
            En <strong>Aislando Futuro</strong> nos preocupamos porque nuestros clientes aprovechen al máximo el potencial de la lana de oveja. Por eso diseñamos un programa amplio, flexible y certificado que cubre desde fundamentos hasta técnicas avanzadas.
        </p>

        <h3>Oferta formativa</h3>
        <ul class="cursos-lista">
            <li><strong>Curso Básico:</strong> Introducción a la lana de oveja, propiedades físicas y térmicas, impacto ambiental y ventajas frente a aislantes tradicionales. Duración: 5 horas presenciales o en línea.</li>
            <li><strong>Curso Intermedio:</strong> Preparación del espacio, selección de materiales, herramientas necesarias y procedimientos paso a paso de instalación. Modalidad presencial, 8 horas.</li>
            <li><strong>Curso Avanzado:</strong> Técnicas especializadas para instalaciones en estructuras complejas, control de calidad, seguridad y normativas vigentes. Incluye prácticas certificadas. Duración: 12 horas.</li>
            <li><strong>Seminario sobre Sustentabilidad:</strong> Enfoques ecológicos, certificaciones verdes y tendencias mundiales en aislantes naturales. Modalidad webinar, 3 horas.</li>
            <li><strong>Taller de Innovación en Construcción Sostenible:</strong> Caso de estudio y desarrollo de proyectos con lana de oveja y otros biomateriales. Intensivo 2 días.</li>
            <li><strong>Curso de Capacitación para Instructores:</strong> Para profesionales que desean impartir capacitaciones propias y estar certificados por Aislando Futuro.</li>
        </ul>

        <h3>¿Qué aprenderás?</h3>
        <ul>
            <li>Técnicas de preparación e instalación profesional.</li>
            <li>Diagnóstico de problemas térmicos y soluciones con lana de oveja.</li>
            <li>Normativas actuales y beneficios de certificaciones.</li>
            <li>Cómo integrar la lana en proyectos arquitectónicos y de construcción sostenible.</li>
            <li>Procedimientos para maximizar ahorro energético y confort.</li>
        </ul>

        <p>
            Todos los cursos incluyen material didáctico digital, certificación oficial y acceso a nuestro servicio de asesoría exclusiva para resolver dudas durante y después del curso.
        </p>
    </section>

    <!-- Beneficios -->
    <section id="beneficios">
        <h2>Beneficios al ser Cliente</h2>

        <p>Además de acceder a un producto premium y ecológico, nuestros clientes disfrutan de múltiples beneficios exclusivos:</p>

        <ul class="beneficios">
            <li><strong>15% de descuento</strong> en el total de tu boleta en Sodimac en compras relacionadas con aislamiento y construcción.</li>
            <li>Participación gratuita en capacitaciones y talleres.</li>
            <li>Acceso prioritario a nuevos lanzamientos y productos innovadores.</li>
            <li>Asesoría técnica personalizada durante todo el proceso: compra, instalación y mantenimiento.</li>
            <li>Descuentos exclusivos en servicios asociados, como instalación profesional y consultoría energética.</li>
            <li>Material educativo actualizado y soporte técnico permanente.</li>
            <li>Participación en programas de fidelización con regalos, incentivos y reconocimientos.</li>
            <li>Garantía extendida de hasta 10 años por compra directa.</li>
        </ul>

        <blockquote style="background:#d8ebbb; padding:20px; border-left: 7px solid #7bb24b; margin-top: 40px; font-style: italic;">
            "Gracias a Aislando Futuro, logramos reducir considerablemente nuestra factura energética y mejorar el confort térmico en nuestra casa. Su capacitación y asesoría hicieron la diferencia." – <strong>Carolina M., Santiago</strong>
        </blockquote>
    </section>

    <!-- Equipo -->
    <section id="equipo">
        <h2>Nuestro Equipo</h2>
        <p>Somos un grupo multidisciplinario de profesionales apasionados por la sustentabilidad y la construcción eficiente.</p>
        <div style="display: flex; gap: 50px; flex-wrap: wrap; justify-content: center;">
            <div style="flex-basis: 300px; text-align: center;">
                <img src="https://images.unsplash.com/photo-1544005313-94ddf0286df2?auto=format&fit=crop&w=300&q=80" alt="Equipo técnico" style="border-radius: 14px; width: 100%; box-shadow: 0 5px 15px rgba(38,71,19,0.3);" />
                <h3>Paz Osorio</h3>
                <p>Ingeniero Civil y Director Técnico</p>
            </div>
            <div style="flex-basis: 300px; text-align: center;">
                <img src="https://images.unsplash.com/photo-1508214751196-bcfd4ca60f91?auto=format&fit=crop&w=300&q=80" alt="Equipo capacitación" style="border-radius: 14px; width: 100%; box-shadow: 0 5px 15px rgba(38,71,19,0.3);" />
                <h3>María López</h3>
                <p>Coordinadora de Capacitaciones</p>
            </div>
            <div style="flex-basis: 300px; text-align: center;">
                <img src="https://images.unsplash.com/photo-1507003211169-0a1dd7228f2d?auto=format&fit=crop&w=300&q=80" alt="Equipo atención cliente" style="border-radius: 14px; width: 100%; box-shadow: 0 5px 15px rgba(38,71,19,0.3);" />
                <h3>Alejandro Cáceres</h3>
                <p>Asesor Comercial y Postventa</p>
            </div>
        </div>
    </section>

    <!-- Proyectos -->
    <section id="proyectos">
        <h2>Proyectos Destacados</h2>
        <p>Estos son algunos proyectos reales donde la lana de oveja aportó innovación, eficiencia energética y sustentabilidad.</p>

        <div style="margin-top:30px;">
            <h3>Condominio Ecológico "Verde Vivo" - Temuco</h3>
            <img src="https://images.unsplash.com/photo-1506744038136-46273834b3fb?auto=format&fit=crop&w=600&q=80" alt="Proyecto Verde Vivo" style="width: 100%; max-width: 800px; border-radius: 14px; box-shadow: 0 5px 17px rgba(89,129,56,0.3); margin-bottom: 18px;"/>
            <p>
                Instalamos rollos de aislamiento térmico de lana de oveja en 45 viviendas, logrando una reducción promedio del consumo energético del 60%. Los propietarios reportaron ambientes más confortables y menor dependencia de calefacción externa.
            </p>
        </div>

        <div style="margin-top:40px;">
            <h3>Escuela Sostenible "Alma Verde" - Valdivia</h3>
            <img src="https://images.unsplash.com/photo-1494526585095-c41746248156?auto=format&fit=crop&w=600&q=80" alt="Escuela Alma Verde" style="width: 100%; max-width: 800px; border-radius: 14px; box-shadow: 0 5px 17px rgba(89,129,56,0.3); margin-bottom: 18px;"/>
            <p>
                En un proyecto junto a la municipalidad, aislamos las aulas y oficinas con lana de oveja natural, mejorando notablemente el confort térmico y acústico, beneficiando a más de 600 estudiantes. Además, formamos al personal de mantenimiento con nuestras capacitaciones.
            </p>
        </div>
    </section>

    <!-- Testimonios -->
    <section id="testimonios">
        <h2>Testimonios de Clientes</h2>
        <ul class="testimonios-lista">
            <li>
                "La calidad del producto y el acompañamiento de Aislando Futuro excedieron nuestras expectativas. Un servicio humano y profesional." – <strong>Bastián López.</strong>
            </li>
            <li>
                "Los cursos fueron muy claros, aprendí desde cero cómo instalar la lana de oveja en los proyectos que lidero, y el ahorro energético ha sido real." – <strong>Aylin Pincheira.</strong>
            </li>
            <li>
                "Muy contentos por la durabilidad y aislamiento termorregulado. Además, tener apoyo siempre disponible hizo la diferencia." – <strong>Corporación Edificios Verdes</strong>
            </li>
        </ul>
    </section>

    <!-- Blog -->
    <section id="blog">
        <h2>Blog y Noticias</h2>
        <article style="margin-bottom: 40px;">
            <h3>¿Por qué elegir materiales naturales en construcción?</h3>
            <p>Los materiales como la lana de oveja aportan no solo eficiencia sino también salud y reducción de la huella ambiental...</p>
            <a href="#" class="btn-primary">Leer Más</a>
        </article>
        <article style="margin-bottom: 40px;">
            <h3>Nuevas Normativas Ambientales: Impacto en el Aislamiento</h3>
            <p>Conoce las últimas regulaciones y cómo nuestra lana de oveja cumple y supera los estándares requeridos...</p>
            <a href="#" class="btn-primary">Leer Más</a>
        </article>
        <article>
            <h3>Cómo integrar capacitación y producto para proyectos exitosos</h3>
            <p>La diferencia que marca una buena capacitación en la ejecución y el rendimiento de los aislantes naturales...</p>
            <a href="#" class="btn-primary">Leer Más</a>
        </article>
    </section>

    <!-- FAQ -->
    <section id="faq">
        <h2>Preguntas Frecuentes (FAQs)</h2>
        <ul class="faq-lista">
            <li><strong>¿La lana de oveja es resistente al agua o humedad?</strong><br> Aunque la lana no es impermeable, su capacidad para regular la humedad ayuda a prevenir condensaciones y deterioro estructural.</li>
            <li><strong>¿Qué diferencia hay entre la lana de oveja y otros aislantes?</strong><br> La lana es renovable, natural y con alta capacidad térmica y acústica, además de ser ignífuga y saludable para los ambientes.</li>
            <li><strong>¿Se puede instalar en viviendas existentes?</strong><br> Sí, tenemos soluciones técnicas para adaptación y retrofitting en hogares y edificios preexistentes.</li>
            <li><strong>¿Los cursos son presenciales o online?</strong><br> Ofrecemos ambas modalidades para facilitar el acceso a todos nuestros clientes.</li>
            <li><strong>¿Es necesario usar herramientas especiales para la instalación?</strong><br> No, las instalaciones son sencillas con herramientas básicas y nuestras capacitaciones enseñan los métodos más eficientes.</li>
        </ul>
    </section>

    <!-- Reseñas de Clientes -->
    <section id="reseñas">
        <h2>Deja tu Reseña</h2>
        <p>Tu opinión es muy valiosa para nosotros y para ayudar a futuros clientes a tomar la mejor decisión. Completa el formulario y déjanos tu experiencia con <strong>Aislando Futuro</strong>.</p>

        <div class="reseñas-container">
            <ul id="lista-reseñas" class="reseñas-lista">
                <!-- Reseñas enviadas aparecerán aquí dinámicamente -->
            </ul>

            <form id="form-reseñas" onsubmit="return agregarReseña(event)">
                <label for="autor">Nombre</label>
                <input type="text" id="autor" name="autor" placeholder="Tu nombre" required minlength="3" />

                <label for="emailR">Correo electrónico (no será publicado)</label>
                <input type="email" id="emailR" name="emailR" placeholder="ejemplo@correo.com" required />

                <label for="rating">Calificación</label>
                <select id="rating" name="rating" required>
                    <option value="" disabled selected>Selecciona</option>
                    <option value="5">★★★★★ - Excelente</option>
                    <option value="4">★★★★ - Muy bueno</option>
                    <option value="3">★★★ - Bueno</option>
                    <option value="2">★★ - Regular</option>
                    <option value="1">★ - Malo</option>
                </select>

                <label for="comentario">Comentario</label>
                <textarea id="comentario" name="comentario" placeholder="Escribe tu reseña aquí" required minlength="15" rows="5"></textarea>

                <button type="submit">Enviar Reseña</button>
            </form>
        </div>
    </section>

    <!-- Contacto -->
    <section id="contacto">
        <h2>Contacto</h2>
        <p>Estamos para ayudarte. Para cotizaciones, consultas o agendar nuestras capacitaciones, contáctanos:</p>
        <p style="font-weight: 900; font-size: 1.4em; margin: 10px 0;">📞 Teléfono / WhatsApp: <strong>+56 9 3497 0831</strong></p>
        <p style="font-weight: 900; font-size: 1.2em; margin: 10px 0;">✉️ Email: <strong>contacto@aislandofuturo.com</strong></p>

        <form id="contactForm" onsubmit="return validarFormulario()" style="max-width:650px; margin: 40px auto 0;">
            <label for="nombreC">Nombre completo</label>
            <input type="text" id="nombreC" name="nombreC" required minlength="3" placeholder="Tu nombre completo" />
            
            <label for="emailC" style="margin-top: 20px;">Correo electrónico</label>
            <input type="email" id="emailC" name="emailC" required placeholder="ejemplo@correo.com" />

            <label for="telefonoC" style="margin-top: 20px;">Teléfono (opcional)</label>
            <input type="tel" id="telefonoC" name="telefonoC" placeholder="+56 9 1234 5678" />

            <label for="mensajeC" style="margin-top: 20px;">Mensaje</label>
            <textarea id="mensajeC" name="mensajeC" required minlength="15" rows="7" placeholder="Escribe tu consulta o comentario aquí"></textarea>
            
            <button type="submit">Enviar Mensaje</button>
        </form>
    </section>
</main>

<footer>
    <p>© 2025 Aislando Futuro - Todos los derechos reservados</p>
    <p>Contacto: contacto@aislandofuturo.com | +56 9 3497 0831</p>
    <p>Desarrollado con pasión por un futuro sustentable</p>
</footer>

<script>
    // Validación para formulario de contacto principal
    function validarFormulario() {
        const nombre = document.getElementById('nombreC').value.trim();
        const email = document.getElementById('emailC').value.trim();
        const mensaje = document.getElementById('mensajeC').value.trim();
        const emailRegex = /^[^\s@]+@[^\s@]+\.[^\s@]+$/;

        if (nombre.length < 3) {
            alert('Por favor, ingresa un nombre válido con al menos 3 caracteres.');
            document.getElementById('nombreC').focus();
            return false;
        }
        if (!emailRegex.test(email)) {
            alert('Por favor, ingresa un correo electrónico válido.');
            document.getElementById('emailC').focus();
            return false;
        }
        if (mensaje.length < 15) {
            alert('El mensaje debe tener al menos 15 caracteres.');
            document.getElementById('mensajeC').focus();
            return false;
        }
        alert('Mensaje enviado correctamente. Nos pondremos en contacto pronto.');
        return true;
    }

    // Reseñas dinámicas
    const listaReseñas = document.getElementById('lista-reseñas');
    const formReseñas = document.getElementById('form-reseñas');

    function agregarReseña(event) {
        event.preventDefault();

        const autor = document.getElementById('autor').value.trim();
        const emailR = document.getElementById('emailR').value.trim();
        const rating = parseInt(document.getElementById('rating').value);
        const comentario = document.getElementById('comentario').value.trim();

        if (!autor || !emailR || !rating || comentario.length < 15) {
            alert('Por favor completa todos los campos correctamente (comentario mínimo 15 caracteres).');
            return false;
        }

        // Crear nueva reseña en HTML
        const li = document.createElement('li');

        const estrellas = '★'.repeat(rating) + '☆'.repeat(5 - rating);
        li.innerHTML = `<div class="star-rating" aria-label="Calificación: ${rating} estrellas">${estrellas}</div>
                        <div class="reseña-autor">${autor}</div>
                        <div class="reseña-texto">${comentario}</div>`;

        // Insertar reseña al inicio de la lista
        listaReseñas.insertBefore(li, listaReseñas.firstChild);

        // Limpiar formulario
        formReseñas.reset();
        alert('Gracias por tu reseña, ha sido agregada.');

        return true;
    }
</script>

</body>
</html>
