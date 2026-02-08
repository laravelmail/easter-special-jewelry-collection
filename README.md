# Easter Special Jewelry Collection

Professional Easter special marketing email template for showcasing a jewelry collection in the retail or fashion industry.

![Thumbnail](./thumbnail.png)

## Template Details

- **Industries:** Retail, Fashion
- **Message Type:** Marketing
- **Tags:** easter special offer, jewelry collection

## Files
- `index.html`: The improved, localized, and branded HTML template.
- `template.blade.php`: Ready-to-use Laravel Blade template with `asset()` helpers.
- `assets/`: Directory containing localized images and styles used in the template.

## Usage in Laravel

### 1. Store the Template
Place the `index.html` content in a Blade view (e.g., `resources/views/emails/easter-special-jewelry-collection.blade.php`).

### 2. Handle Assets
Move the content of `assets/` to your public directory (e.g., `public/vendor/mail-templates/easter-special-jewelry-collection/`) and update the paths in the HTML to use the `asset()` helper.

### 3. Send Email
```php
Mail::to($user)->send(new \App\Mail\GenericEmail([
    'view' => 'emails.easter-special-jewelry-collection',
    'data' => [
        // Your dynamic data here
    ]
]));
```

---
*Created with ❤️ by **[LaravelMail.com](https://laravelmail.com)** - Your source for professional email templates.*
