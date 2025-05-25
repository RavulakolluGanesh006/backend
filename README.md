### overview
This Express server receives form data via a POST request at /api/Generationform, validates it, and forwards it to an n8n webhook for automation workflows. It's designed to work with a frontend form like GenerationForm.js.
It will recieve data from react app and dend data tp n8n webhook it will send data to email in json and the data is stored in spreadsheet

### step-1
we will capture the data from the front end through axios post
### step-2
we will recieve the response and send to n8n webhook
### step-3
In n8n we need to setup http method as post and path as /GenerationForm and copy the url
### step-4
there will be add button search for send email in trigger point setup SMTP give your creditionals and give password as app password and host as smtp.gmail.com and port as 465 after that return and give from,to,subject and message from json.body
### step-5
add your google sheet account add your creditional add url of spreadsheet
map automatically
