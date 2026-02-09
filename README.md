# Stencil Ink — Privacy Policy / Política de Privacidad

**Last updated / Última actualización:** 2026-02-09

---

## 🇪🇸 Política de Privacidad (Español)

Stencil Ink (“la App”) respeta tu privacidad. Esta Política explica qué información se trata cuando usas la App, para qué se usa y con quién se comparte.

### 1) Responsable y contacto
**Responsable:** [Matias Torres / Sacrify_101]  
**Contacto:** [matiastorres.a@hotmail.com]

### 2) Qué información tratamos

#### A) Imágenes del dispositivo
La App permite seleccionar imágenes almacenadas en tu iPhone/iPad para:
- generar stencils (plantillas) para tatuaje o dibujo
- mejorar calidad de imagen (super-resolución)

La App **no accede a tus fotos** sin tu acción. Tú eliges qué imágenes usar.

#### B) Cuenta, identificadores y créditos (Firebase Auth + Firestore)
La App usa autenticación (por ejemplo, “Sign in with Apple”) y guarda datos en Firestore para que el sistema de créditos funcione y pueda sincronizarse entre dispositivos.

En Firestore podemos almacenar:
- **uid** (identificador del usuario en Firebase)
- **publicUserId** (ID público tipo “INK-XXXXXX”)
- **walletBalance** (saldo de créditos)
- **createdAt / updatedAt** (fechas de creación/actualización)
- Registros relacionados con compras y operaciones (por ejemplo, en subcolecciones como **purchases** u otras necesarias para el funcionamiento y control de abusos)

También puede existir una colección de mapeo (por ejemplo **publicIds**) para relacionar `publicUserId → uid` y permitir soporte/sincronización.

No solicitamos tu nombre real, dirección, número de teléfono ni accedemos a tus contactos.

#### C) Inicio de sesión con Apple (Sign in with Apple)
Si eliges iniciar sesión con Apple, se usa para:
- vincular y **sincronizar créditos** entre dispositivos (iPhone/iPad)
- mejorar la seguridad y continuidad del servicio

Stencil Ink recibe de Apple un **identificador único** asociado a tu cuenta de Apple para esta App (y, si tú lo permites, un correo como el “email privado/relay” de Apple). No accedemos a tu contraseña de Apple.

#### D) Analítica (Firebase Analytics)
La App utiliza Firebase Analytics para entender el uso general de la App y mejorarla. Puede recoger información como:
- eventos de uso (por ejemplo, pantallas vistas, interacciones)
- información aproximada del dispositivo y de la app (modelo, versión iOS, versión de la app)
- datos técnicos agregados (rendimiento básico)

No usamos Analytics para conocer tu identidad real.

#### E) Procesamiento local (Real-ESRGAN)
Algunas mejoras de imagen pueden ejecutarse **localmente en tu dispositivo** mediante modelos integrados en la App (por ejemplo, Real-ESRGAN). En este caso, la imagen **se procesa en tu dispositivo**.

#### F) Procesamiento remoto (Replicate) — filtros de stencil
Al usar ciertos filtros de stencil, la imagen puede enviarse a un proveedor externo (Replicate) para procesarla y devolverte el resultado.

- Se envía solo la imagen necesaria para generar el resultado solicitado
- Se usa únicamente para proporcionar la función solicitada
- No vendemos tus imágenes ni las usamos para publicidad

**Nota:** Como cualquier servicio remoto, el proveedor puede conservar temporalmente datos técnicos de la solicitud para operar y prevenir abuso.

#### G) Publicidad (Google AdMob)
La App muestra:
- **banners**
- **anuncios recompensados (rewarded)** para obtener mejoras sin gastar créditos

AdMob puede tratar datos como:
- identificadores del dispositivo (p. ej., ID de publicidad)
- IP aproximada
- eventos de rendimiento del anuncio (impresiones, clics)
- señales antifraude y diagnóstico

### 3) Con quién compartimos información
Solo compartimos información con proveedores necesarios para operar la App:
- Apple (Sign in with Apple)
- Firebase (autenticación, base de datos, analítica)
- Replicate (procesamiento remoto cuando eliges esos filtros)
- Google AdMob (publicidad)

No vendemos tus datos.

### 4) Retención
Intentamos minimizar datos:
- Datos de cuenta/créditos (uid, publicUserId, walletBalance, timestamps y registros asociados) se conservan mientras sea necesario para ofrecer el servicio y sincronizar créditos.
- Los datos de analítica se tratan de forma agregada/estadística.
- Los datos tratados por proveedores externos (Ads/Replicate) pueden retenerse según sus propias políticas para operar el servicio y prevenir abuso.

### 5) Seguridad
Aplicamos medidas razonables para proteger la información, pero ningún sistema es 100% infalible. Evita usar imágenes extremadamente sensibles si vas a usar filtros remotos.

### 6) Privacidad de menores
La App no está dirigida a menores de 13 años (o edad mínima equivalente). Si crees que un menor nos ha proporcionado información personal, contáctanos.

### 7) Cambios en esta Política
Podemos actualizar esta Política. Publicaremos la nueva versión con la fecha actualizada.

---

## 🇬🇧 Privacy Policy (English)

Stencil Ink (“the App”) respects your privacy. This Policy explains what information is processed when you use the App, how it’s used, and who it may be shared with.

### 1) Controller and contact
**Controller:** [Matias Torres / Sacrify_101]  
**Contact:** [matiastorres.a@hotmail.com]

### 2) Information we process

#### A) Photos/images on your device
The App lets you select images stored on your iPhone/iPad to:
- generate tattoo/drawing stencils
- enhance image quality (super-resolution)

The App **does not access your photos** unless you choose them.

#### B) Account, identifiers & credits (Firebase Auth + Firestore)
The App uses authentication (e.g., Sign in with Apple) and stores data in Firestore so the credits system works and can sync across devices.

In Firestore we may store:
- **uid** (Firebase user identifier)
- **publicUserId** (public ID such as “INK-XXXXXX”)
- **walletBalance** (credits balance)
- **createdAt / updatedAt** timestamps
- records related to purchases and operations (e.g., subcollections like **purchases** and other service data required for correct operation and abuse prevention)

A mapping collection (e.g., **publicIds**) may be used to map `publicUserId → uid` for syncing/support purposes.

We do not ask for your real name, address, phone number, and we do not access your contacts.

#### C) Sign in with Apple
If you choose Sign in with Apple, it is used to:
- link and **sync credits** across devices (iPhone/iPad)
- provide a more secure and consistent experience

We receive an Apple-provided unique identifier for your account in this App (and, if you allow it, an email such as Apple’s private relay). We never receive your Apple password.

#### D) Analytics (Firebase Analytics)
The App uses Firebase Analytics to understand general app usage and improve it. It may collect:
- usage events (e.g., screen views, interactions)
- device/app information (device model, iOS version, app version)
- aggregated technical metrics

We do not use Analytics to learn your real-world identity.

#### E) On-device processing (Real-ESRGAN)
Some image enhancements can run **locally on your device** using models embedded in the App (e.g., Real-ESRGAN). In these cases, the image is processed **on your device**.

#### F) Remote processing (Replicate) — stencil filters
When you use certain stencil filters, the image may be sent to a third-party provider (Replicate) to generate the result and return it to the App.

- Only the image required to produce the requested output is sent
- It is used solely to provide the feature you requested
- We do not sell your images or use them for advertising

**Note:** Like any remote service, the provider may temporarily retain technical request data for operations and abuse prevention.

#### G) Advertising (Google AdMob)
The App may display:
- **banner ads**
- **rewarded ads** to unlock enhancements without spending credits

AdMob may process data such as:
- device identifiers (e.g., advertising ID)
- approximate IP address
- ad performance events (impressions, clicks)
- anti-fraud and diagnostics signals

### 3) Sharing with third parties
We only share information with providers necessary to operate the App:
- Apple (Sign in with Apple)
- Firebase (auth, database, analytics)
- Replicate (remote processing when you choose those filters)
- Google AdMob (advertising)

We do not sell your data.

### 4) Retention
We aim to minimize data:
- Account/credits data (uid, publicUserId, walletBalance, timestamps and related records) is kept as needed to provide the service and sync credits.
- Analytics data is processed in an aggregated/statistical manner.
- Third-party providers (Ads/Replicate) may retain data according to their own policies for service operation and abuse prevention.

### 5) Security
We take reasonable measures to protect information, but no system is 100% secure. Avoid using highly sensitive images when using remote filters.

### 6) Children’s privacy
The App is not intended for children under 13 (or the minimum equivalent age). If you believe a child provided personal information, contact us.

### 7) Changes to this Policy
We may update this Policy. The new version will be posted with an updated “Last updated” date.
