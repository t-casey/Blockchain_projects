# Building a Blockchain Ledger - Using PyChain and Streamlit


### **TO RUN:**
navigate to the folder and in the terminal run the Streamlit application by using:
> `streamlit run pychain.py`.

![terminal](images/terminal.png)

Once the program runs, it will open a new URL tab on your default web browser

![pychain-genblock](images/pychain-genblock.png)

---
### **TO USE:**
- Enter values for the *sender*, *receiver*, and *amount*
    - **sender input:** please enter a name (i.e. John) 
    - **receiver input:** please enter a name (i.e. Sally) 
    - **amount input:** please enter a float or int (i.e. 50.00 or 50) 
- You can also change the *Block Difficulty* which determines the hash difficulty for the miner in the form of number of zeros '0's needed at the beginning of the hash to add a new block
- then click the `Add Block` button. 

- Do this several times to store several blocks in the ledger.

### Notice how the Ledger updates to indicate the block has been added

![pychain-block1](images/pychain-block1.png)

### Play with the `Block Difficulty` and watch the Ledger grow
![pychain-block2](images/pychain-block2.png)

---
### **HOW TO VERIFY**
Verify the block contents and hashes 2 ways
1. Validate the chain by clicking the `Validate Chain` button
2. Use the `Block Inspector` drop-down menu to see specific block records

    ![pychain-verify](images/pychain-verify.png)
