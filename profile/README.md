<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0a0a0a,55:141b2d,100:56b8d4&height=190&section=header&text=Trainity&fontColor=ffffff&fontSize=56&fontAlignY=40&desc=Training%20Operating%20System%20for%20Coaches%20and%20Athletes&descAlignY=67" alt="Trainity banner" />

### Training operating system para entrenadores y atletas

<a href="https://git.io/typing-svg">
  <img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=600&size=20&pause=1500&color=56B8D4&center=true&vCenter=true&width=900&lines=Coach+Ops;Session+Logging;Metrics+and+Progress;AI+Modules" alt="Trainity highlights" />
</a>

<p>
  <img src="https://img.shields.io/badge/Beta-Abierta-56b8d4?style=flat-square&labelColor=0f172a" alt="Beta abierta" />
  <img src="https://img.shields.io/badge/Frontend-React%2019%20%2B%20Vite-56b8d4?style=flat-square&labelColor=0f172a" alt="Frontend" />
  <img src="https://img.shields.io/badge/Backend-Express%205-56b8d4?style=flat-square&labelColor=0f172a" alt="Backend" />
  <img src="https://img.shields.io/badge/Database-MongoDB-56b8d4?style=flat-square&labelColor=0f172a" alt="Database" />
  <img src="https://img.shields.io/badge/Contracts-Zod-56b8d4?style=flat-square&labelColor=0f172a" alt="Contracts" />
  <img src="https://img.shields.io/badge/Focus-Mobile%20Logging-56b8d4?style=flat-square&labelColor=0f172a" alt="Mobile logging" />
</p>

<p>
  <img src="https://img.shields.io/badge/Audience-Coaches-111827?style=flat-square&labelColor=0f172a&color=1f2937" alt="Coaches" />
  <img src="https://img.shields.io/badge/Audience-Athletes-111827?style=flat-square&labelColor=0f172a&color=1f2937" alt="Athletes" />
  <img src="https://img.shields.io/badge/Mode-Desktop--first%20Ops-111827?style=flat-square&labelColor=0f172a&color=1f2937" alt="Desktop first ops" />
  <img src="https://img.shields.io/badge/Mode-Mobile--first%20Sessions-111827?style=flat-square&labelColor=0f172a&color=1f2937" alt="Mobile first sessions" />
  <img src="https://img.shields.io/badge/Look-Dark--first-111827?style=flat-square&labelColor=0f172a&color=1f2937" alt="Dark first" />
</p>

</div>

---

## Trainity

Trainity es una plataforma de entrenamiento construida para centralizar rutinas, sesiones y metricas en un solo sistema. La direccion del producto es clara: menos friccion operativa, mas claridad y mejor ejecucion en el entrenamiento real.

Se esta desarrollando como un `training operating system` para entrenadores, clientes y atletas independientes. La mayor parte del codigo de aplicacion sigue siendo privada mientras el producto evoluciona. Este perfil publico existe para compartir la direccion del proyecto, su arquitectura y sus principios.

> El objetivo no es hacer otra app de fitness generica.
> El objetivo es construir software que sirva durante una sesion real, en una operativa real y con decisiones reales.

## Por Que Existe

El entrenamiento serio sigue teniendo demasiado ruido operativo:

- rutinas repartidas entre mensajes, notas y hojas de calculo
- logging lento cuando deberia ser inmediato
- metricas dispersas o dificiles de interpretar
- herramientas bonitas para demo, pero torpes en uso diario

Trainity se esta construyendo para cerrar ese hueco con un enfoque claro:

- `desktop-first` donde el entrenador necesita gestion
- `mobile-first` donde el atleta necesita velocidad
- arquitectura limpia para que el producto pueda crecer sin romperse

## Mapa Del Sistema

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Plan</h3>
      <p>Rutinas, estructura, asignacion y contexto para que la programacion no viva repartida entre herramientas.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Execute</h3>
      <p>Logging de sesiones pensado para usarse durante el entreno, no despues ni desde una interfaz torpe.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Read</h3>
      <p>Metricas y progreso con lectura operativa para decidir el siguiente paso con rapidez.</p>
    </td>
  </tr>
</table>

## Para Quien

<table>
  <tr>
    <td width="33%" valign="top">
      <h3>Trainer</h3>
      <p>Crea rutinas, asigna clientes y revisa progreso desde una operativa pensada para desktop.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Client</h3>
      <p>Recibe rutinas, registra sesiones y reporta contexto de entrenamiento con la menor friccion posible.</p>
    </td>
    <td width="33%" valign="top">
      <h3>Independent</h3>
      <p>Gestiona sus propias rutinas y sesiones con una experiencia enfocada en consistencia y progreso.</p>
    </td>
  </tr>
</table>

## Superficies Del Producto

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>Coach Ops</h3>
      <p>Creacion de rutinas, asignacion, seguimiento y control operativo para entrenadores que trabajan con multiples atletas.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Session Logging</h3>
      <p>Registro de sesiones pensado para tocar, confirmar y seguir. Menos inputs inutiles. Mas continuidad durante el entreno.</p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>Metrics</h3>
      <p>Volumen, adherencia, progreso por ejercicio y lectura del bloque de entrenamiento sin ruido analitico.</p>
    </td>
    <td width="50%" valign="top">
      <h3>AI Modules</h3>
      <p>Revision de video y feedback asistido como modulos aislados del core, con prioridad para el criterio del entrenador.</p>
    </td>
  </tr>
</table>

## Lo Que Resuelve

- Rutinas, sesiones y metricas en un solo lugar.
- Logging de entrenamientos pensado para uso real durante la sesion.
- Seguimiento de progreso y adherencia con lectura operativa clara.
- Base preparada para modulos de IA desacoplados del core.

## Estado Del Producto

- Registro y login con seleccion de rol.
- Creacion y edicion de rutinas.
- Asignacion de rutinas a clientes.
- Registro de sesiones con series, reps, peso y notas.
- Dashboard con metricas semanales y progreso por ejercicio.
- Alertas simples de adherencia e inactividad.

## Mapa Funcional

<p>
  <img src="https://img.shields.io/badge/Auth-Roles%20and%20Access-56b8d4?style=flat-square&labelColor=111827" alt="Auth" />
  <img src="https://img.shields.io/badge/Routines-Create%20Assign%20Import-56b8d4?style=flat-square&labelColor=111827" alt="Routines" />
  <img src="https://img.shields.io/badge/Workout%20Logs-Draft%20and%20Final-56b8d4?style=flat-square&labelColor=111827" alt="Workout Logs" />
  <img src="https://img.shields.io/badge/Metrics-Progress%20and%20Adherence-56b8d4?style=flat-square&labelColor=111827" alt="Metrics" />
  <img src="https://img.shields.io/badge/Social-Friends%20and%20Leaderboards-56b8d4?style=flat-square&labelColor=111827" alt="Social" />
  <img src="https://img.shields.io/badge/AI-Video%20Review-56b8d4?style=flat-square&labelColor=111827" alt="AI" />
</p>

## Senales De Ingenieria

<p>
  <img src="https://img.shields.io/badge/Validation-Zod-56b8d4?style=flat-square&labelColor=111827" alt="Zod" />
  <img src="https://img.shields.io/badge/Auth-JWT-56b8d4?style=flat-square&labelColor=111827" alt="JWT" />
  <img src="https://img.shields.io/badge/Security-Rate%20Limiting-56b8d4?style=flat-square&labelColor=111827" alt="Rate limiting" />
  <img src="https://img.shields.io/badge/Access-Role%20Ownership-56b8d4?style=flat-square&labelColor=111827" alt="Role ownership" />
  <img src="https://img.shields.io/badge/Database-MongoDB%20Indexes-56b8d4?style=flat-square&labelColor=111827" alt="Mongo indexes" />
  <img src="https://img.shields.io/badge/AI-Isolated%20Modules-56b8d4?style=flat-square&labelColor=111827" alt="AI modules" />
</p>

## Principios De Construccion

- `Desktop-first` para entrenadores en gestion y reporting.
- `Mobile-first` para logging de sesiones.
- Interacciones rapidas y baja friccion en flujos criticos.
- Diseno premium, claro y consistente.

## Arquitectura

```text
web (React / Vite)
        |
        v
api (Express)
        |
        v
db (MongoDB / Mongoose)
```

### Principios de sistema

- `controllers -> services -> repositories -> models`
- validacion de entrada con `Zod`
- ownership y roles de dominio explicitos
- frontend orientado a producto, no a demos bonitas
- IA aislada del core transaccional

## Tesis De Producto E Ingenieria

<table>
  <tr>
    <td width="25%" valign="top">
      <h3>Speed</h3>
      <p>El logging tiene que ser mas rapido que la duda del usuario.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Clarity</h3>
      <p>La interfaz debe explicar prioridades sin pedir esfuerzo cognitivo extra.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Discipline</h3>
      <p>Contratos, ownership y limites entre capas para poder evolucionar sin caos.</p>
    </td>
    <td width="25%" valign="top">
      <h3>Durability</h3>
      <p>Software utilizable hoy y sostenible cuando el producto se expanda.</p>
    </td>
  </tr>
</table>

## Lenguaje De Producto

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>UX</h3>
      <p>Jerarquia visual fuerte, componentes consistentes y una interfaz que responde rapido al contexto del usuario.</p>
    </td>
    <td width="50%" valign="top">
      <h3>Visual System</h3>
      <p>Dark-first, acento `#56b8d4`, tipografia IBM Plex y una direccion premium sin ruido decorativo innecesario.</p>
    </td>
  </tr>
</table>

## Tech Stack

- Frontend: `React 19`, `Vite`, `Tailwind CSS`
- Backend: `Node.js`, `Express 5`
- Base de datos: `MongoDB Atlas`, `Mongoose`
- IA local y experimental: `Ollama`

## Para Talento Tecnico

Buscamos gente que piense en producto y sistemas a la vez.

- Backend limpio y contratos robustos.
- Frontend con criterio visual y rendimiento percibido.
- Ingenieria orientada a adopcion real, no solo a shipping de features.
- Interes en tooling interno, workflows de IA y calidad de ejecucion.

## Para Partners E Inversores

Trainity no compite por volumen de contenido. La apuesta es construir infraestructura de producto para entrenamiento serio y repetible.

- Operativa clara para entrenadores.
- Experiencia movil utilizable durante el entreno.
- Arquitectura preparada para modulos premium y expansion funcional.
- Direccion de producto guiada por consistencia de sistema.

## Lo Que Compartiremos Publicamente

Aunque el codigo principal siga siendo privado por ahora, este perfil se ira usando para publicar:

- direccion de producto
- decisiones de arquitectura
- repositorios publicos auxiliares cuando tenga sentido
- puntos de entrada para colaboracion tecnica o estrategica

## Comunidad

- Profile repo: `.github`
- Website: `https://placeholder.trainity.dev`
- Waitlist: `https://placeholder.trainity.dev/waitlist`
- Contacto general: `alexmico2006@gmail.com`
- Partnerships: `alexmico2006@gmail.com`

---

<div align="center">

**Software para gente que entrena de verdad.**

</div>
