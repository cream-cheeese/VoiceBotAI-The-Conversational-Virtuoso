# GPT-3 Voice Interaction Script

## Description

This Python script enables users to interact verbally with OpenAI's GPT-3 model. Since GPT-3 itself doesn't support verbal communication, we've integrated Eleven Labs to provide GPT-3 with a voice and microphone for receiving verbal inputs. The user's spoken input is recorded, transcribed, processed by GPT-3, and the resulting output is made audible using Eleven Labs.

## Installation

Follow these steps to install and set up the script:

1. **Clone the repository:**

   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```

2. **Install dependencies:**

   Ensure you have Python 3.x installed. Then, install the required Python packages using pip:

   ```bash
   pip install -r requirements.txt
   ```

   Make sure to replace `requirements.txt` with the actual filename if it's different in your project.

3. **Setup Eleven Labs:**

   Follow the setup instructions for Eleven Labs to enable audio input and output capabilities for GPT-3.

4. **API Keys and Configuration:**

   Obtain API keys or configure any necessary settings for both GPT-3 and Eleven Labs. Place these keys securely and update the configuration files as needed.

## Usage

### Verbal Interaction with GPT-3

To start interacting with GPT-3 using voice commands, follow these steps:

1. **Run the script:**

   ```bash
   python main.py
   ```

2. **Speak your input:**

   Speak clearly into the microphone connected to Eleven Labs. Your spoken input will be recorded and transcribed automatically.

3. **Receive GPT-3's response:**

   After processing your input, the script will feed it to GPT-3 for analysis and generate response, the textual response is converted to a verbal one using Eleven Labs.

### Example

Here's an example of how to use the script:

- **Input:** Speak "What is the weather like today?"
- **Output:** You will hear GPT-3's response through the connected audio output.

---

