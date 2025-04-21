### Installation

```bash
pip install django-msgraph-mail
```

### How to use this

EMAIL_BACKEND = "django_msgraph_mail.backend.GraphEmailBackend"
EMAIL_SENDER = "your-sender@domain.com"
CLIENT_ID = "your-azure-client-id"
CLIENT_SECRET = "your-azure-client-secret"
TENANT_ID = "your-tenant-id"

###