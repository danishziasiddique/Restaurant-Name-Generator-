# Restaurant Name Generator

This application generates restaurant names and menu items based on the selected cuisine.

## **Preview**

![Screenshot 2024-06-12 at 6 50 16 PM](https://github.com/danishziasiddique/Restaurant-Name-Generator-/assets/82972335/50cef5bf-49b0-4dd1-8081-a8777793b35f)


## Usage

1. **Select a Cuisine:**
   
    Choose a cuisine from the sidebar dropdown menu. Options include Indian, Italian, Mexican, Arabic, and American.

2. **View Restaurant Name and Menu Items:**

    Upon selecting a cuisine, the application will generate a restaurant name and suggest menu items relevant to the chosen cuisine.

## Implementation

The generator utilizes OpenAI's language model to create restaurant names and menu items. It consists of two chains:

1. **Restaurant Name Chain:**
   
    - Prompt: "I want to open a restaurant for {cuisine} food. Suggest a fancy name for this."
    - Output: Restaurant name.

2. **Menu Items Chain:**
   
    - Prompt: "Suggest some menu items for {restaurant_name}. Return it as a comma-separated string."
    - Output: Menu items.

These chains are executed sequentially, resulting in the generation of both a restaurant name and corresponding menu items.

## Dependencies

- Streamlit: `streamlit`
- Langchain Helper: `langchain_helper`

## Contributing

Contributions are welcome! Please open an issue or submit a pull request if you have any improvements or new features you'd like to see.

