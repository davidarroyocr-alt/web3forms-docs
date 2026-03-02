<form action="https://api.web3forms.com/submit" method="POST">
  <!-- Access Key -->
  <input type="hidden" name="access_key" value="b0b60ce0-7620-47ee-b8d1-4cd969713d13">

  <!-- First Name / Last Name -->
  <label for="first_name">First Name:</label>
  <input type="text" id="first_name" name="first_name" placeholder="Enter your first name" required>

  <label for="last_name">Last Name:</label>
  <input type="text" id="last_name" name="last_name" placeholder="Enter your last name" required>

  <!-- Address -->
  <label for="address">Address:</label>
  <input type="text" id="address" name="address" placeholder="Enter your address" required>

  <label for="city">City:</label>
  <input type="text" id="city" name="city" placeholder="Enter your city" required>

  <input type="hidden" name="state" value="Georgia">

  <label for="zip">Zip Code:</label>
  <input type="text" id="zip" name="zip" placeholder="Enter your zip code" required>

  <!-- Phone / Call Time -->
  <label for="phone">Phone:</label>
  <input type="tel" id="phone" name="phone" placeholder="Enter your phone number" required>

  <label>Best time to call:</label>
  <input type="radio" id="am" name="call_time" value="AM" required>
  <label for="am">Morning (AM)</label>
  <input type="radio" id="pm" name="call_time" value="PM">
  <label for="pm">Afternoon (PM)</label>

  <!-- Services -->
  <label>Services Needed:</label>
  <input type="checkbox" id="exterior" name="services[]" value="Exterior">
  <label for="exterior">Exterior</label>
  <input type="checkbox" id="interior" name="services[]" value="Interior">
  <label for="interior">Interior</label>

  <!-- Notes -->
  <label for="notes">Additional Notes:</label>
  <textarea id="notes" name="notes" placeholder="Enter any extra details"></textarea>

  <!-- Email -->
  <label for="email">Email:</label>
  <input type="email" id="email" name="email" placeholder="Enter your email" required>

  <!-- Submit Button -->
  <button type="submit">Submit Form</button>
</form>
