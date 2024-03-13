# 📧 Checky - Validate Email API 📧

![Checky Logo](assets/cover.png)

Checky is a powerful API for validating email addresses. Whether you're building an email verification feature for your application or need to ensure the accuracy of email inputs in a form, Checky has you covered. With Checky, you can easily verify the format, existence, and validity of email addresses, ensuring smooth communication with your users.

## 🚀 Features

- Validate the format and structure of email addresses.
- Check if the email domain is blacklisted using a predefined list of disposable email domains.
- Check for the existence of email domains using DNS lookup.
- Verify the validity of email addresses by initiating an SMTP conversation.

## 🏁 Quick Start

To get started with Checky, follow these simple steps:

1. [Sign up for an account](https://rapidapi.com/kidddevs/api/checky-validate-email-api) on RapidAPI and subscribe to the Checky Validate Email API.
2. Use the provided API key to access the endpoints.
3. Start validating email addresses in your applications or services.

## 🔁 Endpoints

- **Validate Email (POST /validate):**
  - Validates a single email address provided in the request body.
  
- **Validate Email (GET /validate):**
  - Validates a single email address provided as a query parameter.

- **Extract Emails (POST /extract):**
  - Extracts email addresses from a text input and validates each email found.

## 🔑 API Key

To access the Checky Validate Email API, you need to sign up on RapidAPI and subscribe to the API. Upon subscription, you will receive an API key that you can use to authenticate your requests.

## 💻 Usage

```bash
# Validate a single email address using POST request
curl -X POST \
  checky-validate-email-api/validate \
  -H 'Content-Type: application/json' \
  -H 'X-RapidAPI-Key: YOUR_API_KEY' \
  -d '{"email": "example@example.com"}'

# Validate a single email address using GET request
curl -X GET \
  'checky-validate-email-api/validate?email=example@example.com' \
  -H 'X-RapidAPI-Key: YOUR_API_KEY'

# Extract and validate email addresses from text input
curl -X POST \
  checky-validate-email-api/extract \
  -H 'Content-Type: application/json' \
  -H 'X-RapidAPI-Key: YOUR_API_KEY' \
  -d '{"text": "Here are some emails: example@example.com, test@test.com"}'
  
# Extract and validate email addresses from HTML as text input
curl -X POST \
  checky-validate-email-api/extract \
  -H 'Content-Type: application/json' \
  -H 'X-RapidAPI-Key: YOUR_API_KEY' \
  -d '{"text": "<body><h1>HTML Test</h1><p>This is a sample HTML document with test email addresses:</p><ul><li>john.doe@example.com</li><li>alice.smith@test.com</li><li>info@company.org</li></u></body></html>"}'
```
  
## 🔧 Issues

If you encounter any issues or have suggestions for improvement, please [open an issue](https://github.com/dakidarts/Checky-Validate-Email-API/issues) on GitHub. We appreciate your feedback!

## 📝 License

This project is licensed under the MIT License. See the LICENSE file for details. 📝

## 🌐Social Links

- [Website](https://dakidarts.com)
- [Twitter](https://twitter.com/dakidarts)
- [Instagram](https://instagram.com/dakidarts)
- [LinkedIn](https://linkedin.com/company/dakidarts)

---

Happy Validating! 🎉

Start using Checky today to ensure the validity of your email addresses and enhance the communication experience with your users. If you have any questions or need assistance, don't hesitate to reach out. Happy validating! 😊
