<template lang="pug">
.curso-main-container.pb-3
  BannerInterno
  .container.tarjeta.tarjeta--blanca.p-4.p-md-5
    .titulo-principal
        .titulo-principal__numero
          span 3
        h1 Libros contables
    .bloque-texto-a.color-secundario.p-4.p-md-5.mb-5 
      .row.m-0.align-items-center.justify-content-between
          .col-lg-4.mb-4.mb-lg-0
              img(src="@/assets/curso/images/tema3/img_30.svg")
          .col-lg-8
            .bloque-texto-a__texto.p-4
              p Los libros de información financiera están conformados por libros auxiliares y principales, su diligenciamiento debe efectuarse de forma cronológica, acorde a la normatividad vigente. Los libros contables están conformados por comprobantes de contabilidad base para la elaboración de estados financieros (Angulo, 2018). En coherencia con el Decreto ley 19 de 2012 (Secretaría del Senado, 2020), se registran en las Cámaras de comercio los libros de actas de socios y accionistas.

    p.mt-3 Según el Código Comercio (Secretaría del Senado, 2020. Art. 48 al 56):

    AcordionA.mt-5(tipo="a" clase-tarjeta="tarjeta tarjeta--gris")
        .row.px-5(titulo="Artículo 48:")
          .col-md-6.mb-4.mb-md-0
          p Todo comerciante conformará su contabilidad, libros, registros contables, inventarios y estados financieros en general, a las disposiciones de este Código y demás normas sobre la materia. Dichas normas podrán autorizar el uso de sistemas que, como la microfilmación, faciliten la guarda de su archivo y correspondencia. Asimismo, será permitida la utilización de otros procedimientos de reconocido valor técnico-contable, con el fin de asentar sus operaciones, siempre que facilite el conocimiento y prueba de la historia clara, completa y fidedigna de los asientos individuales y el estado general de los negocios.
        
        .row.px-5(titulo="Artículo 49:")
          .col-md-6.mb-4.mb-md-0
          p Libros de comercio para los efectos legales, cuando se haga referencia a los libros de comercio, se entenderán por tales los que determine la ley como obligatorios y los auxiliares necesarios para el completo entendimiento de aquellos.
        .row.px-5(titulo="Artículo 53:")
          .col-md-6.mb-4.mb-md-0
          p De las operaciones mercantiles. En los libros se asentarán en orden cronológico las operaciones mercantiles y todas aquellas que puedan influir en el patrimonio del comerciante, haciendo referencia a los comprobantes de contabilidad que las respalden.

          p.mt-3 El comprobante de contabilidad es el documento que debe elaborarse previamente al registro de cualquier operación y en el cual se indicará el número, fecha, origen, descripción y cuantía de la operación, así como las cuentas afectadas con el asiento. A cada comprobante se anexarán los documentos que lo justifiquen.

        .row.px-5(titulo="Artículo 57 en los libros de comercio se prohíbe:")
          .col-md-6.mb-4.mb-md-0
            .row
              ol.lista-ol--cuadro.mt-5
                  li 
                    .lista-ol--cuadro__vineta
                      span 1
                    |   Alterar en los asientos el orden o la fecha de las operaciones a que estos se refieren;
                  li 
                    .lista-ol--cuadro__vineta
                      span 2
                    |   Dejar espacios que faciliten intercalaciones o adiciones en el texto de los asientos o a continuación de estos;

                  li 
                    .lista-ol--cuadro__vineta
                      span 3
                    |   Hacer interlineaciones, raspaduras o correcciones en los asientos. Cualquier error u omisión se salvará con un nuevo asiento en la fecha en que se advirtiere;
                  li 
                    .lista-ol--cuadro__vineta
                      span 4
                    |   Borrar o tachar en todo o en parte los asientos, 

                  li 
                    .lista-ol--cuadro__vineta
                      span 5
                    |   Numeral modificado por el artículo 174 del Decreto 19 de 2012. El nuevo texto es el siguiente: Arrancar hojas, alterar el orden de estas o mutilar 

            p.mt-3 Para observar la totalidad del capítulo de libros de comercio, revisar el link en:
          .row.mt-5
              .col-lg-6
                a.anexo.mb-4.mb-lg-0(href="http://www.secretariasenado.gov.co/senado/basedoc/codigo_comercio_pr001.html" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-link.svg")
                  .anexo__texto
                    p Enlace web. Archivo general
          p.mt-3 En tema tributario observemos el Estatuto Tributario (Secretaría del Senado, 2020. Art. 654 y 655):
          br
          p.mb-3 Nos menciona las sanciones relacionadas con la contabilidad y de clausura de establecimiento.
          p.mb-3 Artículo 654: Habrá lugar a aplicar sanción por libros de contabilidad, en los siguientes casos:
          .row.justify-content-center.align-items-center.mt-3
            .col
              .row
                .col-sm.mb-5.mb-sm-0
                  ol.lista-ol--cuadro
                    li 
                      .lista-ol--cuadro__vineta
                        span a
                      | No llevar libros de contabilidad si hubiere obligación de llevarlos.
                    li 
                      .lista-ol--cuadro__vineta
                        span b
                      | No tener registrados los libros principales de contabilidad, si hubiere obligación de registrarlos.
                    li 
                      .lista-ol--cuadro__vineta
                        span c
                      | No exhibir los libros de contabilidad, cuando las autoridades tributarias lo exigieren.
                    li 
                      .lista-ol--cuadro__vineta
                        span d
                      | Llevar doble contabilidad.
                    li 
                      .lista-ol--cuadro__vineta
                        span e
                      | No llevar los libros de contabilidad en forma que permitan verificar o determinar los factores necesarios para establecer las bases de liquidación de los impuestos o retenciones.
                    li 
                      .lista-ol--cuadro__vineta
                        span f
                      | Cuando entre la fecha de las últimas operaciones registradas en los libros, y el último día del mes anterior a aquél en el cual se solicita su exhibición, existan más de cuatro (4) meses de atraso.

                  p.mb-3 Artículo 655, sanciones por irregularidades en la contabilidad.

                  p.mb-3 (Ajuste de las cifras en valores absolutos en términos de UVT por el artículo 51 de la Ley 1111 de 2006 (Secretaría del Senado, 2020). El texto con el nuevo término es el siguiente:) Sin perjuicio del rechazo de los costos, deducciones, impuestos descontables, exenciones, descuentos tributarios y demás conceptos que carezcan de soporte en la contabilidad, o que no sean plenamente probados de conformidad con las normas vigentes, la sanción por libros de contabilidad será del medio por ciento (0.5%) del mayor valor entre el patrimonio líquido y los ingresos netos del año anterior al de su imposición, sin exceder de 20.000 UVT.
                  p.mb-3 Para profundizar en el tema libros contables, revisar el concepto 650 (Consejo Técnico de la Contaduría Pública, 2020), en el siguiente enlace: 

          .row.mt-5
              .col-lg-12
                a.anexo.mt-4.mb-lg-0(href="https://www.ctcp.gov.co/conceptos/2018" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p  Artículo 57   

    separador    

    #t_3_1.titulo-segundo
      h2 3.1 Conceptos, clasificación, formatos y comprobantes
    
    p.mt-3 Los libros de contabilidad deben respetar los principios básicos de contabilidad. Ser diligenciados y presentados en el momento que las autoridades de inspección los soliciten, so pena de sanciones por no llevar libros de contabilidad. Una vez solicitados dichos libros de contabilidad por parte de la administración de impuestos y aduanas nacionales DIAN, después de cinco días sin realizar la entrega efectiva, se generará una sanción (Angulo, 2018).
    br
    p Está prohibido llevar doble contabilidad o presentar más de cuatro meses de retraso en el registro de información financiera (Angulo, 2018).
    br
    p Los libros contables oficiales deben presentar sus respectivos soportes, con documentos que cumplan los requisitos legales, que resguarden las cifras presentadas.
    br
    p Dentro de los libros que se deben diligenciar y presentar se encuentran (Angulo, 2018):

    
        .row.justify-content-center.align-items-center.mt-3
          .col
            .row
              .col-sm.mb-5.mb-sm-0
                ol.lista-ol--cuadro
                  li 
                    .lista-ol--cuadro__vineta
                      span 1
                    | Libro diario.
                  li 
                    .lista-ol--cuadro__vineta
                      span 2
                    | Libro mayor y balances.
                  li 
                    .lista-ol--cuadro__vineta
                      span 3
                    | Libro de actas de asambleas.
                  li 
                    .lista-ol--cuadro__vineta
                      span 4
                    | Libros de actas de Consejo de Administración o Junta Directiva
                  li 
                    .lista-ol--cuadro__vineta
                      span 5
                    | Libro de actas de Junta de Vigilancia o Comité de Control Social.
                  li 
                    .lista-ol--cuadro__vineta
                      span 6
                    | Libro de Registro social.
                  li 
                    .lista-ol--cuadro__vineta
                      span 7
                    | Libros auxiliares.

          .col-auto 
              img(src="@/assets/curso/images/tema3/img_31.svg" alt="", style="width:300px; display:inline-block; margin:auto 6rem;").img-fluid

          hr.my-5
          h3 Libro diario

          p.mb-5 Es un medio de prueba para las autoridades, registra el día a día las operaciones comerciales, registrando devengos contables, presenta como características sumas iguales.

         
          h4 Características:

    .row.justify-content-center.align-items-center
        .col-auto 
            img.img-a.my-3(src="@/assets/curso/images/tema3/img_32.svg" alt="", style="width:350px; display:block; margin:auto 5rem;").img-fluid
        .col-sm.mb-3
          
           
            ul.lista-ul--color
              li 
                i.fas.fa-check
                | Contiene fecha de elaboración.
              li 
                i.fas.fa-check
                  
                | Códigos contables, aplica principio básico de la partida doble.
              li 
                i.fas.fa-check
                
                | Presenta una columna de la cuenta auxiliar, generalmente trabajada a seis (6) Dígitos.
              li
                i.fas.fa-check

                | Columna para los débitos.
              li 
                i.fas.fa-check

                | Columna para créditos.
              li 
                i.fas.fa-check

                | Sumas iguales.
            p.mb-4.mt-4 El libro diario de contabilidad presenta registros contables clasificados en asientos:
            ul.lista-ul--color 
              li 
                i.fas.fa-check
                  
                p #[strong Normales:] registra operaciones diarias de la organización.
              li 
                i.fas.fa-check
                
                p #[strong De ajustes:] registra las depreciaciones y amortizaciones.
              li 
                i.fas.fa-check

                p #[strong Cierre:] al finalizar un periodo contable, comúnmente al finalizar el año, se debe hacer cierre de cuentas para ser trasladadas como saldos iniciales para un nuevo periodo contable.

    .row.mt-5
      .col-lg-5
        a.anexo.mb-4(href="http://elcontador.net/libro-diario-general/" target="_blank")
          .anexo__icono
            img(src="@/assets/template/icono-pdf.svg")
          .anexo__texto
            p Anexo. Libro diario

    hr.mystery-5
    h4 Libro mayor y balances

    p.mt-3 Cada mes se debe realizar cierre del periodo con el fin de identificar el comportamiento financiero del periodo y, de esta forma, que los administradores puedan tomar decisiones. 

    
        .row.justify-content-center.align-items-center.mt-3
          .col
            h5 Características:
            .col-sm.mt-3
              ul.lista-ul--color 
                li 
                  i.fas.fa-check
                  | Posibilita la elaboración de estados de resultados integrales.
                li 
                  i.fas.fa-check
                    
                  | Permite la elaboración de estado de situación financiera.
                li 
                  i.fas.fa-check
                  
                  | El resumen de la información se hace mediante la aplicación de cuentas mayores de forma resumida de débitos y créditos. Se deben codificar a cuatro (4) dígitos, contiene la información de los libros auxiliares. 
                
            h5 Diligenciamiento:

            .col-sm.mt-3
              ul.lista-ul--color 
                li 
                  i.fas.fa-check
                  | Registra número de folio mayor, acorde al consecutivo, donde se realiza el resumen de la transacción económica.
                li 
                  i.fas.fa-check
                    
                  | Codifica nombre de la cuenta contable utilizada.
                li 
                  i.fas.fa-check
                  
                  | Registra saldo del mes anterior, acorde al principio de partida doble y naturaleza de las cuentas débitos y créditos.
                li
                  i.fas.fa-check

                  | Movimientos del periodo en las columnas debe y haber, que reciben los débitos y créditos de las transacciones.
                li
                  i.fas.fa-check

                  | Restar y sumar acorde al caso y naturaleza de las cuentas para obtener el nuevo saldo de inicio para el nuevo periodo.    
                  
          .col-auto 
              img.img-a.my-3(src="@/assets/curso/images/tema3/img_33.svg" alt="", style="width:300px; display:inline-block; margin:auto 5rem;").img-fluid
              
          .row.mt-5
            .col-lg-6
              a.anexo.mb-4(href="http://fccea.unicauca.edu.co/old/fcf/fcfse41.html" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p Anexo. Libro mayor y balances
          
    hr.my-5

    h4 Libro de actas de asamblea 

    p.mt-2 Según el Código del Comercio (Secretaría del Senado, 2020. Art. 189 y 431):

    p.mt-3 Artículo189. Las decisiones de la junta de socios o de la asamblea se harán constar en actas aprobadas por la misma, o por las personas que se designen en la reunión para tal efecto, y firmadas por el presidente y el secretario de la misma, en las cuales deberá indicarse, además, la forma en que hayan sido convocados los socios, los asistentes y los votos emitidos en cada caso. La copia de estas actas, autorizada por el secretario o por algún representante de la sociedad, será prueba suficiente de los hechos que consten en ellas, mientras no se demuestre la falsedad de la copia o de las actas. A su vez, a los administradores no les será admisible prueba de ninguna clase para establecer hechos que no consten en las actas.
    br
    p Artículo 431. Lo ocurrido en las reuniones de la asamblea se hará constar en el libro de actas. Estas se firmarán por el presidente de la asamblea y su secretario o, en su defecto, por el revisor fiscal. Las actas se encabezarán con su número y expresarán cuando menos: lugar, fecha y hora de la reunión; el número de acciones suscritas; la forma y antelación de la convocación; la lista de los asistentes con indicación del número de acciones propias o ajenas que representen; los asuntos tratados; las decisiones adoptadas y el número de votos emitidos en favor, en contra, o en blanco; las constancias escritas presentadas por los asistentes durante la reunión; las designaciones efectuadas, y la fecha y hora de su clausura.

  
        .row.justify-content-center.align-items-center
          .col-auto 
              img.img-a.my-3(src="@/assets/curso/images/tema3/img_34.svg" alt="", style="width:350px; display:inline-block; margin:auto 4rem;").img-fluid
          .col.mt-5
            h5 Diligenciamiento:
            .col-sm.mt-3
              ul.lista-ul--color 
                li 
                  i.fas.fa-check
                  | Registro fecha de la solicitud.
                li 
                  i.fas.fa-check
                    
                  | Registro razón social y NIT.
                li 
                  i.fas.fa-check
                  
                  | Indicar el tipo de inscripción.
                li
                  i.fas.fa-check

                  | Dirección de la página web.
                li 
                  i.fas.fa-check

                  | Nombre y firma del representante legal de la empresa.
                li 
                  i.fas.fa-check

                  | Nombre y firma del Revisor fiscal, anexando número de tarjeta profesional.

            .row.mt-5
              .col-lg-12
                a.anexo.mb-4(href="https://www.camarabaq.org.co/wp-content/uploads/2019/01/3-Formato-Inscripcio%CC%81n-de-libros-pa%CC%81ginas-web.pdf" target="_blank")
                  .anexo__icono
                    img(src="@/assets/template/icono-pdf.svg")
                  .anexo__texto
                    p Anexo. Libro mayor y balances
        hr.my-5
        h4 Libros de Consejo de administración o Junta directiva
        .row.justify-content-center.align-items-center.mt-3
          .col
            p En este libro se registra la información básica de la empresa, se incluyen todas las decisiones en las actas, como acuerdos a los que llegan los dueños de una empresa. Se debe llevar un orden cronológico de las reuniones, en él se encuentran inscritos los dueños, administradores y representante legal, siempre debe estar firmado por secretario y presidente.
            br
            p Según Ley 1755 de 2001 (Secretaría del Senado, 2020. Art. 47):
            br
            p Las decisiones de la asamblea se harán constar en actas firmadas por el presidente y el secretario de la misma, en las cuales deberá indicarse si es ordinaria o extraordinaria. Además, la forma de la convocatoria, orden del día, nombre y calidad de los asistentes, su unidad privada y su respectivo coeficiente, y los votos emitidos en cada caso.
            br
            p En los eventos en que la asamblea decida encargar personas para verificar la redacción del acta, las personas encargadas deberán hacerlo dentro del término que establezca el reglamento, y en su defecto, dentro de los veinte (20) días hábiles siguientes a la fecha de la respectiva reunión.
            br
            p Dentro de un lapso no superior a veinte (20) días hábiles contados a partir de la fecha de la reunión, el administrador debe poner a disposición de los propietarios del edificio o conjunto, copia completa del texto del acta en el lugar determinado como sede de la administración, e informar tal situación a cada uno de los propietarios. En el libro de actas se dejará constancia sobre la fecha y lugar de publicación.
            br
            p La copia del acta debidamente suscrita será prueba suficiente de los hechos que consten en ella, mientras no se demuestre la falsedad de la copia o de las actas. El administrador deberá entregar copia del acta a quien se la solicite.
            br
            p.mb-5 PARÁGRAFO. Todo propietario a quien se le niegue la entrega de copia de acta podrá acudir en reclamación ante el Alcalde Municipal o Distrital o su delegado, quien a su vez ordenará la entrega de la copia solicitada, so pena de sanción de carácter policivo.

            h5 Libros de actas de Junta de vigilancia o Comité de control social y registro social.

            p Para registrar dichos libros se requiere una carta de solicitud de inscripción de libros.

            .col-sm.mt-3
              ul.lista-ul--color 
                li 
                  i.fas.fa-check
                  | Fecha de solicitud.
                li 
                  i.fas.fa-check
                    
                  | Nombre de la sociedad y número de -matrícula.
                li 
                  i.fas.fa-check
                  
                  | Nombre de libro registro social o junta de vigilancia.
                li
                  i.fas.fa-check

                  | Registro de todas las hojas de los libros a registrar, acompañado de las firmas del representante legal de la sociedad.

          .col-auto 
              img.img-a.my-3(src="@/assets/curso/images/tema3/img_35.svg" alt="", style="width:300px; display:inline-block; margin:auto 4rem;").img-fluid
              
    hr.my-5

    h5 Características:
    p Según Circular 002 de 2016 de la Super Intendencia de Industria y Comercio (Cámara de Comercio de Santa Marta, 2020):

    TabsC.color-acento-contenido.mb-5
        .py-3.py-md-4(titulo="2.1.9.2")
          .row
            .col-md-6.mb-4.mb-md-0
              h5 Respecto de los libros de comercio:
              p Una vez efectuada la inscripción de los libros sometidos a dicha formalidad, el secretario de la Cámara de Comercio insertará una constancia en la primera hoja del libro registrado que contendrá los siguientes datos:

              .col-sm.mt-3
                ul.lista-ul--color 
                  li 
                    i.fas.fa-check
                    | Cámara de Comercio. 
                  li 
                    i.fas.fa-check
                      
                    | Nombre de la persona a quien pertenece. 
                  li 
                    i.fas.fa-check
                    
                    | Fecha, número de inscripción y libro en el cual se efectuó.
                  li 
                    i.fas.fa-check

                    | Nombre del libro o uso al que se destina, y Código del libro y número de hojas útiles de que está compuesto. 

            p.mt-3 Las Cámaras de Comercio deberán autenticar las hojas útiles de los libros mediante un sello de seguridad impuesto en cada una de ellas. Para efectos de inscripción de nuevos libros (físicos o electrónicos) será necesario acreditar ante la respectiva Cámara de Comercio que a los existentes les faltan pocos folios por utilizar, o que deben ser sustituidos por causas ajenas a su propietario, mediante la presentación del propio libro o del certificado del revisor fiscal, cuando exista el cargo o, en su defecto del contador público.
  

        .py-3.py-md-4(titulo="2.1.9.2.1")
          .row
            .col-md-12.mb-4.mb-md-0
              h5 Registro de libros de comercio en medios electrónicos.

              p.mt-3 Teniendo en cuenta que la ley facultó a los comerciantes para llevar los libros de comercio en medios electrónicos, es necesario que las Cámaras de Comercio implementen dentro de sus servicios virtuales, en los términos y condiciones señalados en las normas que rijan la materia, la posibilidad de efectuar el registro de estos libros, para lo cual deberán habilitar en sus plataformas electrónicas o sistemas de información, dicho servicio, garantizando su disponibilidad y fácil acceso para su posterior consulta. Las Cámaras de Comercio deberán dar publicidad al servicio de registro de libros de comercio en medios electrónicos y establecer los controles respectivos que impidan el registro en forma simultánea de un mismo libro, en medios electrónicos o de forma física, a fin de evitar su duplicidad. Las Cámaras de Comercio podrán facilitar la utilización de los mecanismos de firma digital o electrónica, no obstante, corresponde al comerciante la elección de cualquiera de estos siempre y cuando cumplan con los requisitos previstos en las normas que rijan la materia. El servicio de registro de libros en medios electrónicos deberá estar disponible para las entidades sin ánimo de lucro inscritas en las Cámaras de Comercio, en los mismos términos y condiciones de las sociedades comerciales, de acuerdo con las normas que rijan esta materia. 

        .py-3.py-md-4(titulo="2.1.9.2.2")
          .row
            .col-md-12.mb-4.mb-md-0
              h5  Procedimiento para efectuar registro de los libros de comercio registrables en medios electrónicos:
                 
              p.mt-3 De conformidad con lo establecido en la ley, los comerciantes que quieran llevar sus libros de comercio registrables, en medios electrónicos, deberán solicitarlo de manera expresa ante la Cámara de Comercio correspondiente a su domicilio, indicando una dirección de correo electrónico a la cual se le puedan remitir las inscripciones efectuadas y aceptando los términos y condiciones por ella establecidas para el efecto. Una vez recibida la solicitud de inscripción de los libros registrables, por parte del interesado, la Cámara de Comercio correspondiente deberá efectuar una inscripción por cada uno de los libros en el Libro respectivo del registro de que se trate, debiendo devolver al solicitante el archivo electrónico al correo electrónico que tenga reportado el comerciante o inscrito. Para ello, la Cámara de Comercio deberá firmarlo digital o electrónicamente, dejando constancia electrónica de la fecha y la hora en que fue enviado o remitido el archivo, por cualquier medio tecnológico disponible. De conformidad con lo establecido en las normas que rigen la materia, la constancia electrónica expedida por la Cámara de Comercio correspondiente, deberá tener la siguiente información: – Cámara de Comercio receptora. – Fecha de presentación del libro para registro. – Fecha de inscripción. – Número de inscripción. – Identificación del comerciante o persona obligada a registrar. – Nombre del libro, y – Uso al que se destina. A su vez, si a la fecha de la solicitud de inscripción del libro registrable por medios electrónicos, el libro físico que lo antecede posee hojas que no hubieren sido empleadas, deberán ser anuladas, de acuerdo con lo previsto en las normas que rigen la materia.

        .py-3.py-md-4(titulo="2.1.9.2.3")
          .row
            .col-md-12.mb-4.mb-md-0
              
              p.mt-3 Conformación de los libros registrados en medios electrónicos Efectuada la inscripción del libro de actas de juntas de socios o accionistas en medios electrónicos, el comerciante o inscrito tendrá derecho a remitir a la Cámara de Comercio, por el término de un (1) año, los archivos electrónicos en donde consten las actas de dicho órgano, los cuales deberán ser firmados digital o electrónicamente por quienes actuaron como presidente y secretario de la reunión. La solicitud de asentar el archivo electrónico contentivo del acta, en el libro correspondiente, deberá estar suscrita digital o electrónicamente por el representante legal, presidente o secretario. Efectuada la inscripción del libro de socios o accionistas en medios electrónicos, el comerciante o inscrito tendrá derecho a remitir a la Cámara de Comercio, por el término de un (1) año, archivos electrónicos destinados a ese libro, los cuales deberán ser firmados digital o electrónicamente por el representante legal. Es responsabilidad de cada comerciante la provisión de las firmas digitales o electrónicas y, estampas cronológicas necesarias. Una vez recibidos los archivos electrónicos, la Cámara de Comercio correspondiente deberá devolver al solicitante el archivo electrónico al correo electrónico que tenga reportado el comerciante o inscrito. Para ello, la Cámara de Comercio deberá firmarlo digital o electrónicamente, dejando constancia electrónica de la fecha y la hora en que fue enviado o remitido el archivo por cualquier medio tecnológico disponible.

    h5 Libros auxiliares:

    p.mt-3 Son los libros que reflejan de forma ordenada las operaciones realizadas por la empresa, afectando los débitos y créditos de una o varias cuentas y subcuentas, con el fin de generar el saldo en una fecha determinada.

    p.mt-3 Entre los libros auxiliares se encuentran: libro auxiliar de bancos, caja, IVA, inventarios, ingresos ordinarios, etc.

    
        .row.justify-content-center.align-items-center.mt-3
          .col
            h5 Características:
            .col-sm.mt-3
                ul.lista-ul--color
                  li 
                    i.fas.fa-check
                    | Nombre del libro auxiliar.
                  li 
                    i.fas.fa-check
                      
                    | Fecha de la transacción
                  li 
                    i.fas.fa-check
                    
                    | Detalle de la transacción
                  li 
                    i.fas.fa-check
                    | Débitos
                  li 
                    i.fas.fa-check
                      
                    | Créditos
                  li 
                    i.fas.fa-check
                    
                    | Saldo
                           
          .col-auto 
              img.img-a.my-3(src="@/assets/curso/images/tema3/img_36.svg" alt="", style="width:380px; display:inline-block; margin:auto 6rem;").img-fluid
              
          .row.mt-5
            .col-lg-6
              a.anexo.mb-4(href="https://www-ebooks7-24-com.bdigital.sena.edu.co/stage.aspx?il=8047&pg=&ed=" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-pdf.svg")
                .anexo__texto
                  p Anexo. Ejemplo:
    hr.my-5
    h4 Diligenciamiento y registro

    
    .row.justify-content-center.align-items-center.mt-5
      .col-auto 
        img.img-a.my-3(src="@/assets/curso/images/tema3/img_37.svg" alt="", style="width:350px; display:inline-block; margin:auto 4rem;").img-fluid
      .col.mt-5
        p Esquema de registro en un Sistema de información financiera:
        .row.mt-5
          .col-lg-12
            a.anexo.mb-4(href="https://www-ebooks7-24-com.bdigital.sena.edu.co/stage.aspx?il=8047&pg=&ed=" target="_blank")
              .anexo__icono
                img(src="@/assets/template/icono-pdf.svg")
              .anexo__texto
                p Anexo. Diligenciamiento y registro.
        p.mt-3 Para revisar el diligenciamiento de comprobantes de contabilidad, se invita a revisar el siguiente enlace:
        .row.mt-5
          .col-lg-12
            a.anexo.mt-4.mb-lg-0(href="http://www.ebooks7-24.com.bdigital.sena.edu.co/stage.aspx?il=&pg=&ed=" target="_blank")
                .anexo__icono
                  img(src="@/assets/template/icono-link.svg")
                .anexo__texto
                  p Enlace web. Planilla integrada de liquidación de aportes:
    hr.my-5

    h4 Sistema de gestión documental emitido por el ente regulador

    p.mt-3 El Estado colombiano busca, mediante la Resolución 8934 de febrero de 2014, implementar el sistema de gestión documental, con el objetivo de mantener organizados los archivos en el sector privado, enfocada básicamente en la organización de:

    
        .row.justify-content-center.align-items-center.mt-3
            .col-sm.mt-3
                ul.lista-ul--color
                  li 
                    i.fas.fa-check
                    | Tablas de retención documental.
                  li 
                    i.fas.fa-check
                      
                    | Programa de gestión documental.
                  li 
                    i.fas.fa-check
                    
                    | Cuadros de clasificación documental.
                  li 
                    i.fas.fa-check
                    | Tablas de valoración documental.
                  li 
                    i.fas.fa-check
                      
                    | Reglamento interno de archivo
                           
            .col-auto 
                img.img-a.my-3(src="@/assets/curso/images/tema3/img_38.svg" alt="", style="width:380px; display:inline-block; margin:auto 6rem;").img-fluid

            .row.mt-5.mb-4
              .col-lg-6
                a.anexo.mt-4.mb-lg-0(href="https://www.sic.gov.co/sites/default/files/normatividad/Resolucion_8934_2014.pdf" target="_blank")
                    .anexo__icono
                      img(src="@/assets/template/icono-link.svg")
                    .anexo__texto
                      p Enlace web. Resolución 8934 de 2014            
    hr     

  Muestras

</template>

<script>
export default {
  name: 'Tema3',
  data: () => ({
    // variables de vue
  }),
}
</script>

<style lang="sass" scoped></style>
