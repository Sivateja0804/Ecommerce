# Ecommerce

Common Fixes:

1. If anytime port is busy and you are getting the url down. Execute the following commands in cmd running as Administrator
   netstat -ano | findstr 5000
   taskkill /F /PID < Process Id >
