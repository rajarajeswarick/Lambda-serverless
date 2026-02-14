# Lambda-serverless
Create and test Lambda Function
From the AWS Managemnet Console 
Goto Lambda, click Create Function
<img width="1885" height="834" alt="image" src="https://github.com/user-attachments/assets/61e3b90c-05ca-4757-b23b-eeebc116cd94" />
You will be presented with multiple options to create a Lambda.
Select 'Author from Scratch'
Give a Name to your Function, 'HelloWorld'
From the Runtime drop down select Python
Keep everything as it is and click Create Function
<img width="1862" height="869" alt="image" src="https://github.com/user-attachments/assets/959cb6b8-e506-4c30-bc18-b6c7099abd9e" />
Lambda is created, scroll down to see the code.
<img width="1851" height="914" alt="image" src="https://github.com/user-attachments/assets/c71b628f-408d-4f92-9072-1149843ec84c" />
lambda_handler is the main function, everytime Lambda is invoked, this is executed first.
This takes two arguments, event and context.
event is the input parameter, you can pass to this function and event accepts a Json object.
If your code has to deal with some application inputs you can pass it in this argument. 
context is more for system information. The lambda service passthis object and cannot change it. 
context will have information about the memory limit, log group and other system information. 
To run the function, click the Test icon, this opens a configure test event.  
Give some event values - 'Greetings', 'Welcome', 'Hi'
<img width="1883" height="904" alt="image" src="https://github.com/user-attachments/assets/067344dc-d60d-4b67-9237-3a4074547539" />
Print the event and context in the code
Deploy and Test, you can see the event and context details in the output.
<img width="1858" height="860" alt="image" src="https://github.com/user-attachments/assets/8aa5f741-651a-4567-a04c-2df647f9d60b" />
