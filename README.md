# FC Barcelona – Printing Lab Signage  
### Ready for Pickup · GOAL Announcement Microsite ⚽

Este repositorio contiene un **microsite de Digital Signage** utilizado en el **Printing Lab del FC Barcelona** para anunciar visual y sonoramente cuándo un pedido personalizado está **listo para ser recogido**.

Cuando un pedido pasa a estado **“Ready for pickup”**, la pantalla:
- Actualiza el listado de pedidos
- Destaca el pedido activo
- Lanza una animación tipo **GOOOAL**
- Reproduce durante **7 segundos** el *goal song* oficial del FC Barcelona
- Refuerza la experiencia de marca con estética y escudo corporativo

Pensado para pantallas de tienda (TV / iPad / signage player).

---

## 🎯 Objetivo
- Mejorar la **experiencia en tienda** durante la recogida de camisetas personalizadas
- Dar visibilidad clara al estado del pedido
- Generar un momento emocional y reconocible (estadio / Barça)
- Integrarse fácilmente en un **CMS de signage** mediante una URL pública

---

## 🧩 Funcionalidades principales

- 📋 Listado de pedidos con estado
- ⭐ Panel “Now serving”
- ⏱️ Reloj en tiempo real + indicador LIVE
- 🔔 Detección de cambio a **Ready for pickup**
- ⚽ Animación **GOOOAL – New member to the club**
- 🎶 Reproducción de audio limitada a 7 segundos
- 🛡️ Escudo oficial del FC Barcelona (header + overlay)
- 🎉 Confetti con colores corporativos
- 🔊 Control manual de activación de sonido (requisito navegador)
- 🔁 Polling simulado (preparado para API real)

---

## 📁 Estructura del proyecto

```text
/
├─ index.html                # Microsite completo (HTML + CSS + JS)
├─ audio/
│  └─ FC_Barcelona_NEW_goal_song_25_26.mp3
└─ assets/
   └─ logo.png          # Escudo FC Barcelona (PNG recomendado)