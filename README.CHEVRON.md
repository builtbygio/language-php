# language-php (Chevron)

PHP highlighter for Chevron. Tree-sitter is the default:

- `text.html.php` → `tree-sitter-php/php` (HTML + `<?php ?>`, owns the file types)
- `source.php` → `tree-sitter-php/php_only` (PHP-only / injection)

The TextMate grammars in `grammars/html.cson` and `grammars/php.cson`
stay as the fallback.

Owned so the pin is not an archived `atom/*` remote.
Chevron loads this via `packageDependencies`.
