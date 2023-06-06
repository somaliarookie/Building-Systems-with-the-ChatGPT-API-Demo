#### Demo of Building Systems with the ChatGPT API on DeepLearning.AI site

Build your own personalized chatbot using ChatGPT that can answer questions specific to your business.


[Building Systems with the ChatGPT API](https://learn.deeplearning.ai/chatgpt-building-system/lesson/1/introduction), written in
[Python](https://www.python.org/).

> Use quote blocks to emulate reply text.
> This line is part of the same quote.

This line is not formatted and does not belong to the quote block.

> This block spans multiple paragraphs.
>
> The second paragraph is grouped with the previous paragraph in the same quote block.
> Character formatting is _also_ supported inside the **quote block**.

> Quote blocks can also be nested.
>> When you start a new line with additional > characters,
>>> it simulates a threaded conversation.

#### Getting started

1. Just replace your key here: `` openai.api_key = "input your key here" ``
2. Create a chatbot suitable for your own website: Write your product information into the ``products.json`` file (you need to follow the JSON format as shown in the figure) 
  ```
  {
    "TechPro Ultrabook": {
        "name": "TechPro Ultrabook",
        "category": "Computers and Laptops",
        "brand": "TechPro",
        "model_number": "TP-UB100",
        "warranty": "1 year",
        "rating": 4.5,
        "features": [
            "13.3-inch display",
            "8GB RAM",
            "256GB SSD",
            "Intel Core i5 processor"
        ],
        "description": "A sleek and lightweight ultrabook for everyday use.",
        "price": 799.99
    } }
  ```





