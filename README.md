# ZetuNet ISP Billing System

A professional cloud-based multitenant ISP billing system designed for Kenyan ISPs.

## Features

- Multi-tenant architecture for independent ISP operations
- Support for Hotspot, PPPoE, and Static IP packages
- Integrated M-PESA payment system
- Client management and billing
- Voucher generation and management
- Customizable branding per tenant
- SuperAdmin dashboard for system management

## System Requirements

- PHP 8.0 or higher
- MySQL 5.7 or higher
- Apache/Nginx web server
- SSL certificate (for secure connections)
- Composer (PHP package manager)

## Installation

1. Clone the repository
2. Run `composer install` to install dependencies
3. Create a MySQL database
4. Import the database schema from `database/schema.sql`
5. Configure your environment variables in `.env`
6. Set up your web server to point to the `public` directory

## Directory Structure

```
zetunet-billing/
├── app/
│   ├── config/
│   ├── controllers/
│   ├── models/
│   ├── views/
│   └── helpers/
├── public/
│   ├── assets/
│   ├── css/
│   ├── js/
│   └── index.php
├── database/
│   └── schema.sql
├── vendor/
├── .env
├── composer.json
└── README.md
```

## Support

For support, please contact support@zetunet.co.ke

## License

Proprietary - All rights reserved 