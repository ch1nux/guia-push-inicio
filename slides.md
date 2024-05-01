---
theme: ./theme
title: Guía de Inicio de Push Protocol
info: |
  Guia de Inicio de push Protocol.
  Esta guía es para entender en líneas generales
  como funciona la arquitectura de servicios de Push Protocol
  Así como también para entender que es un protocolo.
class: text-center
highlighter: shiki
drawings:
  persist: false
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
fonts:
  provider: none
  sans: Strawford
layout: intro
---

<img class="mx-auto" src="/images/Push-Logo-Standard-White.svg" width="300" />

# Guia de Inicio de Push Protocol

<p class="text-3xl">...explicado con memes (?) 🤔</p>

---

<img class="my-auto mx-auto" src="/images/memes-memes-everywhere.jpg" />

---

# Esta es una guía para entender:

- 🤝🏼 ¿Qué es un protocolo?
- 🔔 ¿Qué es Push Protocol?
- ✅ Lo que puede hacer Push por nosotros.
  - 📢 Push Notificaciones.
  - ✉ Push Mensajería.
  - 🤑 Tokenomics [$PUSH][1]
- 📝 Documentacion importante.


[1]:https://push.org/docs/tokenomics/deepdive/$push/

---
class: text-center
---

# ¡Manos a la ubre!

<img
  src="/images/ubre.jpg"
  class="mx-auto mt-10"
  width="500"
  alt="Ubre"
/>

---
layout: intro
---

# ご理解のほどよろしくお願いいたします。 おめでとう！ これで、プロトコルが何であるかを簡単に理解できました。

---
class: text-center
---

# ???

<img src="https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExM2IyOTNobjZ2MjdhMzNrdDFzMTNuNXB2MmJxbnRjcnRnZHg0MjBnYiZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/xL7PDV9frcudO/giphy.gif" alt="wtf" width="400" class="my-auto mx-auto" />

---
layout: image-right

image: /images/hazmat-nuclear-plant.gif
---

# En general un protocolo...

- Así como un idioma, es un conjunto de normas coherentes que se usan para la comunicación.
- Tiene un contexto y unos signos propios.
- Solo se entiende cuando se establece la comunicación.
- No solo se refiere a la comunicación humana, también puede ser simbólica (lenguaje de señas, lenguaje técnico, etc.).
- Es lo que hace que Homero no se contamine de radiación 😅.

---
class: text-center
---

<img class="mx-auto mt-20" src="/images/Push-Logo-Standard-White.svg" width="300" />

<h1 class="py-8">¿Qué es Push Protocol?</h1>

<p class="w-3/4 mx-auto text-center">Es <strong>el</strong> protocolo nativo de web3 que facilita la comunicación entre wallets y aplicaciones, mediante el envío de notificaciones y mensajes multimedia.</p>

---
layout: intro
class: text-center
transition: slide-up
---

# Elige una opción para continuar.

<div class="grid grid-cols-3 grid-rows-1 gap-20">
  <Card :slide="10">
    Push Notificaciones
  </Card>

  <Card :slide="11">
    Push Mensajería
  </Card>

  <Card :slide="13">
    Tokenomics <a href="https://push.org/docs/tokenomics/deepdive/$push/" target="_blank">$PUSH</a>
  </Card>
</div>

---
layout: two-cols
transition: slide-up
---

# Push Notificaciones

- Avisos predeterminados de difusión masiva
- Eventos personalizados
- Eventos programados
- [Servidor de Notificaciones PUSH](https://www.arimetrics.com/glosario-digital/notificacion-push)
- Compatible con aplicaciones web2
- Requiere suscripción
- Requiere sincronizar wallets en la app de [Push](https://app.push.org)
- Requiere la creación de un canal de notificaciones

[Documentación Notificaciones Push Protocol](https://push.org/docs/notifications/)

<Card :slide="9" class="text-center w-48">Volver</Card>

::right::

<img class="mx-auto mt-8" src="https://media1.tenor.com/m/wN4wfxwDhFIAAAAC/bart-simpson-i-am-so-great.gif" alt="bart-pushing" />

---
layout: intro
class: text-center
transition: slide-up
---

# Push Mensajería

<div class="grid grid-cols-3 gap-4">
<Card>Push Chat</Card>
<Card>Push Video</Card>
<Card>Push Spaces</Card>
<img src="https://media1.tenor.com/m/cVdLW-0baz0AAAAd/cats-chat.gif" alt="chat" />
<img src="https://media1.tenor.com/m/vHU4Whpw8Z0AAAAd/bird-call-zoom.gif" alt="video" />
<img src="https://media1.tenor.com/m/5zFRI6HIpREAAAAC/music-listening.gif" alt="spaces" />
</div>

---
layout: two-cols
---

<h1 class="mt-8">Push Mensajería</h1>

- Permite Streaming multimedia (video y/o audio, mono o multicanal)
- No requiere suscripción, solo la app de Push 🤝🏼
- [API](https://www.npmjs.com/package/@pushprotocol/restapi#for-spaces) para desarrollar chats o integraciones compatibles con otras apps ⚙
- La escalabilidad es garantizada mediante Push Nodes ✉
- Mensajería **privada** (requiere autorización) 🔒

[Documentación Mensajería Push Protocol](https://push.org/docs/chat/)

<Card :slide="9" class="text-center w-48">
Volver
</Card>

::right::

<img src="https://media1.tenor.com/m/z9MoFqbpScIAAAAd/private-glass.gif" alt="privacy" class="mx-auto mt-10" />

---
layout: two-cols
---

# Tokenomics $PUSH

- El token nativo se utiliza para habilitar canales de comunicación, gobernanza digital, seguridad e incentivos.
- Es agnóstico, por lo que habilita a otras blockchains o protocolos para establecer comunicación.
- Compatible con cualquier billetera compatible con ERC20
- Para el 2024 se han enviado/desarrollado:
  - Más de 50 millones de mensajes.
  - Más de 150 mil suscriptores con canales activos.
  - Más de 500 integraciones

::right::

<img src="/images/pushprotocol-push-protocol-2.gif" alt="nodes" class="mt-25" />

[Documentación Tokenomics](https://push.org/docs/tokenomics/)

<Card :slide="14" class="text-center w-48 mt-10">Siguiente</Card>

---

<img src="https://push.org/assets/images/pushecosys-075a03b3ca7dc38ba0b68326447be1d2.png" alt="tokenomics" />

---
class: text-center
transition: slide-left
---

# Roadmap Push 2024

<img class="mx-auto w-2/3" src="/images/roadmap-push-2024.png" />

---
layout: intro
class: text-center
---

<div class="flex w-1/2 mx-auto align-center">
<img class="mt-20" src="/images/Push-Logo-Standard-White.svg" width="300" />
<img src="/images/Bell_10.png" alt="keep-pushing" width="200" />
</div>

<h1>Keep Pushing!</h1>

<div class="flex w-1/2 mx-auto align-center justify-between">
<div bg="white" w="20" h="8" rounded="md"><a href="https://github.com/push-protocol/" target="_blank"><logos-github class="w-20 h-8 p-1" /></a></div>
<div bg="white" w="20" h="8" rounded="md"><a href="https://twitter.com/pushprotocol" target="_blank"><logos-twitter class="w-20 h-8 p-1" /></a></div>
<div bg="white" w="20" h="8" rounded="md"><a href="https://t.me/epnsproject" target="_blank"><logos-telegram class="w-20 h-8 p-1" /></a></div>
<div bg="white" w="20" h="8" rounded="md"><a href="https://discord.com/invite/pushprotocol" target="_blank"><logos-discord class="w-20 h-8 p-1" /></a></div>
</div>

