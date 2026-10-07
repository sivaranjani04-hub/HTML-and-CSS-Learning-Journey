# HTML Forms

## What is it?
A form collects information from the user and sends it to a server (or another page). Each field is an `<input>`, `<select>` or `<textarea>`, usually with a `<label>`.

## Syntax
```html
<form action="result.html" method="get">
  <label for="name">Name:</label>
  <input type="text" id="name" name="name" required>
  <input type="submit" value="Send">
</form>
```

## Important attributes/properties
- `action` – where the data goes
- `method` – `get` (visible in URL) or `post` (hidden)
- `type` – text, password, email, tel, date, number, radio, checkbox, file, submit, reset
- `label + for + id` – connects a label to its input
- `name` – name of the data sent (radio buttons with the same name form a group)
- `required, minlength, maxlength` – validation
- `placeholder, value` – hint text / starting value
- `pattern` – regular-expression validation
- `min, max` – limits for number/date
- `select + option` – dropdown
- `textarea rows/cols` – multi-line text
- `accept, enctype="multipart/form-data"` – file uploads

## Examples
- `01-basic-form.html` – form, action, method (GET and POST)
- `02-text-input.html` – text, label, required, minlength, maxlength, placeholder, value
- `03-password.html` – password
- `04-email.html` – email
- `05-phone-pattern.html` – tel and pattern
- `06-date-number.html` – date, number, min, max
- `07-radio-buttons.html` – radio buttons and name grouping
- `08-select-dropdown.html` – select and option
- `09-checkbox.html` – checkboxes
- `10-textarea.html` – textarea
- `11-file-upload.html` – file input, accept, enctype
- `12-complete-form.html` – everything together, submit and reset
- `result.html` – page that receives GET data

## Key takeaway
- `for` must match the input `id`; `name` is what is sent.
- Radio buttons need the SAME `name`.
- Use `enctype="multipart/form-data"` for file uploads.
- POST examples use httpbin.org (needs internet); GET examples work offline.
