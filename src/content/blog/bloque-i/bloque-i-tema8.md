---
title: "Bloque I — Tema 8: Sociedad de la información, identidad y firma electrónica"
description: "LSSI, eIDAS y Ley 6/2020: servicios de confianza, firmas, DNIe y Agenda Digital España 2026."
pubDate: 2026-01-16
heroImage: "./bloque-i-tema8.jpg"
tags: ["TAI", "Bloque I", "Tema 8"]
---

# Bloque I — Tema 8: Sociedad de la información, identidad y firma electrónica

Apuntes sobre la LSSI, el marco eIDAS, la firma electrónica y el DNIe.

## 1. Ley 34/2002 (LSSI-CE)

### Objeto
- Régimen jurídico de los **servicios de la sociedad de la información** y del comercio electrónico.

### Prestadores de servicios
- Persona física o jurídica que presta servicios por vía electrónica.
- Obligación de información: identidad, registro, NIF, códigos de conducta y precios.

### Comunicaciones comerciales
- Deben ser identificables.
- Prohibido ocultar la identidad o enviar sin autorización.
- Obligación de permitir oposición a comunicaciones (baja).

### Contratación electrónica
- Contratos válidos con consentimiento.
- Información previa y acuse de recibo posterior.

### Cookies
- Requieren consentimiento informado.

### Sanciones (según temario)
- Infracciones leves, graves y muy graves, con multas graduadas.

## 2. Marco jurídico de identidad y firma electrónica

Normativa principal:
- **Reglamento (UE) 910/2014 (eIDAS)**.
- **Ley 6/2020** reguladora de determinados aspectos de servicios electrónicos de confianza.
- Leyes 39/2015 y 40/2015 para procedimientos administrativos.

## 3. Conceptos básicos

- **Firma electrónica**: datos electrónicos anexos a otros datos.
- **Firma electrónica avanzada**: vinculada al firmante, permite identificarlo y detectar cambios.
- **Firma electrónica cualificada**: avanzada + certificado cualificado; equivalente a firma manuscrita.
- **Sello electrónico**: garantiza origen e integridad para personas jurídicas.
- **Sello de tiempo**: vincula datos con fecha y hora verificable.

## 4. Infraestructura de clave pública (PKI)

- **CA (Autoridad de Certificación)**: emite certificados.
- **RA (Autoridad de Registro)**: verifica la identidad.
- **VA (Autoridad de Validación)**: comprueba vigencia (CRL/OCSP).
- **TSA**: sellado de tiempo.

## 5. Prestadores de servicios de confianza

- **Cualificados** y **no cualificados**.
- Deben adoptar medidas de seguridad y notificar incidentes.

## 6. Certificados electrónicos

- Certificados de firma, sello y autenticación.
- Vigencia máxima habitual: **5 años** (según Ley 6/2020).
- Revocación o suspensión según causas regladas.

## 7. DNI electrónico (RD 1553/2005)

- DNI que acredita identidad electrónica y permite firmar.
- No cifra datos del usuario: **solo firma electrónica**.
- Certificados: **autenticación** y **firma**.
- Validez del DNIe: 2 años (<5 años), 5 años (<30), 10 años (<70), permanente (>=70).
- PIN personal y uso con dispositivos compatibles.

## 8. Certificados FNMT-RCM (resumen)

- Persona física (ciudadano).
- Representante (persona jurídica o entidad sin personalidad).
- Sector público (sede, sello, SSL/TLS).
- Certificados de componente (SAN multidominio, wildcard, etc.).

## 9. Agenda Digital para España (España Digital 2026)

- Hoja de ruta alineada con la Brújula Digital 2030.
- 3 dimensiones, 12 ejes y 42 medidas.
- Metas 2025 destacadas:
  - Conectividad 100 Mbps: 100% cobertura.
  - 5G: 100% del espectro.
  - Ciberseguridad: 20.000 especialistas.
  - IA y Big Data: 25% empresas.
  - Digitalización AAPP y PYMEs.
  - Competencias digitales básicas: 80% población.

## Esquema de repaso

- LSSI: obligaciones, comunicaciones comerciales y sanciones.
- eIDAS y Ley 6/2020: firma, sellos y prestadores.
- PKI: CA, RA, VA, TSA.
- DNIe: certificados y validez.
- Agenda Digital España 2026: ejes y metas clave.

## Errores típicos en test

- Confundir firma avanzada con firma cualificada.
- Olvidar que el DNIe no cifra datos, solo firma.
- Mezclar obligaciones de LSSI con normativa de protección de datos.
- Creer que todos los prestadores de confianza son cualificados.

## Mini-test (10 preguntas)

1. ¿Qué norma regula la identificación electrónica en la UE?
A) LSSI
B) Reglamento eIDAS
C) Ley 39/2015
D) Ley 19/2013

2. ¿Cuál es la firma con efectos equivalentes a la manuscrita?
A) Electrónica simple
B) Electrónica avanzada
C) Electrónica cualificada
D) Sello electrónico

3. ¿Qué autoridad emite certificados digitales?
A) RA
B) CA
C) VA
D) TSA

4. ¿Qué ley complementa el eIDAS en España?
A) Ley 6/2020
B) Ley 40/2015
C) Ley 50/1997
D) LO 2/1979

5. ¿Qué certificado del DNIe permite autenticación?
A) Certificado de firma
B) Certificado de autenticación
C) Certificado de sello
D) Certificado SSL

6. ¿Qué obligación impone la LSSI en comunicaciones comerciales?
A) Envío sin consentimiento
B) Identificación clara del mensaje
C) Notificación a la AEPD
D) Registro previo obligatorio

7. ¿Qué elemento de PKI verifica la validez de certificados en línea?
A) RA
B) VA
C) TSA
D) CA

8. ¿Cuál es la vigencia máxima general de certificados según Ley 6/2020?
A) 2 años
B) 3 años
C) 5 años
D) 10 años

9. ¿Qué eje de España Digital 2026 busca 100% cobertura >100 Mbps?
A) Ciberseguridad
B) Conectividad digital
C) IA y dato
D) Competencias digitales

10. ¿Qué son las cookies en LSSI?
A) Certificados electrónicos
B) Identificación de usuarios sin consentimiento
C) Datos recuperables con consentimiento informado
D) Identificadores públicos obligatorios

### Soluciones

1. B
2. C
3. B
4. A
5. B
6. B
7. B
8. C
9. B
10. C
