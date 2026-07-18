# Pablo José Schafran
## Unidad 2 · Fortaleciendo el sistema: Hardening en Windows y Linux

### 1. WINDOWS

#### A. Creación de un usuario NO-administrador

Un error frecuente que cometen muchos usuarios principiantes es emplear habitualmente la computadora con una cuenta que posee permisos de administrador. En caso de que un virus o malware acceda al sistema bajo esa cuenta, este adquiriría los mismos privilegios elevados, pudiendo causar daños significativos e incluso comprometer por completo el funcionamiento del equipo.

Para mitigar este riesgo, es recomendable utilizar al menos dos cuentas diferenciadas: una cuenta de administrador (protegida con contraseña robusta) y una cuenta estándar para uso diario. **No desactivar nunca el UAC**.

![Creación de usuario no administrador](images/1000000100000780000003F14466278E.png)

#### B. Verificación de que Windows Update está funcionando

Mantener Windows actualizado es una de las medidas más importantes de seguridad.

![Verificación Windows Update](images/1000000100000780000003F15728F431.png)

#### C. Desactivación específica de SMB 1.0

SMB 1.0 es un protocolo obsoleto responsable de vulnerabilidades graves (ej. WannaCry). Se recomienda desactivarlo.

![Desactivación de SMB 1.0](images/1000000100000780000003F1F2416896.png)

![Configuración avanzada de Windows Features](images/1000000100000780000003F14D1D575E.png)

---

### 2. UBUNTU LINUX

#### A. Creación de un usuario NO-administrador

![Creación de usuario en Ubuntu](images/1000000100000780000003F184B9A38A.png)

![Ventana de usuarios en Ubuntu](images/1000000100000657000003ED0E08D3B0.png)

#### B. Ejecutar las actualizaciones en Ubuntu

1. **Instalar Aptitude**:

   ```bash
   sudo apt install aptitude
   ```

2. **Actualizar lista de paquetes**:

   ```bash
   sudo aptitude update
   ```

3. **Actualizar todo el sistema**:

   ```bash
   sudo aptitude full-upgrade
   ```

![Ejecución de actualizaciones](images/1000000100000780000003F128AC9E6F.png)

![Snapshot de terminal con actualizaciones](images/1000000100000780000003F1458A1DFD.png)

![Configuración NAT / Entorno virtual](images/1000000100000780000003F14DDDFAA1.png)

![Snapshot final de configuración](images/1000000100000780000003F1BD548069.png)

![Otras vistas de configuración](images/1000000100000780000003F165E63939.png)

![Configuración NAT avanzada](images/1000000100000780000003F1E0B48895.png)

![Windows Features / SMB](images/10000001000004FC0000031D4A346E92.png)

![Desinstalación de características](images/10000001000004FC0000031903D464AB.png)

![Usuario estándar en Windows](images/1000000100000506000003118C5F552F.png)

![Confirmación de usuario](images/100000010000050100000321B080D2AA.png)

![Windows Update en ejecución](images/10000001000004FF0000032023276855.png)

![Terminal Ubuntu - Actualizaciones](images/100000010000050700000320CA8712EA.png)

![Aptitude full-upgrade](images/100000010000050D000003271852F2C8.png)

![Resumen de actualizaciones](images/1000000100000505000003183F73A54D.png)

![Configuración final](images/1000000100000504000003239DA6BC79.png)

![Usuario no administrador en Windows](images/1000000100000780000002BCF67E46B5.png)

![Usuario administrador vs estándar](images/10000001000007800000031712F92545.png)

---

**Nota:** Coloca todas las imágenes en una carpeta `images/` junto a este archivo.
