Create a config.env file in the backend folder:
  paste the following codes in that file:
    PORT = 4000
    FRONTEND_URL = http://localhost:5173/
    SNTP_HOST = smtp.gmail.com
    SNTP_PORT = 465
    SMTP_SERVICE=gmail
    SMTP_MAIL=
    SMTP_PASSWORD=

Then open terminal, navigate to the backend in one and frontend in another, then run npm i in both terminals and then run npm run dev in both terminals.
