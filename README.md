# OCA Storage

This repository contains **17** OCA packages for storage.

## Packages Included (17 packages)

- **odoo-bringout-oca-storage-fs_attachment** - From storage: fs_attachment
- **odoo-bringout-oca-storage-fs_base_multi_image** - From storage: fs_base_multi_image
- **odoo-bringout-oca-storage-fs_base_multi_media** - From storage: fs_base_multi_media
- **odoo-bringout-oca-storage-fs_file** - From storage: fs_file
- **odoo-bringout-oca-storage-fs_file_demo** - From storage: fs_file_demo
- **odoo-bringout-oca-storage-fs_image** - From storage: fs_image
- **odoo-bringout-oca-storage-fs_image_thumbnail** - From storage: fs_image_thumbnail
- **odoo-bringout-oca-storage-fs_product_brand_multi_image** - From storage: fs_product_brand_multi_image
- **odoo-bringout-oca-storage-fs_product_multi_image** - From storage: fs_product_multi_image
- **odoo-bringout-oca-storage-fs_product_multi_media** - From storage: fs_product_multi_media
- **odoo-bringout-oca-storage-fs_product_public_category_multi_image** - From storage: fs_product_public_category_multi_image
- **odoo-bringout-oca-storage-fs_storage** - From storage: fs_storage
- **odoo-bringout-oca-storage-fs_storage_backup** - From storage: fs_storage_backup
- **odoo-bringout-oca-storage-image_tag** - From storage: image_tag
- **odoo-bringout-oca-storage-storage_backend** - From storage: storage_backend
- **odoo-bringout-oca-storage-storage_backend_sftp** - From storage: storage_backend_sftp
- **odoo-bringout-oca-storage-storage_file** - From storage: storage_file


## Installation

Install any package from this category:

```bash
# Install from local directory
pip install packages/oca-storage/PACKAGE_NAME/

# Install in development mode  
pip install -e packages/oca-storage/PACKAGE_NAME/

# Using uv (recommended for speed)
uv add packages/oca-storage/PACKAGE_NAME/
```

## Repository Structure

Each package in this repository follows the standard Odoo addon structure:

```
oca-storage/
├── odoo-bringout-oca-PROJECT-ADDON/
│   ├── ADDON_NAME/           # Complete addon code
│   │   ├── __init__.py
│   │   ├── __manifest__.py
│   │   └── ... (models, views, etc.)
│   ├── pyproject.toml        # Python package configuration
│   └── README.md            # Package documentation
└── ...
```

## Contributing

These packages are maintained as part of the [OCA (Odoo Community Association)](https://github.com/OCA) ecosystem.

## License

Each package maintains its original license as specified in the OCA repositories.
