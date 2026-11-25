
# Ex-4: Scenario-Based Report Development Utilizing Diverse Prompting Techniques

## Aim:

To develop an AI-powered retail customer support chatbot that assists customers with product inquiries, order tracking, payment problems, delivery issues, and returns using different AI prompting techniques.

## Algorithm:

1. Identify the main functions of a retail chatbot.
2. Prepare different customer support scenarios.
3. Create prompts using various prompting techniques.
4. Enter the prompts into the AI chatbot.
5. Generate responses for each customer query.
6. Evaluate the responses based on accuracy and clarity.
7. Compare the outputs and prepare the final report.

## Prompts Using Different AI Prompting Techniques
1\. Zero-Shot Prompting: Giving an instruction to the AI without providing any examples.

2\. One-Shot Prompting: Giving one example to the AI before asking a new question.

3\. Few-Shot Prompting: Giving two or more examples to the AI to guide its answers.

4\. Chain-of-Thought Prompting: Asking the AI to analyze a problem step by step before giving the final answer.

5\. Role-Based Prompting: Assigning a specific role to the AI, such as a customer support executive.

6\. Contextual Prompting: Providing background information to the AI so it can give relevant answers.

### 1. Zero-Shot Prompting

Prompt:

```
You are an AI chatbot for an online shopping store.
Answer customer questions in a simple and friendly way.

Customer:
"Do you offer discounts on laptops?"
```

Output:

```
Yes! We offer discounts on selected laptop models
during special sales and promotional events.
You can check our latest offers on the website.
Would you like help finding a laptop within
your budget?
```

### 2. One-Shot Prompting

Prompt:

```
Customer:
"How can I check product availability?"

Assistant:
"Visit our website, search for the product,
and check the availability displayed on
the product page."

Customer:
"How can I update my mobile number?"
```

Output:

```
You can update your mobile number by logging
into your account and visiting the Profile
Settings section. Select Edit Profile, enter
your new mobile number, and verify it using
the OTP sent to your phone.
```

### 3. Few-Shot Prompting

Prompt:

```
You are a retail customer support chatbot.

Example 1:
Customer: "What should I do if I forget my password?"
Assistant: "Click Forgot Password on the login
page and follow the instructions to reset it."

Example 2:
Customer: "Do you provide Cash on Delivery?"
Assistant: "Yes, Cash on Delivery is available
for selected locations."

Customer:
"How can I cancel a product?"
```

Output:

```
You can cancel your product by logging into
your account and opening the My Orders section.
Select the product you want to cancel and click
the Cancel Order option. Cancellation depends
on the current order status.
```

### 4. Chain-of-Thought Prompting

Prompt:

```
You are a retail customer support chatbot.
Analyze the customer's issue and provide
possible reasons and suitable solutions.

Customer:
"I received a message that my order was delivered,
but I have not received the package."

Provide a clear final answer without revealing
internal reasoning.
```

Output:

```
We apologize for the inconvenience.

Possible reasons:
1. The package may have been delivered to
   a neighbor or security desk.
2. The delivery status may have been updated
   incorrectly.
3. There may have been a delivery address issue.

Solution:
Please check with your neighbors or security
desk first. If the package is still missing,
contact customer support with your Order ID
so that we can investigate the issue.
```

### 5. Role Prompting

Prompt:

```
Act as a professional retail customer service
manager. Handle customer complaints politely
and provide helpful solutions.

Customer:
"The product I received is different from
the one I ordered."
```

Output:

```
We sincerely apologize for the mistake.

We understand your concern. Please provide
your Order ID and a photograph of the received
product. Our support team will verify your
complaint and assist you with a replacement
or refund according to our store policy.
Thank you for your patience.
```

### 6. Contextual Prompting

Prompt:

```
Context:
An online retail store provides free delivery
for orders above ₹1500. Orders below ₹1500
have a delivery charge of ₹50.

Customer:
"My shopping order total is ₹1200.
How much delivery charge should I pay?"
```

Output:

```
Your order total is ₹1200, which is below
the ₹1500 free delivery limit.

Therefore, a delivery charge of ₹50 will
be added to your order.

Your total payable amount will be ₹1250.
Thank you for shopping with us!
```

## Result:

Thus, the AI-powered retail customer support chatbot was successfully tested using six different prompting techniques. The chatbot provided appropriate responses to various customer scenarios, including product inquiries, account assistance, order cancellation, missing deliveries, product complaints, and delivery charges. The experiment shows that different prompting techniques help improve chatbot performance, response accuracy, and customer satisfaction in a retail environment.
