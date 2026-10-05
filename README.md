# Turnero 💈

Web para reservar turnos de peluquería.

- **Peluqueros:** cargan su local, ubicación en el mapa, servicios con precio y duración, y sus días y horarios de atención. Ven su agenda de turnos reservados.
- **Clientes:** buscan turnos libres filtrando por día, barrio, servicio, precio máximo y franja horaria (mañana, tarde, noche), los ven en un mapa y reservan con un clic. Pueden ver y cancelar sus turnos.

Todo el programa está en un solo archivo: `index.html`.

## Cómo probarla en tu computadora

Hacé doble clic en `index.html` y se abre en tu navegador. No hace falta instalar nada.

Cuentas de prueba (contraseña `1234` en todas):

| Email                | Tipo de cuenta |
|----------------------|----------------|
| cliente@demo.com     | Cliente        |
| peluquero@demo.com   | Peluquero      |

También podés crear cuentas nuevas desde "Crear cuenta".

## Cómo subirla a GitHub (sin usar comandos)

1. Creá una cuenta en [github.com](https://github.com) si no tenés.
2. Arriba a la derecha tocá **+** y después **New repository**.
3. Poné de nombre `turnero-peluqueria`, dejalo en **Public** y tocá **Create repository**.
4. En la página que aparece, tocá el link **uploading an existing file**.
5. Arrastrá los archivos `index.html` y `README.md` y tocá **Commit changes**.

## Cómo publicarla con un link (gratis)

1. En tu repositorio, entrá a **Settings** y en el menú de la izquierda a **Pages**.
2. En **Branch** elegí `main`, carpeta `/ (root)`, y tocá **Save**.
3. Esperá uno o dos minutos y recargá la página. Va a aparecer tu link, con esta forma:
   `https://TU_USUARIO.github.io/turnero-peluqueria/`

## Importante: limitación de esta versión

Los datos (cuentas, servicios, turnos) se guardan **en el navegador de cada persona**. Eso significa que si un peluquero carga sus horarios en su celular, un cliente desde otra computadora no los ve. Sirve para mostrar cómo funciona la app y como proyecto de portfolio, pero no para usarla con clientes reales.

Las contraseñas tampoco están protegidas: no uses contraseñas reales.

## Próximos pasos

- Conectarla a una base de datos en internet (por ejemplo, [Supabase](https://supabase.com), que es gratis) para que todos vean los mismos datos y el login sea seguro.
- Avisos por email o WhatsApp cuando se reserva o cancela un turno.
- Reseñas y fotos de cada peluquería.
- Pago de seña online (por ejemplo, con Mercado Pago).

## Tecnologías

HTML, CSS y JavaScript sin frameworks. Mapa con [Leaflet](https://leafletjs.com).
