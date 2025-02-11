# **Poetry Assistant**

## **Overview**
Poetry Assistant is a simple **JavaScript-based web tool** that helps users find rhyming words for creative writing and poetry. It fetches words from an external list and identifies words that rhyme with the user’s input based on common suffix patterns.

## **Features**
- **Rhyming Word Finder**: Identifies words that share similar suffixes with the user’s input.
- **User Input Handling**: Allows users to enter words and receive a list of rhyming suggestions.
- **Dynamic Word Fetching**: Retrieves words from an external text file (`wordlist.txt`).
- **Efficient Matching Algorithm**: Compares the last **two or three** characters of words to determine rhymes.
- **Interactive Display**: Presents rhyming words in a user-friendly format.

## **Technologies Used**
- **JavaScript** – Handles input processing and logic.
- **HTML/CSS** – Provides a simple front-end interface.
- **Fetch API** – Retrieves word data from an external file.

## **How It Works**
1. **User Input**: The user enters a word into the input field.
2. **Fetch Word List**: The script loads a pre-defined word list from `Assets/wordlist.txt`.
3. **Find Rhyming Words**:
   - Compares the last **2-3 characters** of each word in the list.
   - Matches words with similar endings to the user input.
4. **Display Results**: The matching words are shown on the webpage.

## **Example Usage**
1️⃣ Enter a word in the input box (e.g., `light`).  
2️⃣ Click the **Find Rhymes** button.  
3️⃣ The tool will fetch words from the word list and display rhyming words (e.g., `bright`, `sight`, `might`).  

## **Potential Enhancements**
- Implement a **phonetic-based** rhyming system for better accuracy.
- Add **synonyms and antonyms** for more writing assistance.
- Integrate **AI-generated rhyming suggestions** for creative flexibility.
- Enhance the UI with **autocomplete** and real-time suggestions.

## **Installation & Setup**
1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/poetry-assistant.git
   ```
2. Open `index.html` in a browser to run the tool.
3. Ensure `wordlist.txt` is in the `Assets/` folder for word fetching.
