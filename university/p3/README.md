# Diffie-Hellman Key Exchange with HMAC Authentication 🛡️  

This project is part of **Homework 3 (HW3)** for the **Information Security course** at **Amirkabir University of Technology**. It demonstrates how to implement **Diffie-Hellman key exchange** and use **HMAC (Hash-based Message Authentication Code)** to ensure message integrity and authenticity.

---

## Features
- **Secure Key Exchange:** Generates a shared secret key without directly transmitting private keys.
- **Message Authentication:** Uses HMAC to ensure the integrity and authenticity of messages.
- **SHA-256 Hash Function:** Implements SHA-256 as the hashing algorithm for HMAC.
- **Interactive Notebook:** A step-by-step Jupyter Notebook with detailed explanations.

---

## Prerequisites
Ensure you have the following:
- **Python 3.8+**
- **Jupyter Notebook**
- **cryptography** library  

To install the required library, run:
```bash
pip install cryptography
```

---

# How to Run the Notebook

## Clone the Repository
To get started, clone the repository to your local machine:

```bash
git clone https://github.com/srvn-nm/diffie-hellman-hmac.git  
cd diffie-hellman-hmac
```

---

## Launch the Jupyter Notebook
Next, launch the Jupyter Notebook environment:

```bash
jupiter notebook  
```

---

Once Jupyter opens, navigate to and open the `diffie_hellman_hmac.ipynb` file.

---

## Follow the Instructions
Run each cell in the notebook sequentially and take time to read through the explanations provided.

---

## Expected Output
The notebook will demonstrate:

- Generating a shared key using Diffie-Hellman.
- Computing HMAC to ensure message integrity and authenticity.
- Verifying that both parties generate the same shared key.

---

### Example Output:
You should see output similar to this:

```vbnet
Shared Key: [A numerical value]  
HMAC: [A hexadecimal hash value]  
```

---


## Folder Structure
Your project directory will have the following structure:

📂 diffie-hellman-hmac

│

├── 📄 diffie_hellman_hmac.ipynb # Jupyter notebook with explanations

└──  📄 README.md # Project documentation

---


## How to Verify the Results
- **Check Shared Key Consistency:** Ensure that both Alice and Bob generate the same shared key.
- **Validate HMAC:** Manually compute the HMAC using the shared key and message to confirm the values match.

---

## Contributing
Contributions are welcome! To contribute:

1. Fork the repository.
2. Create a new branch:
```bash
   git checkout -b feature-branch
  ```

---

## Make your changes and commit:
```bash
git commit -m "Describe your changes"
```

---

## Push to your branch:
```bash
git push origin feature-branch
```

---


## Author
**srvn-nm**

---


## Course and Assignment Information
This project is submitted as part of HW3 for the Information Security course at Amirkabir University of Technology.


---

## License
This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Acknowledgments
- **Cryptography Library:** [cryptography.io](https://cryptography.io)
- Inspired by Diffie-Hellman and HMAC for secure communication.
