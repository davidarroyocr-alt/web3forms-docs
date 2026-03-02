<!-- Nombre y Apellido -->
<input type="text" name="first_name" required>
<input type="text" name="last_name" required>

<!-- Dirección -->
<input type="text" name="address" required>
<input type="text" name="city" required>
<input type="hidden" name="state" value="Georgia">
<input type="text" name="zip" required>

<!-- Teléfono y horario -->
<input type="tel" name="phone" required>
<input type="radio" name="call_time" value="AM" required> Morning
<input type="radio" name="call_time" value="PM"> Afternoon

<!-- Servicios múltiples -->
<input type="checkbox" name="services[]" value="Exterior"> Exterior
<input type="checkbox" name="services[]" value="Interior"> Interior

<!-- Notas -->
<textarea name="notes"></textarea>

<!-- Email -->
<input type="email" name="email" required>
