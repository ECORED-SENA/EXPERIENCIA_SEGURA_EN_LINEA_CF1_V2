<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5.mb-5
    .titulo-principal.color-acento-contenido(data-aos="flip-up")
      .titulo-principal__numero
        span 1
      h1 Ciberseguridad
    
    h3(data-aos="slide-right").mb-3 ¿Qué es la ciberseguridad?
    p.mb-5(data-aos="slide-right") Cano, J (2011), nos dice que es:
    .row.justify-content-center.mb-5(data-aos="zoom-in-up")
      .col-lg-10
        .bloque-texto-f.bg__1-claro.py-5.px-5.mb-5
          .bloque-texto-f__comillas
            i.fas.fa-quote-left
            i.fas.fa-quote-right
          h4.text-regular.bloque-texto-f__texto.text-center El conjunto de herramientas, políticas, conceptos de seguridad, salvaguardas de seguridad, directrices, métodos de gestión de riesgos, acciones, formación, prácticas idóneas, seguros y tecnologías que pueden utilizarse para proteger los activos de la organización y los usuarios en el ciberentorno.
            br
            br
            |Y también incluye activos, bienes, servicios y datos de los dispositivos y usuarios conectados a una red; adicionalmente Cano (2011) agrega, que se pueden contar los servicios/aplicaciones, los sistemas de comunicaciones, las comunicaciones multimedios, y la totalidad de la información transmitida y/o almacenada en el ciberentorno en búsqueda de mantener las propiedades de seguridad en todos estos elementos de cualquier organización o persona sin importar cuál sea la red que frecuenta, su edad, su entorno y su uso.
          .bloque-texto-f__avatar
            .bloque-texto-f__avatar__img
              img(src='@/assets/curso/1.svg', alt='Texto que describa la imagen')
    .row.mb-5.align-items-end
      .col-lg-7(data-aos="slide-right"): img(src='@/assets/curso/2.svg' alt="¿Sabía que en los últimos años el concepto de ciberseguridad se ha convertido en un estándar y en una necesidad en todas las organizaciones?")
      .col-lg-5(data-aos="slide-left")
        p.mb-0 Esto se da porque cada vez más y con mayor frecuencia se recurre al uso de las tecnologías de la información y las comunicaciones para apalancar los procesos operativos junto con las propuestas de valor de los negocios. 
          br
          br
          |El desarrollo y evolución de la tecnología nos lleva a hacer uso de servicios como Internet, la interconexión entre sedes y con mayor frecuencia la utilización de tecnologías de computación en la nube.
    p.mb-5 Las redes sociales y en general el Internet, hacen totalmente necesario proteger toda la información que se gestiona al ingresar en cualquiera de estos recursos digitales, solo de esa forma se pueden mantener monitoreadas las amenazas de las cuales se puede ser víctima.
      br
      br
      |Protegerse de los peligros de la actual coyuntura tecnológica, conlleva a diseñar y adoptar una serie de procesos que posibiliten la protección de los activos, recursos e información personal y empresarial de todos los seres digitales y para ello se recomienda la aplicación de las siguientes fases como paso inicial:
    .row.mb-5.justify-content-center(data-aos="zoom-in-up")
      .col-lg-10
        PasosA.color-acento-contenido.mb-5(tipo="n")
          .row
            .col-md-6.mb-4.mb-md-0
              h4 Prevención
              p Esta es la primera fase que ayudará de manera significativa en la disminución de los riesgos, actuar de manera temprana implica conocer los activos o recursos tecnológicos más usados y realizar un análisis de las posibles amenazas junto con la forma en que se previenen o contrarrestan, esta fase es de gran importancia para generar conciencia, preparar y capacitar a los usuarios y de esta forma disminuir el número de errores que ocurren por desconocimiento, recuerde siempre que una buena prevención es la mejor defensa.
            .col-md-6
              figure
                img(src='@/assets/curso/3.svg', alt='Texto que describa la imagen')
          .row
            .col-md-6
              figure
                img(src='@/assets/curso/4.svg', alt='Texto que describa la imagen')
            .col-md-6.mb-4.mb-md-0
              h4 Localización
              p Luego de prevenir los esfuerzos, se continúa con la adquisición e implementación de una serie de herramientas tecnológicas que generen una alerta en algún tipo de incidente, para localizar su fuente y afectación, con el fin de tomar las acciones correctivas a que dieran lugar.
                br
                br
                |Esto se logra cuando las medidas y herramientas empleadas están haciendo un constante monitoreo y gestión sobre los recursos tecnológicos. Normalmente, cuando se detectan los incidentes, estos ya han ocurrido muchos días antes, esto es debido a que los delincuentes cada vez utilizan más herramientas y estrategias que dificultan su detección, de ahí la importancia de una constante monitorización sobre los recursos y servicios tecnológicos.

          .row
            .col-md-12.mb-4.mb-md-0
              h4 Reacción
              p Una vez se detecte una posible amenaza se debe realizar una reacción inmediata que permita su mitigación, para esto se recomienda seguir los siguientes pasos:
              .contenedor-tarjetas.justify-content-center(data-aos="zoom-in-down")
                .tarjeta-degrade.p-4.align-items-center.m-1
                  img(src='@/assets/curso/6.svg').mx-3
                  p.fw-bold Desconectar los activos de la red que están siendo afectados.
                .tarjeta-degrade.p-4.align-items-center.m-1
                  img(src='@/assets/curso/7.svg').mx-3
                  p.fw-bold Actualizar los sistemas de protección implementados, como antivirus, #[em antimalware], #[em antispyware], entre otras estrategias implementadas en la organización.
                .tarjeta-degrade.p-4.align-items-center.m-1
                  img(src='@/assets/curso/8.svg').mx-3
                  p.fw-bold Realizar un análisis exhaustivo sobre los sistemas o servicios afectados a fin de detectar el origen y afectación.
                .tarjeta-degrade.p-4.align-items-center.m-1
                  img(src='@/assets/curso/9.svg').mx-3
                  p.fw-bold Cambiar todas las contraseñas.
                .tarjeta-degrade.p-4.align-items-center.m-1
                  img(src='@/assets/curso/10.svg').mx-3
                  p.fw-bold Realizar una limpieza profunda de los recursos tecnológicos con las herramientas con que se cuente.
    
    Separador
    #t_1_1.titulo-segundo(data-aos="fade-right")
      h2 1.1 Marcos de referencia
    p.mb-5 Los ataques cibernéticos son cada vez más comunes y frecuentes, como se mencionó anteriormente, debido a la inmersión de la tecnología en todos los procesos, tanto personales como empresariales; es clara la necesidad de protección en recursos, información y activos, sin embargo, el inicio puede ser lejano y para eso se hace el siguiente planteamiento:
    .row.mb-5.align-items-center
      .col-lg-7(data-aos="slide-right"): img(src='@/assets/curso/11.svg')
      .col-lg-5(data-aos="slide-left")
        p.mb-0 Es ahí donde cobran importancia los marcos de referencia que se han venido desarrollando, porque con la adopción de estos marcos se tendrá clara y en orden, toda la información de valor y útil en el diseño de las estrategias de control y mitigación de riesgos de ciberseguridad.
    p.mb-5 Si bien se debe elegir un marco y trabajar con él, son solo una referencia y no una solución definitiva porque también es importante el enfoque del análisis de riesgos del cual se dará información más adelante. Son varios marcos, cada marco propone una serie de controles diferentes. Se debe elegir por su parte el marco indicado aplicable a su entorno y si se llegase a requerir algún ajuste se puede importar de alguno de los otros marcos y generar su propio marco de seguridad, es así como funciona esta información que con su prudente apropiación logra protección alta.
      br
      br
      |A continuación, se mencionan los marcos de referencia más utilizados y de mayor desarrollo, incluyendo algunos propósitos particulares para su adopción.
    
    .titulo-sexto.color-acento-botones.d-flex.align-items-center(data-aos="fade-right")
      .titulo-principal__numero.p-3
        span.text-white.h5 1
      h5 El primer marco es el dispuesto desde Norteamérica como CSF (#[em Cybersecurity Framework])
    
    .tarjeta.tarjeta--azul.p-4.mb-5(data-aos="zoom-in-up")
      SlyderA
        .row.justify-content-center.p-3
          .col-md-11
            .row
              .col-md-6.mb-4.mb-md-0
                h4 NIST CSF (#[em National Institute of Standards and Technology - Cybersecurity Framework]) - Marco de Ciberseguridad del Instituto Nacional de Estándares y Tecnología.
                p Este marco establece una guía en la que cualquier empresa pueda recibir, comprender, administrar y reducir los riesgos cibernéticos junto con sus redes y datos. Este marco permite la comprensión del lenguaje común y enfoca buenas prácticas en ciberseguridad.
                  br
                  br
                  |El Instituto Nacional de Normas y Tecnología (NIST), una agencia perteneciente al Departamento de Comercio de los Estados Unidos, desarrolló este marco, el cual utiliza un lenguaje cómodo que guía a las compañías en general, a gestionar algún impacto negativo de seguridad digital y así fortalecer la información.
              .col-md-6
                figure
                  img(src='@/assets/curso/12.svg', alt='Texto que describa la imagen')
        .row.justify-content-center.p-3
          .col-md-11
            .row.p-3.align-items-center
              .col-md-6.mb-4.mb-md-0
                p Este marco no provee nuevas estructuras, más funciones de ciberseguridad, ni incrementa categorías, solo reúne las mejores prácticas conocidas al respecto como lo son ISO, ITU, CIS, NIST, entre otros; y las agrupa según afinidad. Se centra en el uso de lanzadores para guiar las actividades de seguridad digital de las empresas considerando los riesgos de la información como parte importante en la gestión de los riesgos.
              .col-md-6
                figure
                  img(src='@/assets/curso/13.svg', alt='Imagen que presenta las mejores prácticas, como son: Identificar. Comprender el contexto, conocer los datos, los activos y los riesgos.Proteger. Aplicación de controles (técnicos, políticas, procesos) para mitigar riesgos.Detectar. Monitoreo y control.Responder. Reducir el impacto de un impacto potencial.Recuperar. Resiliencia y recuperación ante incidentes.')
        .row.justify-content-center.p-3
          .col-md-11
            .row.p-3.align-items-end
              .col-md-6.mb-4.mb-md-0
                p El #[em Framework] Core comprende un conjunto de actividades de ciberseguridad, resultados y referencias informativas que son comunes a través de los sectores de infraestructura crítica. Así, proporciona la orientación detallada para el desarrollo de perfiles individuales de la compañía. Mediante el uso de los perfiles, el marco ayudará a la organización a alinear sus actividades de ciberseguridad con sus requisitos de negocio, tolerancias de riesgo y recursos. Por su parte, los niveles de implementación del marco (#[em tiers]) proporcionan un mecanismo para que las empresas puedan ver y comprender las características de su enfoque para la gestión del riesgo de ciberseguridad.
              .col-md-6
                figure
                  img(src='@/assets/curso/14.jpg', alt='Texto que describa la imagen')
        .row.justify-content-center.p-3
          .col-md-11
            div.p-3
              p.mb-4 Las bases del marco CSF son:
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#0077EC;")
                    figure
                      img(src="@/assets/curso/79.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
                    strong.pe-3 01
                    p.mb-0 Identificar estándares de seguridad y guías aplicables de forma trasversal a todos los sectores de infraestructuras críticas.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#03E6B0;")
                    figure
                      img(src="@/assets/curso/80.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
                    strong.pe-3 02
                    p.mb-0 Establecer un lenguaje común para gestionar riesgos de ciberseguridad.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#0077EC;")
                    figure
                      img(src="@/assets/curso/79.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
                    strong.pe-3 03
                    p.mb-0 Proveer un enfoque priorizado, flexible, repetible, neutral, basado en desempeño y efectivo en términos de coste-beneficio basado en las necesidades del negocio.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#03E6B0;")
                    figure
                      img(src="@/assets/curso/80.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
                    strong.pe-3 04
                    p.mb-0 Ayudar a los responsables y operadores de infraestructuras críticas a identificar, inventariar y gestionar riesgos informáticos.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#0077EC;")
                    figure
                      img(src="@/assets/curso/79.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
                    strong.pe-3 05
                    p.mb-0 Establecer criterios para la definición de métricas para el control del desempeño en la implementación.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#03E6B0;")
                    figure
                      img(src="@/assets/curso/80.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
                    strong.pe-3 06
                    p.mb-0 Establecer controles para proteger la propiedad intelectual, la privacidad de los individuos y las libertades civiles cuando se ejecuten actividades de ciberseguridad.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#0077EC;")
                    figure
                      img(src="@/assets/curso/79.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
                    strong.pe-3 07
                    p.mb-0 Identificar áreas de mejora que permitan ser gestionadas a través de colaboraciones futuras con sectores particulares y organizaciones orientadas al desarrollo de estándares.
              .row
                .col-auto.pe-0
                  .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#03E6B0;")
                    figure
                      img(src="@/assets/curso/80.svg")
                .col.ps-0
                  .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
                    strong.pe-3 08
                    p.mb-0 No introducir nuevos estándares cuando existan iniciativas ya desarrolladas que cubran los objetivos de la orden ejecutiva.
                
        .row.justify-content-center.p-3
          .col-md-11
            .row.p-3
              .col-md-6.col-lg-5.mb-4.mb-md-0
                p De acuerdo con el NIST (s.f) “el marco de trabajo es una guía voluntaria, basada en estándares, directrices y prácticas existentes para que las organizaciones de infraestructura crítica gestionen mejor y reduzcan el riesgo de ciberseguridad. Además, se diseñó para fomentar las comunicaciones de gestión del riesgo y la seguridad cibernética entre los interesados internos y externos de la organización“. Eso quiere decir que los objetivos del marco de trabajo en su implementación en una organización se podrían catalogar en los siguientes puntos:
                h5 Todo esto enmarcado en un enfoque orientado a la gestión del riesgo.
              .col-md-6.col-lg-7
                figure
                  img(src='@/assets/curso/16.svg', alt='Imagen que presenta los puntos a tener en cuenta en la implementación de los objetivos del marco de trabajo en una organización.')
    
    .titulo-sexto.color-acento-botones.d-flex.align-items-center(data-aos="fade-right")
      .titulo-principal__numero.p-3
        span.text-white.h5 2
      h5 El siguiente marco es el que presenta ISO denominado ISO / IEC 27001: 2013.
    p.mb-5 Creado y publicado por la Organización Internacional de Normalización (ISO), es un marco general que funciona bien para empresas de diversos tamaños en una variedad de industrias. Es similar al NIST CSF. El marco es respetado y ampliamente conocido internacionalmente. El enfoque de ISO 27001 es la protección de la confidencialidad, integridad y disponibilidad de la información en una empresa. Su filosofía se basa en la gestión de riesgos: investigar dónde están y luego tratarlos de manera sistemática tal como se presenta en la siguiente gráfica:
    .titulo-sexto.color-acento-contenido
      h5 Figura 1.
      span ISO / IEC 27001: 2013
    figure(data-aos="zoom-in-up")
      img(src='@/assets/curso/17.svg', alt='Imagen que presenta el marco que presenta ISO denominado ISO / IEC 27001: 2013.')
    br
    br
    .titulo-sexto.color-acento-botones.d-flex.align-items-center(data-aos="fade-right")
      .titulo-principal__numero.p-3
        span.text-white.h5 3
      h5 En tercer lugar se ubica la famosa COBIT que traduce Objetivos de Control para Información y Tecnologías Relacionadas. Proveniente del inglés <i>Control Objectives for Information and related Technology</i>.
    p.mb-5 #[strong COBIT] fue desarrollado por ISACA, una organización global independiente sin fines de lucro, que se enfoca en el gobierno de TI (Tecnologías de la Información). Este marco es similar al marco de NIST e ISO, porque es un marco más general que la mayoría de las organizaciones pueden usar. También está enfocado en el negocio y orientado a procesos. COBIT a menudo es adoptado por auditores de empresas públicas y se utiliza como una herramienta de cumplimiento para Sarbanes-Oxley.
      br
      br
      |Es una guía de mejores prácticas, dirigida al control y supervisión de TI. Cuenta con una serie de recursos que pueden servir de modelo de referencia para la gestión de TI, incluyendo objetivos de control, mapas de auditoría, herramientas para su implementación y una guía de técnicas de gestión, como se puede ver en la siguiente figura:
    .titulo-sexto.color-acento-contenido(data-aos="fade-right")
      p.mb-0 <b>Figura 2.</b> Marco COBIT
    .row.mb-5.justify-content-center(data-aos="zoom-in-up")
      .col-lg-8
        img(src='@/assets/curso/18.jpg', alt='Imagen que presenta el Marco COBIT.')
        figcaption Nota. Tomado de Cynthus (2020).
    .titulo-sexto.color-acento-botones.d-flex.align-items-center(data-aos="fade-right")
      .titulo-principal__numero.p-3
        span.text-white.h5 4
      h5 El cuarto y último marco del contenido a revisar es el marco HITRUST CSF <i>(Health Information Trust Alliance - Cybersecurity Framework).</i>
    p.mb-5 <b>HITRUST CSF</b> fue desarrollado por <i>Health Information Trust Alliance</i> (HITRUST) y es el marco de seguridad más adoptado en la industria de la salud de los Estados Unidos. <b>HITRUST</b> originalmente desarrolló su CSF (<i>Cybersecurity Framework</i> – Marco de ciberseguridad) para enfocarse en elementos clave y riesgos inherentes a la industria de la salud, como las consideraciones de <b>HIPAA</b> (Ley de Responsabilidad y Portabilidad de Seguros de Salud) pero desde entonces han actualizado el marco con controles más amplios que se aplicarían a cualquier organización.
      br
      br
      |#[em HITRUST CSF] es un marco basado en el riesgo y el cumplimiento y se actualiza con bastante frecuencia. También se puede adaptar según una variedad de factores, que incluyen el tipo de organización, el tamaño y los sistemas, así como los requisitos reglamentarios.
    Separador
    #t_1_2.titulo-segundo(data-aos="fade-right")
      h2 1.2 Tríada de la Seguridad de la Información
    p.mb-5 Seguridad de la información significa proteger la información y los sistemas de información de un acceso, uso, divulgación, alteración, modificación, lectura, inspección, registro o destrucción no autorizados. Soriano, M. (2014)
      br
      br
      |El siguiente video nos presenta, de forma más completa, este concepto.
    figure.mb-5
      .video
        iframe(width="560" height="315" src="https://www.youtube.com/embed/iJOOfpo1SdM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen)
      figcaption Ciberseguridad y Seguridad de la Información: tríada
    Separador
    #t_1_3.titulo-segundo(data-aos="fade-right")
      h2 1.3 Amenazas     
    .row.mb-5
      .col-lg-6(data-aos="fade-right")
        p.mb-5 Se refieren a la posibilidad que se presente algún tipo de evento, en cualquier instante de tiempo, y se produzca un daño material o inmaterial sobre los activos informáticos y los sistemas de información. Las amenazas son consideradas como los ataques cometidos por personas internas o externas, que pueden ocasionar daños a la infraestructura tecnológica, a los sistemas de información o a la misma información que circula en la organización.
          br
          br
          |Si bien cada vez son más y más especializadas, a continuación se mencionan algunas de las amenazas más comunes y que mayor afectación provocan en los recursos y medios digitales utilizados frecuentemente.
      .col-lg-6(data-aos="fade-left"): img(src='@/assets/curso/20.svg')
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg__2-claro")
      .row(titulo="<em>Spam</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/21.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Correo no deseado. Mucha gente se ve afectada cada año por correo no deseado que falsificó su información, engañando al usuario para que siga algunos de los enlaces que normalmente contiene y que los redirecciona a sitios previamente programados o en ocasiones, hace que se ejecuten algunos #[em scripts] o fragmento de código, que realizarán alguna actividad prohibida sobre los recursos tecnológicos.
      .row(titulo="<em>Pharming</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/22.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Tiene por principal objetivo convencer al usuario de que visite un sitio web malicioso e ilegítimo redireccionando la URL legítima u original a una URL ilegítima, una vez dentro, el objetivo de los cibercriminales es conseguir que el usuario les dé su información personal. 
      .row(titulo="<em>Phishing</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/23.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Es una de las amenazas informáticas más fáciles de ejecutar. Consiste en enviar correos electrónicos falsos o mensajes que se parecen a los correos electrónicos enviados por compañías legítimas. Así, se hace pensar al usuario que es la compañía legítima y aumentan las probabilidades de que se comparta información personal y financiera, algunos ejemplos podemos encontrarlos en mensajes de banco o entidades financieras donde lo que se busca es robar las credenciales y contraseñas de acceso a sus cuentas. 
      .row(titulo="<em>Ransomware</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/24.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Este tipo de amenaza busca secuestrar o restringir el acceso a las computadoras e información de sus víctimas, para luego solicitar un pago a cambio de recuperar el control de sus datos.
      .row(titulo="<em>Spyware</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/25.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Es un programa de computador malicioso que parece un #[em software] legítimo. Mientras está instalado en el ordenador del usuario, se ejecuta automáticamente y espía su sistema, capturando datos que permitan identificar el comportamiento del uso de los medios tecnológicos por parte del usuario o en algunas ocasiones, elimina sus archivos.
      .row(titulo="<em>Malware</em>").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/26.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Es un #[em software] malicioso. Este es el nombre común dado a varias amenazas de seguridad que se infiltran y dañan un recurso informático.
      .row(titulo="Virus ").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/27.svg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Un virus informático es un tipo de programa o código malicioso escrito para modificar el funcionamiento de un equipo, siempre está oculto en un #[em software] o sitio web legítimo, infecta el ordenador y puede extenderse a todos los que se encuentran en su lista de contactos.
    #t_1_4.titulo-segundo(data-aos="fade-right")
      h2 1.4 Vulnerabilidades 
    p.mb-5 Una vulnerabilidad informática es una debilidad en el #[em software] o en el #[em hardware] que permite a un posible atacante comprometer cualquiera de los elementos de la tríada de la seguridad, como es la integridad, disponibilidad o confidencialidad del sistema o de los datos que procesa.
    .row.mb-5.align-items-end
      .col-md-6(data-aos="fade-right")
        img(src='@/assets/curso/28.svg')
      .col-md-6(data-aos="fade-left")
        p.mb-0 Por errores en la configuración o parametrización de las herramientas que normalmente utilizamos por ejemplo al utilizar contraseñas no seguras, al no actualizar el sistema operativo o antivirus de nuestros dispositivos.
          br
          br
          |Para clasificarlos a continuación, se mencionan algunas de las vulnerabilidades más comunes: 
    .row.mb-5.justify-content-center
      .col-lg-2.center-figure.h-100
        .figure
          img(src='@/assets/curso/29.svg').mb-3
        p.fw-600.text-center Errores en los sistemas de validación.
      .col-lg-2.center-figure.h-100
        .figure
          img(src='@/assets/curso/30.svg').mb-3
        p.fw-600.text-center Errores que permiten el acceso a directorios. 
      .col-lg-2.center-figure.h-100
        .figure
          img(src='@/assets/curso/31.svg').mb-3
        p.fw-600.text-center Errores de configuración.
      .col-lg-2.center-figure.h-100
        .figure
          img(src='@/assets/curso/32.svg').mb-3
        p.fw-600.text-center Errores en la gestión y asignación de permisos.
      .col-lg-2.center-figure.h-100
        .figure
          img(src='@/assets/curso/33.svg').mb-3
        p.fw-600.text-center Errores en la gestión de recursos. 
    Separador
    #t_1_5.titulo-segundo(data-aos="fade-right")
      h2 1.5 Activos de información
    p.mb-5 Este término se relaciona con todos los elementos tecnológicos o relacionados con la tecnología que la organización utiliza, para el cumplimiento de sus metas o #[em core] del negocio. Según la norma ISO/IEC 27001, se entiende como activo todo aquello que es importante y que la organización valora, por lo tanto debe de protegerse.
      br
      br
      |Desde el punto de vista personal, activos informáticos serán todos aquellos elementos o herramientas tecnológicas tanto <i>hardware</i> (computadores, celulares, tabletas, PDA, entre otros) o elementos <i>software</i> como aplicaciones, correo electrónico, redes sociales, entre otras que son utilizadas dentro del contexto laboral o uso personal.
      br
      br
      |De acuerdo a la norma ISO/IEC 27001, es necesario clasificar e inventariar todos los activos de información de una empresa luego de ser identificados, esto se hace como cumplimiento al Modelo de Seguridad y Privacidad de la Información, el cual presenta la siguiente forma:
    .row.mb-5
      .col-md-6.col-xl.mb-4.mb-xl-0
        //- .tarjeta-numerada debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta-numerada.color-primario.p-5.h-100
          .tarjeta-numerada__numero
            .h2 1
          p
            b Inventario de activos: 
          p Se deben identificar todos los activos de la compañía y a su vez crear un inventario de estos.

      .col-md-6.col-xl.mb-4.mb-xl-0
        //- .tarjeta-numerada debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta-numerada.color-secundario.p-5.h-100
          .tarjeta-numerada__numero
            .h2 2
          p
            b Propiedad de activos: 
          p Cada activo identificado debe contar con un responsable o propietario. 
      .col-md-6.col-xl.mb-4.mb-xl-0
        //- .tarjeta-numerada debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta-numerada.color-acento-contenido.p-5.h-100
          .tarjeta-numerada__numero
            .h2 3
          p
            b Clasificación de la información:  
          p Se debe realizar su respectiva clasificación dependiendo del requerimiento legal, valor, criticidad, divulgación y modificación.

      .col-md-6.col-xl.mb-4.mb-xl-0
        //- .tarjeta-numerada debe ir acompañado de una de una de estas clases => 
        //- .color-primario, .color-secundario, .color-acento-contenido, .color-acento-botones
        //- estas clases tambien tienen un modificador --borde
        .tarjeta-numerada.color-acento-botones.p-5.h-100
          .tarjeta-numerada__numero
            .h2 4
          p
            b Manipulación de información: 
          p Se debe contar con procedimientos que permitan etiquetar la información y que funcione con el sistema de clasificación que definió la empresa.
    p.mb-5 La clasificación de un activo de información está dada por las propiedades de los datos, estas propiedades son:
    .contenedor-tarjetas.justify-content-center.mb-5(data-aos="zoom-in-down")
      .tarjeta-degrade.p-4.align-items-center.m-1
        img(src='@/assets/curso/34.svg').mx-3
        p.fw-bold.mb-0 Confidencialidad.
      .tarjeta-degrade.p-4.align-items-center.m-1
        img(src='@/assets/curso/35.svg').mx-3
        p.fw-bold.mb-0 Integridad.
      .tarjeta-degrade.p-4.align-items-center.m-1
        img(src='@/assets/curso/36.svg').mx-3
        p.fw-bold.mb-0 Disponibilidad.
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        p.mb-5 Observe que siempre realizamos énfasis en la tríada de la información como principio para el tratamiento de los datos; esta clasificación también revisa el impacto que tendrá cada uno de los principios en caso de ser vulnerado y el impacto en las personas o empresas en el suceso.
        .cajon.color-acento-contenido.bg__1-claro.p-5.mb-4(style="background-color:#CCE4FB;")
          p Debemos tener siempre presentes los riesgos informáticos, los cuales son todo tipo de vulnerabilidades, amenazas que pueden ocurrir sin previo aviso y producir numerosas pérdidas para las empresas o las personas. Los riesgos más perjudiciales son a las tecnologías de información y comunicaciones, como por ejemplo, la pérdida de datos debido a daño en los discos, virus informáticos, entre otros.
      .col-lg-5(data-aos="fade-left")
        img(src='@/assets/curso/37.svg' style='width: 369px').m-auto
    .row.mb-5.align-items-end
      .col-md-6(data-aos="fade-right")
        img(src='@/assets/curso/38.svg')
      .col-md-6(data-aos="fade-left")
        p.mb-0 Cada amenaza es diferente y no todas tienen el mismo impacto en el sistema de seguridad de los sistemas informáticos, hay exigencias elevadas y exigencias que no son tan peligrosas, pero el sistema de información y riesgo se debe encargar de todas estas amenazas de manera consciente y firme, es por eso que las partes trabajan en integrar los tipos de riesgo en tres niveles, estableciendo de esa forma la exigencia o nivel en función de la seguridad.
    .tarjeta.bg__4-claro.p-4.mb-5(style="background-color:#fff3c7 !important;")
      SlyderA
        .row.p-4.justify-content-center
          .col-lg-7.mb-4.mb-lg-0(style="place-self:center;")
            h4 Bajo
            p Cuando una amenaza no representa un ataque importante en los procesos de una organización o institución.
          .col-lg-5
            figure.m-auto.col-8.col-md-8.col-lg-12
              img(src='@/assets/curso/39.svg')
        .p-4.justify-content-center
          .col-lg-6.m-auto
            .mb-4.text-center
              h4 Medio
              p Se establece cuando la amenaza impacta de forma parcial a las actividades de la organización o institución.
          .col-lg-5.m-auto
            figure.m-auto.col-8.col-md-8.col-lg-12
              img(src='@/assets/curso/40.svg')
        .row.p-4.justify-content-center
          .col-lg-5.mb-4.mb-lg-0(style="place-self:center;")
            figure.m-auto.col-8.col-md-8.col-lg-12
              img(src='@/assets/curso/41.svg')
          .col-lg-5(style="place-self:center;")
            h4 Bajo
            p Cuando una amenaza no representa un ataque importante en los procesos de una organización o institución.
    .row.mb-5.justify-content-center
      .col-lg-10
        .bloque-texto-g.color-primario.p-3.p-sm-4.p-md-5.mb-5
          .bloque-texto-g__img(
            :style="{'background-image': `url(${require('@/assets/curso/42.svg')})`}"
          )
          .bloque-texto-g__texto.p-4
            p.mb-0 Recuerde: analizar el riesgo es el punto inicial de trabajo en la seguridad de información, puesto que ya con el riesgo identificado se decide si se elimina, se ignora, se transfiere o se logra mitigar sabiendo siempre su real impacto corporativo y personal, es decir, se hace la gestión del riesgo.
    p.mb-5 Anteriormente se estudió que existen diferentes riesgos informáticos, algunos de los más frecuentes son generados gracias al uso de dispositivos (informática) y se debe tener mucho cuidado porque algunos son de bajo riesgo, pero pueden subir de nivel con rapidez y facilidad:
    AcordionA.mb-5(tipo="a" clase-tarjeta="tarjeta bg__2-claro")
      .row(titulo="Fraude a través de redes o medios computacionales").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/43.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Es algo muy común y que se debe tener en cuenta, ya que comprende la manipulación ilegal de la información de la empresa a través de la creación de datos falsos, la alteración de los datos originales, así como de los procesos informáticos de la compañía con el propósito de obtener algún beneficio o de perjudicar a la organización.
      .row(titulo="Utilizar ilegalmente los sistemas informáticos de otras personas").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/44.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Esto es algo que se ve mucho en las organizaciones y se trata de cuando los trabajadores, o personas ajenas a la organización, utilizan sin autorización los equipos y programas de un sistema informático ajeno, desde el plano personal es muy común cuando hacemos uso de los correos electrónicos, redes sociales y acceso a sistemas informáticos de nuestros familiares o amigos sin su consentimiento. 
      .row(titulo="Riesgo de asociaciones con contrapartes").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/45.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Este tipo de riesgo se puede presentar al tomar la decisión de trabajar en un proyecto conjunto con un tercero. Los riesgos pueden surgir al momento de compartir información personal o empresarial. 
      .row(titulo="Acceso").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/46.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Claves de seguridad débiles, predecibles o compartidas.

      .row(titulo="Utilidad").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/47.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Mal uso de la tecnología, utilizar los recursos o medios tecnológicos para propósitos distintos a los originalmente deseados. 

      .row(titulo="Infraestructura").px-5
        .col-md-3
          figure
            img(src='@/assets/curso/48.jpg', alt='Texto que describa la imagen')
        .col-md-9.mb-4.mb-md-0
          p Hurtos de activos como aparatos tecnológicos (computadoras, celulares, PDA, tabletas, entre otros dispositivos que contienen información personal y/o financiera).
    p.mb-5 En los protocolos de seguridad de la información ya determinamos los riesgos y las amenazas que pueden atacar tanto los recursos físicos como digitales, ahora nos preguntamos:
    .row.mb-5
      .col-lg-7(data-aos="fade-right")
        img(src='@/assets/curso/49.svg')
      .col-lg-5(data-aos="fade-left")
        p Para determinar cómo tratarlo y las acciones de mitigación a realizar, tenga en cuenta lo siguiente:
        ol.lista-ol--cuadro
          li.d-flex
            .lista-ol--cuadro__vineta
              span 1
            div Revisar las políticas de seguridad.
          li.d-flex
            .lista-ol--cuadro__vineta
              span 2
            div Actualizar todos los filtros y antivirus.
          li.d-flex
            .lista-ol--cuadro__vineta
              span 3
            div Ajustar y cambiar de contraseñas de manera periódica.
          li.d-flex
            .lista-ol--cuadro__vineta
              span 4
            div Instalar #[em firewalls].
          li.d-flex
            .lista-ol--cuadro__vineta
              span 5
            div Reservar datos, no compartir contraseñas.
          li.d-flex
            .lista-ol--cuadro__vineta
              span 6
            div No compartir cuentas y contraseñas de acceso a cuentas o recursos.
    p.mb-5 Con relación a las redes sociales se dispone el siguiente paso:
    .row.mb-5(style="background-color:#CCE4FB;")
      .col-lg-6(data-aos="fade-right")
        .tarjeta-adorno.bg__1.p-4.mt-5.d-flex.align-items-center
          .tarjeta-adorno_imagen
            img(src='@/assets/curso/50.svg' style='width: 127px')
          .tarjeta-adorno_contenido.px-4.py-2
            p.mb-0 No aceptar invitaciones de personas o perfiles que no reconozca.
      .col-lg-6(data-aos="fade-left")
        .tarjeta-adorno.bg__1.p-4.mt-5.d-flex.align-items-center
          .tarjeta-adorno_imagen
            img(src='@/assets/curso/51.svg' style='width: 127px')
          .tarjeta-adorno_contenido.px-4.py-2
            p.mb-0 Revisar los contenidos antes de compartirlos para evitar problemas de seguridad.
    p.mb-4 Se deben tener los controles de manera preventiva antes de tener que actuar con los correctivos.
      br
      br
      |Una vez calculado el riesgo, se debe responder con mitigación inmediata por medio de estrategias activas. A continuación se hace mención de las cuatro estrategias principales que puede usar en el caso de requerir mitigar un riesgo:
    .row.mb-5.justify-content-center.col-xl-10.m-auto(data-aos="zoom-in-up")
      .row
        .col-auto.pe-0
          .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#66AEF4;border-radius:15px 0px 0px 0px;")
            figure
              img(src="@/assets/curso/81.svg" style="width:80px;height:80px;")
        .col.ps-0
          .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
            strong.pe-3 01
            p.mb-0 Transferir el riesgo a un tercero. Por ejemplo, contratando un seguro que cubra los daños a terceros ocasionados por fugas de información.
      .row
        .col-auto.pe-0
          .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#35EBC0;")
            figure
              img(src="@/assets/curso/82.svg" style="width:80px;height:80px;")
        .col.ps-0
          .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
            strong.pe-3 02
            p.mb-0 Eliminar el riesgo. Por ejemplo, eliminando un proceso o sistema que está sujeto a un riesgo elevado. En el caso práctico que hemos expuesto, podríamos eliminar la wifi de cortesía para dar servicio a los clientes si no es estrictamente necesario.
      .row
        .col-auto.pe-0
          .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#66AEF4;")
            figure
              img(src="@/assets/curso/82.svg" style="width:80px;height:80px;")
        .col.ps-0
          .h-100.p-3.d-flex.align-content-center(style="background-color:#CCE4FB;")
            strong.pe-3 03
            p.mb-0 Asumir el riesgo, se da cuando algún riesgo puede ser aceptados, ya que su impacto no es tan alto o porque mitigarlo puede resultar demasiado costoso. 
      .row
        .col-auto.pe-0
          .h-100.p-2.d-flex.align-content-center.flex-wrap(style="background-color:#35EBC0;border-radius:0px 0px 0px 15px;")
            figure
              img(src="@/assets/curso/83.svg" style="width:80px;height:80px;")
        .col.ps-0
          .h-100.p-3.d-flex.align-content-center(style="background-color:#9AF5DF;")
            strong.pe-3 04
            p.mb-0 Implantar medidas para mitigarlo. Por ejemplo, adquirir y actualizar periódicamente un sistema de protección antivirus.
      
          
      
</template>

<script>
export default {
  name: 'Tema1',
  components: {},
  data: () => ({
    // variables de vue
  }),
  mounted() {
    this.$nextTick(() => {
      this.$aosRefresh()
    })
  },
  updated() {
    this.$aosRefresh()
  },
}
</script>
<style lang="sass">
.bloque-texto-f:before
  background-color: #ffd947
.contenedor-tarjetas
  display: flex
  flex-wrap: wrap
  .tarjeta-degrade
    box-shadow: 1px 2px 10px #cccc
    border-radius: 10px
    background: linear-gradient(90deg, rgba(3,230,176,1) 0%, rgba(150,219,225,1) 50%, rgba(3,230,176,1) 100%)
    background-size: 600% 400%
    animation: gradient 8s alternate infinite
    flex-basic: 300px
    flex-grow: 1
    justify-content: center
    width: 400px
    display: flex
    img
      width: 118px
    transition: transform .3s ease-in-out
    &:hover
      transform: scale(1.1)
@keyframes gradient
	0%
		background-position: 0% 50%;

	50%
		background-position: 100% 50%;

	100%
		background-position: 0% 50%;
.tarjeta--azul
  background-color: #F3F9FF
.figure
  img
    width: 190px
    height: 190px
.bloque-texto-g__img
  left: auto
  right: 0
.bloque-texto-g
  justify-content: flex-start !important
.tarjeta-adorno
  justify-content: flex-end
  position: relative
  @media (min-width: $bp-min-xl )
    &_imagen
        position: absolute
        left: 0
        bottom: 0
        transform: translate(30%, -10%)
    &_contenido
      width: 70%
.slyder-a__tipo-a .slyder-a__bullets
  bottom: 0px
.acordion .tarjeta
  background-color: #03E6B0
.acordion__activo
  background-color: #9AF5DF !important
</style>
