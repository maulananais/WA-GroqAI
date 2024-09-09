### Base Repositories:
1. [Hisoka-Morou](https://github.com/nyx095/Hisoka-Morou)
2. [Wa-OpenAI](https://github.com/Sansekai/Wa-OpenAI)

---
# **WA-GroqAI**

This is a WhatsApp bot that uses the Groq API to provide AI-based responses, along with [Baileys](https://github.com/WhiskeySockets/Baileys) as the main library for managing WhatsApp interactions.

### How to Use on Desktop/VPS

1. **Install Node.js and Git**
   - **Windows/Mac/Linux**: Download and install Node.js from the official [Node.js](https://nodejs.org/) website.
   - **Linux**: Install Git using the following command:
     - **Debian/Ubuntu**: `sudo apt install git -y`
     - **CentOS/Red Hat**: `sudo yum install git -y`

2. **Clone the Repository**
   Run the following command in the terminal:
   ```bash
   git clone https://github.com/maulananais/WA-GroqAI.git
   ```

3. **Navigate to the Project Directory**
   ```bash
   cd WA-GroqAI
   ```

4. **Install Dependencies**
   ```bash
   npm install
   ```

5. **Set Up Groq API**
   Open the `key.json` file and insert your Groq API key:
   ```bash
   {
     "GROQ_API_KEY": "your_api_key_here"
   }
   ```

6. **Run the Bot**
   ```bash
   node index.js
   ```

---

### How to Use in Termux

1. **Install Node.js and Git**
   ```bash
   pkg install nodejs git
   ```

2. **Clone the Repository**
   ```bash
   git clone https://github.com/maulananais/WA-GroqAI.git
   ```

3. **Navigate to the Project Directory**
   ```bash
   cd WA-GroqAI
   ```

4. **Install Dependencies**
   ```bash
   npm install
   ```

5. **Set Up Groq API**
   Edit the `key.json` file and insert your Groq API key.

6. **Run the Bot**
   ```bash
   node index.js
   ```

---

### Documentation

For more information on how to use the Groq API, visit [Groq Documentation](https://groq.com/docs).

---

### Donations

If you would like to support the development of this project, feel free to donate via [Saweria](https://saweria.co/maulananais).

---

### Special Thanks To:
- Allah SWT
- My parents
- My girlfriend
- [Groq](https://groq.com) for their API
- [Node.js](https://nodejs.org) for the backend platform
- [Git](https://git-scm.com) for version control

---

### License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
