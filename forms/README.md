## Getting Started

- Install the version of Node JS for your OS https://nodejs.org/en/download
- From a terminal run the following commands to check if the installation was successful:
  - `$ node -v`
  - `$ npm -v`
  - Set PATH environment variable to path/to/bin/node and path/to/bin/npm if the above commands failed to return the version number.
- In the terminal install dependencies using the command:
  `$ npm install`
- In the terminal run the local server using the command:
  - `node form-server.js`
- Open "form.html" in a browser. Enter username and password and click "Submit".

## Questions for you to answer

1. What is the purpose of the _action_ attribute in the _form_ tag?
   A: The action to be performed once the form is submitted.

2. What is the purpose of the _method_ attribute in the _form_ tag?
   A: It tells the web browser how to send form data to a server using http request methods.

3. What is the purpose of the _name_ attribute in the _input_ tag?
   A: The form data from that input tag is stored in the key value that is defined using _name_.

4. What is the purpose of the _type_ attrbute in the _input_ tag?
   A. It defines the type of the input field. Like password, text,radio, submit etc.

5. What is the purpose of the _label_ tag?
   A. It defines a label for a form element. It gives some idea about the input element to the user.

6. What is the purpose of the _required_ attribute?
   A. It indicates that user must specify a value for the input before the form can be submitted.
