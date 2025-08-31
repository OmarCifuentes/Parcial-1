# Instrucciones para Cambiar la Ubicación del Mapa


### 1. Obtener el Código de Embed de Google Maps

1. Ve a [Google Maps](https://www.google.com/maps)
2. Busca la dirección de tu tienda
3. Haz clic en "Compartir"
4. Selecciona "Insertar un mapa"
5. Copia el código HTML que aparece

### 2. Reemplazar en el Código

Busca esta línea en `contact.html` y `index.html`:

```html
<iframe 
  src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3024.2219901290355!2d-74.00369368400567!3d40.71312937933185!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x89c25a23e28c1191%3A0x49f75d3281df052a!2s150%20Park%20Row%2C%20New%20York%2C%20NY%2010007%2C%20USA!5e0!3m2!1sen!2s!4v1640995200000!5m2!1sen!2s" 
  width="100%" 
  height="240" 
  style="border:0; border-radius: 8px;" 
  allowfullscreen="" 
  loading="lazy"
  title="ShopLogo Store Location">
</iframe>
```

Reemplaza solo la parte del `src` con tu nuevo código de embed.

### 3. Ubicaciones Actuales

- **Página de Contacto**: `contact.html`
- **Página Principal**: `index.html` 
### 4. Personalización Adicional

Puedes cambiar:
- `height="240"` - Altura del mapa
- `title="ShopLogo Store Location"` - Título para accesibilidad
- `style="border:0; border-radius: 8px;"` - Estilos del borde


