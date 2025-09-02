# Azure-Static-Website
<img width="1416" height="814" alt="Screen Shot 2025-09-02 at 10 24 36 AM" src="https://github.com/user-attachments/assets/6f5a1242-33f3-4014-a138-825e09428b3e" />


Go see my Azure Static Website I created here: https://pritikasstoragegroup.z13.web.core.windows.net/

# Azure Storage Static Website Demo

I created a Azure Static Website on how to set up an Azure Storage Static Website, I know **IRONIC**. The project is designed to be hosted entirely on Azure's `$web` container without requiring any backend or server.

## **Project Overview**

An Azure Storage Static Website allows you to host HTML, CSS, and JavaScript files directly in Azure Blob Storage. By enabling the static website feature, you get an instant public URL to share a microsite, portfolio, or demo app.

## **Features**

- Fully static website hosted on Azure Storage.
- Step-by-step text-heavy tutorial on setting up Azure Static Websites.
- Ready-to-use `index.html` and optional `404.html`.
- No backend or database required.
- Publicly accessible URL hosted directly from Azure.

  ## **Common Errors**

- **404 Errors:** Ensure the index document is named exactly `index.html`.
- **Wrong Container:** Files must be uploaded to `$web` container.
- **Capitalization:** Azure is case-sensitive; `Index.html` will not work if your index document name is `index.html`.
- **Blob Endpoint Access:** Always use the Primary endpoint provided under Static website settings.

## **Use Cases**

- Portfolio website
- One-page resume
- Demo or microsite
- Project documentation hosting

## **Next Steps**

- Connect a custom domain
- Enable HTTPS
- Integrate Azure CDN for global performance
