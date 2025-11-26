# Matrix Morpheus GRUB Theme
**Red Pill vs Blue Pill**

Tema minimalista inspirado en Matrix para GRUB con fondos dinámicos a pantalla completa que cambian entre Linux y Windows.

---

**Configuración actual:**  
Este tema está configurado para **Ubuntu + Windows** dual-boot.

Los iconos están ordenados horizontalmente en pantalla,  
pero se navega usando las teclas **Arriba** y **Abajo** como en un menú GRUB normal.

---

![Matrix Morpheus GRUB Theme preview](preview.gif)

## Instalación

1. Clona el repositorio (o si ya lo tienes, salta al paso 2)

```shell
git clone https://github.com/Priyank-Adhav/Matrix-Morpheus-GRUB-Theme
```

2. Entra en la carpeta

```shell
cd Matrix-Morpheus-GRUB-Theme
```

3. Haz el instalador ejecutable

```shell
chmod +x install.sh
```

4. Ejecuta el script de instalación como administrador

```shell
sudo ./install.sh
```

5. Reinicia para ver tu nuevo tema

---

## Notas

- El script crea automáticamente los iconos necesarios para Ubuntu (`ubuntu.png`, `gnu-linux.png`, `linux.png`) a partir de la imagen base.
- Windows usa `windows.png` que ya viene incluido.
- Si GRUB tiene entradas adicionales (como "Advanced options" o "UEFI Firmware Settings"), considera ocultarlas para una experiencia visual más limpia.
