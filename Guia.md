
# 🧠 Plan de Estudio Intensivo: Linux, LDAP, Redes y Automatización
**Duración:** 4 semanas (1 mes)  
**Objetivo:** Adquirir habilidades prácticas en administración Linux, redes, LDAP, certificados, scripting y reportería para fortalecer mi perfil profesional en sistemas.

---

## 🔷 Semana 1: Fundamentos de Linux + Redes + Firewall

### 🎯 Objetivos:
- Aprender comandos y estructuras clave de Linux.
- Comprender los fundamentos de redes.
- Aplicar configuraciones básicas de firewall en Linux.

### 📚 Temas:
- Comandos esenciales: `ls`, `cd`, `chmod`, `ps`, `top`, `systemctl`, `journalctl`, `df`, `du`.
- Gestión de usuarios y grupos: `useradd`, `passwd`, `usermod`, `groupadd`, `chown`.
- Red: conceptos de IP, máscara, gateway, DNS, puertos, TCP/UDP.
- Herramientas: `ip`, `ping`, `ss`, `netstat`, `traceroute`, `tcpdump`, `nmap`.
- Firewall básico: `ufw`, introducción a `iptables`.

### 🛠 Prácticas sugeridas:
- Instalar Ubuntu Server en VM.
- Configurar red estática y DNS.
- Crear usuarios con permisos diferenciados.
- Aplicar reglas de `ufw` para permitir SSH y bloquear otros puertos.

---

## 🔷 Semana 2: LDAP (Active Directory) + Certificados SSL/TLS

### 🎯 Objetivos:
- Integrar Linux con Active Directory vía LDAP.
- Comprender y usar certificados para aplicaciones web.

### 📚 Temas:
- ¿Qué es LDAP y cómo funciona AD?
- Herramientas: `realmd`, `sssd`, `krb5`, `ldap-utils`, `getent`, `ldapsearch`.
- Certificados SSL/TLS: `openssl`, CSR, key, CRT, CA.
- Configuración HTTPS en Apache o Nginx.

### 🛠 Prácticas sugeridas:
- Unir Linux a un dominio AD simulado o real.
- Autenticación de usuarios del dominio.
- Crear certificados autofirmados y usarlos en un servidor web.

---

## 🔷 Semana 3: Bash Scripting + BATS + Reporterías

### 🎯 Objetivos:
- Automatizar tareas administrativas con Bash.
- Crear reportes automatizados del sistema.
- Probar scripts con BATS.

### 📚 Temas:
- Scripting: variables, condicionales, bucles, funciones.
- Crontab y tareas programadas.
- Uso de BATS para pruebas de scripts.
- Reportería: CPU, RAM, disco, logs, uptime.
- Envío de reportes por email (`ssmtp`, `mail`, `mutt`).

### 🛠 Prácticas sugeridas:
- Script `monitor_disco.sh` para verificar espacio.
- Script `check_usuarios.sh` para listar y verificar cuentas activas.
- Pruebas con BATS para validar salida de scripts.
- Cronjob para enviar reportes del sistema diariamente.

---

## 🔷 Semana 4: Proyecto Final + GitHub + CV Técnico

### 🎯 Objetivos:
- Aplicar todos los conocimientos adquiridos en un proyecto integrado.
- Subir todo a GitHub y actualizar mi CV técnico.

### 📚 Proyecto Final:
- Crear un entorno con:
  - Integración a LDAP/AD.
  - Configuración de reglas de firewall.
  - Servidor web seguro con HTTPS.
  - Automatización y reportería por scripts.
- Documentar todo en un `README.md`.

### 🛠 Actividades finales:
- Subir scripts y configuraciones a GitHub.
- Crear secciones técnicas en el CV:
  - Linux Sysadmin básico
  - LDAP/AD integration
  - Bash scripting & reportería
  - Seguridad básica con firewall y certificados
- Publicar experiencia técnica en LinkedIn.

---

## 🧩 Recursos recomendados:
- 📘 [The Linux Command Line](https://linuxcommand.org/tlcl.php)
- 📘 [Linux Essentials - Cisco Networking Academy](https://skillsforall.com)
- 🧪 [BATS Testing Framework](https://github.com/bats-core/bats-core)
- 🔐 [OpenSSL Guide](https://www.openssl.org/docs/man1.1.1/man1/openssl.html)
- 🎓 [Red Hat LDAP Integration Guide](https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/configuring_authentication_and_authorization/index)

---

## ✅ Resultado esperado:
Al finalizar este plan, seré capaz de:
- Administrar un sistema Linux a nivel básico-intermedio.
- Integrar usuarios con LDAP/AD.
- Aplicar conceptos clave de redes y seguridad (firewall).
- Automatizar tareas comunes con Bash y probarlas con BATS.
- Crear reportería útil para monitoreo de sistemas.
- Mostrar todo esto en mi portafolio GitHub y en entrevistas técnicas.

---
