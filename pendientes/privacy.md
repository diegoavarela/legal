---
title: Pendientes - Privacy Policy
---

# Privacy Policy

**Pendientes: Lists & Focus**

**Last updated: October 26, 2026**

---

## Overview

Pendientes ("the App") is developed by Diego Varela. This Privacy Policy explains how we handle your information when you use the App on iPhone and Mac.

**The short version: We don't collect, store, or share any of your personal data — unless you turn on Agents, which is optional and off by default (see below).**

---

## Data Collection

### What We Don't Collect

- We do not collect personal information
- We do not have accounts or servers of our own
- We do not track your usage
- We do not use analytics
- We do not serve advertisements
- We do not share any data with third parties

### Data That Stays on Your Device and Your iCloud

- **Lists and tasks**: Stored on your device and in your personal iCloud account (Apple's CloudKit), so they sync across your devices. The developer can't access them.
- **Shared lists**: If you share a list, Apple makes it available to the people you invite, through iCloud.
- **Settings**: Stored on your device and in your iCloud key-value storage, so they sync across your devices.
- **Calendar (optional)**: If you turn it on, the App reads today's events to show them and creates events only when you ask it to. This data never leaves your device or your Apple account.
- **Reminders (optional)**: If you import from Reminders, the App only reads them, on your device.
- **Face ID / Touch ID**: Used only to open Private. The App never receives your biometric data.
- **Notifications**: Reminders are local notifications scheduled on your device.
- **Export**: The file you export stays wherever you save it and doesn't include Private.

---

## Agents (optional, off by default)

If you turn on **Settings → Agents**, you can connect AI assistants (for example Claude, ChatGPT, Grok or Meta Muse) so they can read your lists and add things for you. To make that work:

- The App sends our server (hosted on Vercel, with an Upstash Redis database) a copy of **only the lists you choose**, your Focus and what's due today. **Private is never sent.** This copy is stored **encrypted** and replaced every time something changes.
- Requests from your assistants (for example "add milk to Groceries") are kept on our server only until your device applies them, and then deleted.
- We store a list of the assistants you connected, so you can see and disconnect them in the App.
- To wake your device when an assistant asks for something, we store your device's push notification token.
- What the assistant does with the information it reads is governed by that assistant's own privacy policy.

We don't use this data for anything else, we don't sell it and we don't share it. **Turning Agents off deletes everything from our server immediately.** If no device contacts the server for 30 days, the copy is deleted automatically.

---

## Deleting Your Data

You can delete everything by removing the App and its iCloud data (Settings → [your name] → iCloud → Manage Storage).

---

## Contact

If you have questions about this Privacy Policy, contact: **varelad@gmail.com**

---

# Política de privacidad (español)

**Pendientes no recopila datos**, salvo que actives Agentes (opcional, ver abajo). No hay cuentas, publicidad, analíticas ni rastreo.

- **Tus listas y tareas** se guardan en tu dispositivo y en **tu iCloud** (CloudKit de Apple), para sincronizarlas entre tus equipos. El desarrollador no tiene acceso a ellas.
- **Listas compartidas:** si compartís una lista, Apple la pone a disposición de las personas que invitás, a través de iCloud.
- **Calendario (opcional):** si lo activás, la app lee tus eventos de hoy para mostrarlos y crea eventos solo cuando se lo pedís. Esos datos no salen de tu dispositivo ni de tu cuenta de Apple.
- **Recordatorios (opcional):** si importás desde Recordatorios, la app solo los lee, en tu dispositivo.
- **Face ID / Touch ID:** se usa solo para abrir Privado. La app nunca recibe tus datos biométricos.
- **Avisos:** son notificaciones locales, programadas en tu dispositivo.
- **Exportar:** el archivo que exportás queda donde vos lo guardes y no incluye Privado.
- **Agentes (opcional, apagado por defecto):** si activás Ajustes → Agentes para conectar asistentes como Claude, ChatGPT, Grok o Meta Muse, la app manda a nuestro servidor (Vercel y Upstash Redis) una copia **cifrada** de **solo las listas que elijas**, el Foco y lo de hoy. **Privado nunca se manda.** Los pedidos de tus asistentes quedan en el servidor hasta que tu dispositivo los aplica, y después se borran. También guardamos qué asistentes conectaste y el token de avisos de tu dispositivo, para despertarlo. Lo que haga cada asistente con lo que lee se rige por su propia política. **Al desactivar Agentes se borra todo del servidor al instante**, y si ningún dispositivo se conecta en 30 días, se borra solo.

Podés borrar todo eliminando la app y sus datos de iCloud (Ajustes → [tu nombre] → iCloud → Administrar almacenamiento).

Contacto: **varelad@gmail.com**
