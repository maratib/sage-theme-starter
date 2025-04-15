# Sage Theme Starter

## Create Theme

```bash
composer create-project roots/sage your-theme-name

cd your-theme-name

# Install node dependencies
npm install

# Build assets
npm run build

# Rename .env.example to .env
```

## Package Theme

```bash
# Remove node_modules
rm -rf node_modules

# Remove vendor
rm -rf vendor

# Install only require composer packages
composer install --no-dev  --optimize-autoloader

# Zip the folder
```
