# finanzas-banco

Página puente para la app personal **Finanzas** (iOS).

Tras autorizar el acceso de solo lectura a la cuenta bancaria (banca abierta, vía Enable Banking),
el banco redirige a esta página, que reenvía a la app (`finanzas://banco?...`).

No contiene ni guarda ningún dato: solo pasa los parámetros de la URL a la app.
