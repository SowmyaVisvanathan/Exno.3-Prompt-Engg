# Exno.3-Scenario-Based Report Development Utilizing Diverse Prompting Techniques
### DATE: Sowmya V                                                   
### REGISTER NUMBER : 212222110045

### Aim: 
To design an AI-powered chatbot that assists customers in resolving issues related to product troubleshooting, order tracking, and general inquiries. The chatbot should handle various customer queries efficiently while maintaining a conversational and user-friendly tone. In this experiment, we will employ different prompt patterns to guide the development process of the chatbot, ranging from basic task-oriented prompts to more complex, persona-driven prompts.

### Algorithm:  
### 1. Direct Instruction Prompting
- This involves giving clear and concise commands. For example:
- "Track order number 456789 and inform the customer of the estimated delivery date."
This prompt is straightforward and easy for the AI to act on without needing additional context.

### 2. Contextual Prompting
- Here, background information is included to help the AI generate more accurate responses. For instance:
- "The customer recently purchased a smart speaker and reports that it won’t connect to Wi-Fi. Help troubleshoot the issue."
By including the context (the product and the problem), the AI can deliver more relevant assistance.

### 3. Persona-Based Prompting
- This prompt sets a specific tone or role for the AI. Example:
- "As a friendly customer support assistant, explain how to reset a smart thermostat in simple terms."
This shapes the AI’s response to be both helpful and approachable, improving the user experience.

### 4. Few-Shot Prompting
- Few-shot prompts guide the AI by showing a few example question-answer pairs before asking the real question. Example:
- "Example 1: Q: How do I return an item? A: Go to 'My Orders', select the item, then click 'Return'.
- Example 2: Q: Where is my package? A: Check your order status under 'My Orders'.
- Now: Q: My blender isn’t working. A:"
- This helps the AI understand the response format and expected tone.

### 5. Chain of Thought Prompting
- This strategy instructs the AI to reason step-by-step. For example:
- "The customer says their headphones won't turn on. First, ask if the device is charged. Then check if the power button is working. Finally, suggest a reset process."
- It improves problem-solving by guiding the AI through logical steps.

### 6. Instruction with Constraints
- This approach adds specific rules or limitations. Example:
- "Track the customer's order, but do not mention the delivery date unless it is within 24 hours. Keep the response under 50 words."
- Such constraints ensure the response stays within a brand's tone or compliance requirements.

### 7. Reflective Prompting
- Reflective prompting encourages the AI to self-evaluate its response. For instance:
- "Respond to the customer about an app crash issue, then check whether your explanation would make sense to someone with no technical background. If not, rephrase it."
- This technique improves clarity and quality control in responses.

### Result: 
Combining multiple prompting strategies ensures that the chatbot can effectively handle varied customer queries with accuracy, empathy, and efficiency. Whether you need a direct answer, a step-by-step guide, or a context-aware reply, using the right prompting approach helps create a high-quality customer support experience.
